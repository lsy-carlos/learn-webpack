# learn
学习
问题1：
npm run build 报错 Cannot find module 'webpack/lib/node/NodeTemplatePlugin'
解决：
第一步：npm config get prefix ，获取输出path“C:\Users\jaxGu\AppData\Roaming\npm”加上"\node_modules"用于第二步值
第二步：添加系统环境变量：NODE_PATH:C:\Users\jaxGu\AppData\Roaming\npm\node_modules
第三步：关掉终端，重新打开。