### UIRecoderTest是一个ui测试框架
### 此处是安装好的

    npm install  // 安装依赖
    uirecorder start // 开始执行测试
    npm run javasdk // 打开测试服务
    双击根目录chromedriver 打开测试浏览器
    source run.sh sample/test.spec.js ( Linux|Mac ) 或 run.bat sample/test.spec.js ( Windows )

#### uirecorder mocha 安装步骤

#### 安装 uirecorder和mocha

    npm install uirecorder mocha -g
####  初始化项目

    uirecorder init
#### 下载依赖 这两个必须放在同一目录下
[Selenium Server & IEDriverServer][1]
[ChromeDriver][2]
#### 启动服务器

    java -jar selenium-server-standalone-3.6.0.jar  // 后面是下载的版本号
#### 双击打开chromedriver
#### 执行测试

    source run.sh sample/test.spec.js ( Linux|Mac ) 或 run.bat sample/test.spec.js ( Windows )








  [1]: http://selenium-release.storage.googleapis.com/index.html
  [2]: http://chromedriver.storage.googleapis.com/index.html
