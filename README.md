## 安装

要求PHP>=7.4  
- git clone https://github.com/w3yyb/laravel-admin-skeleton.git
- composer install -vvv
- cp .env.example .env
- php artisan key:generate
- php artisan migrate（执行前需要配置好数据库连接）
- php artisan db:seed（执行前需要配置好数据库连接）
- php artisan serve（打开 http://127.0.0.1:8000 即可浏览）

## 查看

- 路由：http://127.0.0.1:8000/admin
- 认证：账号 admin，密码 admin

## 参考
-https://blog.p2hp.com/archives/7282  
