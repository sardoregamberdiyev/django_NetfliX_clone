# Django Netflix Clone
Bu mashhur Netflix video oqim saytining kloni. Django yordamida yaratilgan va TMDB API ma'lumotlarini qayta ishlash uchun so'rovlar kutubxonasidan foydalanadi.

![](https://github.com/steve-njuguna-k/Django-Netflix-Clone/blob/master/Screenshot.PNG)

## Contributors
- [Faith Njoki](https://github.com/faithnjoki)
- [Steve Njuguna](https://github.com/steve-njuguna-k)

## Requirements
Foydalanuvchi quyidagi funktsiyalarni bajarishi mumkin:

- Foydalanuvchi mavjud bo'lgan turli filmlar va teleko'rsatuvlarni ko'rishi mumkin.
- Foydalanuvchi film tavsifi va uning joriy reytingini ko'rishi mumkin.
- Foydalanuvchi film yoki teleko'rsatuv treylerini tomosha qiladi.

## Installation / Setup instruction
Ilova ishlashi uchun quyidagi o'rnatishlarni talab qiladi:
- pip
- gunicorn
- django
- postgresql
- requests

## Technologies Used
- python 3.9.6

## Project Setup Instructions
1) git clone the repository 
```
https://github.com/steve-njuguna-kDjango-Netflix-Clone.git
```
2. cd into Django-Netflix-Clone
```
cd Django-Netflix-Clone
```
3. create a virtual env
```
py -m venv env
```
4. activate env
```
env\scripts\activate
```
5. CMD-ni oching va bog'liqliklarni o'rnating
```
pip install -r requirements.txt
```
6. Yaratish Migrations
```
py manage.py makemigrations
```
7. Migrate DB
```
py manage.py migrate
```
8. Ilovani ishga tushirish
```
py manage.py runserver
```

## Known Bugs
- Hozircha maʼlum xatoliklar yoʻq, lekin agar siz xatolikni aniqlasangiz, tortib olish soʻrovlariga ruxsat beriladi

© 2023 Egamberdiyev Sardor
