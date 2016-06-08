# Setting up the Project
#项目安装

First you'll need [Node.js](https://nodejs.org) and the package manager
that comes with it: [npm](https://www.npmjs.com/).
首先你需要安装Nodejs和它的包管理器npm.

Once you've got that working, head to the command line where we'll set
up our project.
保证它们能够正常的工作,然后我们设置我们的项目

## Clone the Tutorial
## 克隆这个教程

```
git clone https://github.com/reactjs/react-router-tutorial
cd react-router-tutorial
cd lessons/01-setting-up
npm install
npm start
```

Now open up [http://localhost:8080](http://localhost:8080)
现在打开[http://localhost:8080](http://localhost:8080)

Feel free to poke around the code to see how we're using webpack and npm
scripts to run the app.
我们使用了webpack和npm来运行这个项目.

You should see a "Hello React Router" message in the browser.
你应该在你的浏览器中看到了"Hello React Router"的信息.

## Make Some Changes
## 做一些修改

Open up `modules/App.js` and change the text to something like "Hello
<your name>". The browser automatically reloads with your new code.

打开`modules/App.js`然后改变其中的一点代码,就像这样:  "Hello
<your name>".浏览器会自动刷新你输入的新的代码.

---

[Next: Rendering a Router](../02-rendering-a-route/)
