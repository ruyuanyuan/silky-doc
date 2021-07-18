### 按钮 button
---
<view-button></view-button>

---

<highlight-code  lang="vue">

        <template>
            <div class="yun-button">
                <yun-button >按钮</yun-button>
                    <yun-button color='#409EFF' fontColor='#fff'>按钮</yun-button>
                    <yun-button color='#67C23A' fontColor='#fff' borderColor='yellow'>按钮</yun-button>
                    <yun-button color='#E6A23C' fontColor='#fff'>按钮</yun-button>
                    <yun-button color='#F56C6C' radius='10' fontColor='#fff'>按钮</yun-button>
                    <yun-button type='colorliner'  fontColor='#fff'>按钮</yun-button>
                    <yun-button type='colorliner' :colors='["#409EFF","#67C23A","#F56C6C"]' fontColor='#fff'>按钮</yun-button>
                    <yun-button type='colorliner' :colors='["#E6A23C","#F56C6C","#E6A23C"]' direction='bottom' fontColor='#fff'>按钮</yun-button>
                    <yun-button type='colorliner' :colors='["#409EFF","#67C23A"]' direction='top' fontColor='#fff'>按钮</yun-button>
                    <yun-button type='colorliner' animate='shake' :colors='["#E6A23C","#F56C6C","#E6A23C"]' direction='bottom' fontColor='#fff'>按钮</yun-button>
                    <yun-button type='colorliner' animate='border' :colors='["#409EFF","#67C23A"]' direction='top' fontColor='#fff' >按钮</yun-button>
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
          <td>type</td>
          <td>String</td>
          <td>color</td>
          <td>color/colorliner</td>
          <td>纯色按钮/过渡色按钮</td>
        </tr>
        <tr>
          <td>color</td>
          <td>String</td>
          <td>#fff</td>
          <td>-</td>
          <td>背景颜色</td>
        </tr>
        <tr>
          <td>fontColor</td>
          <td>String</td>
          <td>#666</td>
          <td>-</td>
          <td>文字颜色</td>
        </tr>
        <tr>
          <td>borderColor</td>
          <td>String</td>
          <td>#efefef</td>
          <td>-</td>
          <td>边框颜色</td>
        </tr>
        <tr>
          <td>radius</td>
          <td>String/Number</td>
          <td>4</td>
          <td>-</td>
          <td>圆角</td>
        </tr>
        <tr>
          <td>colors</td>
          <td>Array</td>
          <td>["#667eea", "#bf8bf5", " #667eea"]</td>
          <td>-</td>
          <td>type为colorliner时生效,色值数组,数组长度必须>=2,与color属性冲突</td>
        </tr>
        <tr>
          <td>direction</td>
          <td>String</td>
          <td>left</td>
          <td>left/top/right/bottom</td>
          <td>type为colorliner时生效,过渡色方向</td>
        </tr>
        <tr>
          <td>animate</td>
          <td>String</td>
          <td>shake</td>
          <td>shake/border</td>
          <td>按钮动画</td>
        </tr>
    </tbody>
</table>


