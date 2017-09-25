1，state：整个应用的唯一状态树（唯一数据源）；

2，mutations：对应用状态的实际修改的地方，类似于事件，通过store调用commit\(name\)来提交；接收两个参数，模块化后接收第三个参数rootstate。

3，actions：业务处理，通常在这里提交mutations来变更状态。

4，getter：store中的计算属性，可接收两个参数（本模块state和整个应用的getters）。

最简单的store;

const store = new Vuex.Store\({

```
  state:{}
```

}

\#test

