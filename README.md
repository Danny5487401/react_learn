# react

## Flux 架构及其主要特点
![flux stucture](image.png)

Flux 是一种构建用户界面的架构设计模式。Flux的核心思想就是数据和逻辑永远单向流动。


Redux 是一个使用叫做“action”的事件来管理和更新应用状态的模式和工具库,它以集中式Store（centralized store）的方式对整个应用中使用的状态进行集中管理，其规则确保状态只能以可预测的方式更新。

MobX 是一个身经百战的库，它通过运用透明的函数式响应编程（Transparent Functional Reactive Programming，TFRP）使状态管理变得简单和可扩展


## react 组件 (Component)
![react component](image-1.png)

React通过组件的思想，将界面拆分成一个个可以复用的模块，每一个模块就是一个React 组件。一个React 应用由若干组件组合而成，一个复杂组件也可以由若干简单组件组合而成。