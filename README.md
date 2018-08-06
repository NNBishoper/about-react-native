# about-react-native

- React Native背景

为什么取名React Native？React是什么？Native又是什么？  

### React

- React 是由Facebook推出的一个JavaScript框架，主要用于前段开发。
- React 采用组件化方式简化Web开发
  - DOM:每个HTML界面可以看做一个DOM
  - 原生的web开发方式，HTML一个文件，javaScript一个文件，文件分开，就会导致修改起来比较麻烦。
  - 可以把一组相关的HTML标签和JavaScript单独封装到一个组件类中，便于复用，方便开发。
- React 可以高效的绘制界面
  - 原生的Web,刷新界面(DOM)，需要把整个界面刷新.
  - React只会刷新部分界面，不会整个界面刷新。
  - 因为React独创了Virtual DOM机制。Virtual DOM是一个存在于内存中的JavaScript对象，它与DOM是一一对应的关系，当界面发送变化时，React会利用DOM Diff算法，把有变化的DOM进行刷新.
- React是采用JSX语法，一种JS语法糖，方便快速开发。

### Native

想要了解Native是什么，需要了解下开发App有哪些开发模式：

- Native App

- Web App

- Hybrid App

- Weex

- React Native
