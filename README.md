# 部门系统原型

## 安装和运行
```shell
git clone https://github.com/ohmountain/department-prototype.git

cd department-prototype

composer install # 并依次输入数据库信息

php bin/console doctrine:database:create # 创建数据库
php bin/console doctrine:schema:update   # 更新表结构到数据库

php bin/console run:server               # 运行
```
