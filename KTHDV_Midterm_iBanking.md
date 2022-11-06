# iBanking
>> **Team members:**
>>>		Hồ Minh Chí Tân- 519H0044
>>>		Nguyễn Dương - 519H0156
>>>		Nguyễn Thanh Hùng - 519H0170



> **Welcome,**
>> This is a app banking for student TDT-er to payment their tuition each semester. Everything is free, if you love our website, please introduce it to your friends, or any ideas you want. 
>
>> Before you continue, ensure you meet the following requirements:
>> - You have installed **VirtualEnv** 
>> - You have a basic understanding of **flask**
>> - You need to import necessary **LIBs**
> ---
>> **CREATE VENV (virtualenv : môi trường ảo)**
>> `py -3 -m venv .venv`
>> Ctrl+Shift+P -> Python: Select Interpreter
>> Browse : .venv\Scripts\python.exe
>> https://code.visualstudio.com/docs/python/tutorial-flask
>> Set-ExecutionPolicy Unrestricted -Force
>> .venv\scripts\activate
> ---
>> **INSTALL PIP**
>> `python -m pip install --upgrade pip`
> ---
>> **IMPORT NECCESSARY LIBS**
>> `pip install flask`
>> `pip install flask_moment`
>> `pip uninstall flask_bootstrap bootstrap_flask`
>> `pip install bootstrap-flask`
>> `pip install flask-wtf`
>> `pip install -U Flask-SQLAlchemy`
>> `pip install flask-login`
>---
>> **Run FLASK_APP**
>>  `flask --app app --debug run`
>---
>>  **Đường dẫn tới các trang**
>>>***Đăng nhập***:  *[http://127.0.0.1:5000/login](http://127.0.0.1:5000/login)*
>>---
>>>**Cần đăng nhập trước (required)**:
>>>>	***Đóng tiền*** :  *[http://127.0.0.1:5000/](http://127.0.0.1:5000/)*
>>>>	***Học phí (cá nhân)*** :  *[http://127.0.0.1:5000/hocphi](http://127.0.0.1:5000/hocphi)
>>>>	***Thông tin*** :  *[http://127.0.0.1:5000/thongtincanhan](http://127.0.0.1:5000/thongtincanhan)*
>>>>	***Đăng xuất*** :  *[http://127.0.0.1:5000/logout](http://127.0.0.1:5000/logout)*
>>---
>>>**Tạo dữ liệu để test:**
>>>> *[http://127.0.0.1:5000/createnewdata](http://127.0.0.1:5000/)*
>>---
>>>**Xem database**
>>>>	***User_DB*** :  *[http://127.0.0.1:5000/database/user](http://127.0.0.1:5000/)*
>>>>	***Account_DB*** :  *[http://127.0.0.1:5000/database/account](http://127.0.0.1:5000/)*
>>>>	***Tuition_DB*** :  *[http://127.0.0.1:5000/database/tuition](http://127.0.0.1:5000/)*
>>>>	***Payment_DB*** :  *[http://127.0.0.1:5000/database/payment](http://127.0.0.1:5000/)*
>>>>	***OTP_DB*** :  *[http://127.0.0.1:5000/database/otp](http://127.0.0.1:5000/)*