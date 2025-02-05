# 投资新闻展示平台
项目基于 gin + vue2.0 + vuex + vue-router + element-ui + mysql + redis + gorm + go-redis + go-sql-driver/mysql + go-redis/redis-stack-go + go-redis/redis-stack-go/redisearch + go-redis/redis-stack-go/redisearch/redisearch-go + go-red
去建立的

# 安装步骤
## 后端安装
1. 修改.env.example 为 .env 并修改其中的数据库地址内容
2. go mod tidy 安装依赖
3. go run backend/migrations/main.go 创建表结构
4. go run backend/main.go 启动后端服务

##  前端安装
1. npm install 安装依赖
2. 修改.env.example 为 .env 并修改其中的后端地址内容
3. 编译项目
4. 部署项目
