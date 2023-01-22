# chatbot AI project
ในการ Run source code  ให้ทำตามขั้นตอน ดังนี้


- ติดตั้ง virtual environment โดยเรียกใช้สิ่งต่อไปนี้

```
cd your-folder-project-name

virtualenv chatenv

source chatenv/bin/activate
```
- ติดตั้ง libraries ที่จำเป็นทั้งหมด
```
pip3 install nltk

pip3 install numpy

pip3 install keras

pip3 install tensorflow

pip3 install flask

Pip3 install pythainlp
```
- รัน  train_chatbot.py เพื่อสร้าง model
```
python3 train_chatbot.py
```
- รัน app.py เพื่อสร้างส่วนหน้า page ของ Flask บนพอร์ต 8888 (หรือพอร์ตใดๆ ที่ app ชี้ไป)
```
python3 app.py
```
