CRM 项目划分：
1、权限系统
2、Stark组件
3、crm业务

项目结构
luffy_permission/
├── db.sqlite3
├── luffy_permission
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── manage.py
├── rbac            # 权限组件，便于以后应用到其他系统
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── templates
└── web            # 客户管理业务
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── models.py
    ├── tests.py
    └── views.py