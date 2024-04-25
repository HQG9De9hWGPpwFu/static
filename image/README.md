# 关于 PicGo + Github 搭建免费图床


- 点击直达 [node 官网](https://nodejs.org)
- 点击直达 [jsdelivr 官网](https://www.jsdelivr.com)
- 推荐工具 [clean-mark](https://github.com/croqaz/clean-mark) 

## clean-mark 工具

- 安装
```
npm install clean-mark --global
```

- 语法
```
clean-mark {{$url}}
```

- 示例
```
clean-mark "https://juejin.cn/post/7267847052988628992"
```

- 安装时注意事项，即关于 node 版本兼容问题

```
PS E:\workspace>  npm install -g npm@10.5.2
npm ERR! code EBADENGINE
npm ERR! engine Unsupported engine
npm ERR! engine Not compatible with your version of node/npm: npm@10.5.2
npm ERR! notsup Not compatible with your version of node/npm: npm@10.5.2
npm ERR! notsup Required: {"node":"^18.17.0 || >=20.5.0"}
npm ERR! notsup Actual:   {"npm":"8.1.2","node":"v16.13.1"}
```
