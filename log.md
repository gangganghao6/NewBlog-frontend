### 2022年8月27日：创建项目
### 2022年8月28日：生成https密匙
[vite集成https，并安装本地自签名证书](https://zhuanlan.zhihu.com/p/551720193)
### 2022年9月3日：
1. D:\IDEA\WebStorm 2021.1.3\plugins\JavaScriptLanguage\languageService\eslint\bin\eslint8-plugin.js
   文件第139行
   ```javascript
   parsedCommandLineOptions = this.libOptions.parse != null
   //this.libOptions=>this.libOptions.parse
   ```
2. 工程化设置
3. 删除github上的keys文件夹
   ```git
   git rm keys -r
   git commit -m "删除keys文件夹"
   git push
   ```
### 2022年10月23日：建立了目录总体架构，安装了所有需要的库，添加了.env文件作为配置文件，添加了`<Suspense>`的支持，编写了所有网络请求代码。

### 2022年10月24日：编写在线聊天逻辑