# 自研脚手架开发

### 脚手架初始化工作&lerna操作
##### lerna 核心操作
**lerna create** [https://github.com/lerna/lerna/tree/v3.22.1/commands/create#readme]
> 创建 package
**lerna add** [https://github.com/lerna/lerna/tree/v3.22.1/commands/add]
> 为 package 安装依赖
**lerna link** [https://github.com/lerna/lerna/tree/v3.22.1/commands/link]
> 给开发的包中有互相依赖作关联
**lerna clean**
> 清空包的依赖, 清除 node_modules
**lerna bootstrap**
> 安装依赖并关联软连接
**lerna exec** [https://github.com/lerna/lerna/tree/v3.22.1/commands/exec]
> 执行 npm 命令
**lerna publish**
> 发布包

