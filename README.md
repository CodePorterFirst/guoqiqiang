laravel环境
composer install -vvv
复制.env文件，配置数据库
执行php artisan key:generate 产生key
执行php artisan base:reset 生成数据库和默认数据
执行php artisan jwt:secret 生成jwt key

vue环境
cd resources/js/
npm install
修改.env.development和.env.production中接口主地址
npm run serve 开发环境
npm run build 生产环境
