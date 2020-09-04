# 前端全栈开发

## 开发步骤

#### 全局安装nest.js

```
yarn global add @nestjs/cli
```

#### 使用nest.js创建server文件夹

```
nest new server
```

#### 因为涉及两个服务端模块，使用以下命令生成nest子模块

- 进入到server文件夹

```
nest g app (admin) //可自定义
```

#### 数据库公用，创建一个数据库模块

```
nest g lib db
// @libs 可选
```

#### 运行admin服务

```
nest start -w admin
```

### 数据库模块开发

#### 安装 

`nestjs-typegoose  `

`@typegoose/typegoose`

`mongoose`

`@types/mongoose`

#### 在admin模块里添加子模块

`nest g mo -p admin users`

#### 添加控制器

`nest g co -p admin users`