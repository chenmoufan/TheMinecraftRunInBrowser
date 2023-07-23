## 中文版本
# 关于WebMC

这是一个使用JavaScript编写的基于WebGL的网页版minecraft。
现在只是更新到了1.1.2的测试版本

> Any application that can be written in JavaScript, will eventually be written in JavaScript.  
  --Jeff Atwood (co founder of Stack OverFlow)
  >> 任何能够用 JavaScript 实现的应用，最终都必将用 JavaScript 实现。  
     --Jeff Atwood（Stack OverFlow 的联合创始人）

这就是网上著名的“[Atwood定律](https://blog.codinghorror.com/the-principle-of-least-power/)”，看到这个定律后，一直跃跃欲试，想用js实现下最喜欢的mc。从0开始制作，不使用任何第三方库。虽然很多地方会尝试重复造轮子，但我喜欢这种从零开始随心所欲创造的感觉。~~(虽然现在啥都没有实现)~~

虽然知道这句话是从 _[the Principle of Least Power](https://www.w3.org/DesignIssues/Principles.html)_ 和[图灵完备](https://en.wikipedia.org/wiki/Turing_completeness)角度出发的 ~~(大概)~~，但咱还是要学PHPer来一句：JavaScript是世界上最好的语言。

# 如何运行

需要运行在服务器上，因为有纹理图片的跨域问题。  
若是有Node.js环境，那可以执行`node server.js`指令来运行一个简单的服务器，然后通过`http://localhost:3000/`进行访问。  
若是你正在使用的IDE有自带的静态服务器功能，那可以通过IDE在浏览器中打开`/index.html`文件。

## English
# About WebMC

This is a web-based version of Minecraft written in JavaScript based on WebGL.

Now it has only been updated to the test version of 1.1.2

>Any application that can be written in JavaScript, will eventually be written in JavaScript
--Jeff Atwood (co founder of Stack OverFlow)

>>Any application that can be implemented in JavaScript will ultimately be implemented in JavaScript.
--Jeff Atwood (co founder of Stack OverFlow)

This is the famous' Atwood's Law 'online（ https://blog.codinghorror.com/the-principle-of-least-power/ ）”After seeing this law, I have been eager to try it out and want to implement my favorite MC using JavaScript. Starting from 0, without using any third-party libraries. Although many places will try to make wheels repeatedly, I like the feeling of creating from scratch as you please~~ (Although nothing has been achieved now)~~

Although I know that this sentence is from_ [The Principle of Least Power]（ https://www.w3.org/DesignIssues/Principles.html ）_ And Turing Complete（ https://en.wikipedia.org/wiki/Turing_completeness ）From a perspective~~(roughly)~~, but we still need to learn PHPer: JavaScript is the best language in the world.


# How to run

Need to run on the server due to cross domain issues with texture images.
If there is a Node.js environment, you can execute the 'node server. js' command to run a simple server, and then use the` http://localhost:3000/ `Conduct access.
If the IDE you are using has its own static server function, you can open the '/index. html' file in the browser through the IDE.
