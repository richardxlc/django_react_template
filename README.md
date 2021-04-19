# django_react_template
vscode编辑
backend:django;django-rest-framework;django-allauth;
core app: serializer定制django rest framework的user serializer, 除了返回token,还返回user
frontend:react store文件里实现登录逻辑，并存储token和username


https://github.com/richardxlc/django_react_template 下载
解压
将含主要文件的文件夹改名为react_ecommerce_rich
vscode打开文件夹react_ecommerce_rich
在terminal中建立虚拟环境：PS E:\Ecommerce_react\react_ecommerce_rich> python -m venv env
激活环境：.\env\Scripts\activate
cd backend
pip install -r requirements.txt
删除db.sqlite3数据库文件（后期会在github中删除）
python manage.py makemigrations
python manage.py migrate
python manage.py createsupersuer
python manage.py runserver
cd backend (package.json所在文件夹)
npm install （安装package.json内的dependicies）
http://localhost:3000/ 访问正常 可登录 可注册
