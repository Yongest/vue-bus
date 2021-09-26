# vue-bus

@zhang_yong/vue-bus ：用最简洁的代码解决Vue各各组件通讯的问题！

1.npm 下载

    npm install @zhang_yong/vue-bus

2.导入

```
import Vue from 'vue'
import Bus from '@zhang_yong/vue-bus'
Vue.use(Bus)
```

3.使用

```
3.1 建立自定义事件，传递数据。
this.$bus.emit(event,val)   
```

```
3.2 监听（在页面任何地方写入）
this.$bus.on(event,(val)=>{
	// do something ...
})
```

