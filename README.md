# 目录结构
```
└─ src
   ├─ db.sqlite3
   ├─ hongjiecarservercenter
   │  ├─ asgi.py
   │  ├─ settings.py
   │  ├─ urls.py
   │  ├─ wsgi.py
   │  ├─ __init__.py
   │  └─ __pycache__
   │     ├─ settings.cpython-313.pyc
   │     ├─ urls.cpython-313.pyc
   │     ├─ wsgi.cpython-313.pyc
   │     └─ __init__.cpython-313.pyc
   ├─ manage.py
   └─ shop
      ├─ admin.py
      ├─ apps.py
      ├─ migrations
      │  ├─ __init__.py
      │  └─ __pycache__
      │     └─ __init__.cpython-313.pyc
      ├─ models.py
      ├─ templates
      │  └─ index.html
      ├─ tests.py
      ├─ views.py
      ├─ __init__.py
      └─ __pycache__
         ├─ admin.cpython-313.pyc
         ├─ apps.cpython-313.pyc
         ├─ models.cpython-313.pyc
         ├─ views.cpython-313.pyc
         └─ __init__.cpython-313.pyc
```
# 启动
```
python -m venv venv
env\Scripts\activate
pip install -r requirements.txt
python manage.py runserver

```

# 小结：
1. 克隆项目并进入目录。  
2. 创建并激活虚拟环境。  
3. 使用 pip install -r requirements.txt 安装依赖。  
4. 运行项目并测试。  
5. 使用 deactivate 退出虚拟环境。  
```