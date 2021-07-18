> 安装

使用 npm 的方式安装

<yun-vcode lang='js'>npm i yun-silky -S</yun-vcode>

> 引入

你可以引入整个 Yun-Silky，或是根据需要仅引入Yun-Silky部分组件。

全局引入


<yun-vcode >
    import Vue from 'vue';
    import YunUI from 'yun-silky'
    import 'yun-silky/lib/silky.css'
    import App from './App.vue';

    Vue.use(YunUI);

    new Vue({
      el: '#app',
      render: h => h(App)
    });
</yun-vcode>


局部引入

<yun-vcode >
    import Vue from 'vue';
    import { Button } from 'yun-silky';
    import App from './App.vue';

    Vue.component(Button.name, Button);
    /* 或写为
    * Vue.use(Button)
    */

    new Vue({
        el: '#app',
        render: h => h(App)
    });
</yun-vcode >