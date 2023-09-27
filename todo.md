#### 写一个style lint

#### 写一个eslint

#### 怎么写一个npm包

#### webpack、 rollup、 gulp、 grunt如何选择

#### 浏览器缓存(304)

#### vite 

#### babel & ts 编译
- 有什么是babel能做但是ts不能做的

#### 怎么写npm包，怎么发包到私有源
- 私有源配置(.npmrc)
  - 业务前缀：
    eg:
    ```js
      // .npmrc
      legacy-peer-deps = true
      save-exact = true
      registry = https://registry.npmjs.org/
      @feng:registry = https://npm.partner.feng.cn/registry/
      @feng-op:registry = https://npm.partner.feng.cn/registry/
      @feng-ai:registry = https://npm2.feng.net/
      @feng-wb:registry = https://npm2.feng.net/
      @feng-design:registry = https://npm.partner.feng.cn/registry/
    ```
