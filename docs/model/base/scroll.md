### 滚动 scroll
---

<view-scroll></view-scroll>

---

<highlight-code  lang="vue">
    <template>
        <div class='view-scroll'>
            <yun-scroll step='30' height='240' >
                <ul>
                    <li class='yun-li' v-for="i in 10" :key='i'>i</li>
                </ul>
                </yun-scroll>
                <yun-scroll step='30' height='240' direction='inline'>
                <ul class='inline'>
                    <li class='yun-li' v-for="i in 10" :key='i'>i</li>
                </ul>
            </yun-scroll>
        </div>
    </template>
</highlight-code> 

<table class='yun-table' style='width:100%;'>
    <thead>
        <tr>
          <th>属性</th>
          <th>类型</th>
          <th>默认值</th>
          <th>可选值</th>
          <th>说明</th>
        </tr>
    </thead>
    <tbody>
        <tr>
          <td>direction</td>
          <td>String</td>
          <td>vertical</td>
          <td>vertical/inline</td>
          <td>滚动方向</td>
        </tr>
        <tr>
          <td>step</td>
          <td>String/Number</td>
          <td>1</td>
          <td>-</td>
          <td>滚动速度</td>
        </tr>
        <tr>
          <td>height</td>
          <td>String/Number</td>
          <td>300</td>
          <td>-</td>
          <td>高度</td>
        </tr>
        <tr>
          <td>scrollId</td>
          <td>String</td>
          <td>scroll0</td>
          <td>-</td>
          <td>滚动ID</td>
        </tr>
    </tbody>
</table>