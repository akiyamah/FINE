```
(venv) akiyamah@akiyamacbookpro FINE % pwd
/Users/akiyamah/Desktop/dev/FINE
(venv) akiyamah@akiyamacbookpro FINE % ls -l
total 16
-rw-r--r--  1 akiyamah  staff  4220  4 26 04:48 README.md
drwxr-xr-x  2 akiyamah  staff    64  4 26 04:25 backend
drwxr-xr-x  5 akiyamah  staff   160  4 26 04:48 docs
drwxr-xr-x  2 akiyamah  staff    64  4 26 04:26 frontend
drwxr-xr-x  6 akiyamah  staff   192  4 26 04:48 venv
(venv) akiyamah@akiyamacbookpro FINE % 
```

```
FINE/
├─ backend/
│   ├─ fine/
│   ├─ app/
│   ├─ manage.py
│   └─ requirements.txt
├─ frontend/
│   ├─ public/
│   ├─ src/
│   ├─ package.json
│   └─ package-lock.json
├─ docs/
├─ .git/
└─ venv/

```

```
source venv/bin/activate
pip install --upgrade pip
pip install django
pip install Pillow

django-admin startproject fine
```

ログイン機能について質問です。
ログイン機能はGoogleのアカウントでサインイン、ログインができて、アプリでアカウントを作成してログインすることができる様にしたいです。
まずは何をすべきから作業項目を箇条書きで教えて