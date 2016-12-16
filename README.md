# proxy-finder
代理获取脚本。异步请求，全部高匿，分http和https，储存为json文件。

## 前置
```
npm install -g superagent
npm install -g superagent-charset
npm install -g superagent-proxy
npm install -g cheerio
```
## 使用方法
```
node proxy-finder.js
```
当前目录会生成proxy.json来记录获取到的proxy

##特点
1. 使用node.js异步获取和测试，并过滤超时代理，效率高。一般脚本运行完成只需十几秒。
2. 从xicidaili和kuaidaili两家比较靠谱的代理发布站获取，亲测国内可用。
3. 双重测试，分别针对http和https做有效性测试，方便不同需求使用。
