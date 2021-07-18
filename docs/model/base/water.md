### 水波 water

---

<view-water></view-water>

---

<highlight-code  lang="vue">
        <template>
            <div class="yun-water">
                <yun-water width="100" height="100" number="40" radius="30%"> </yun-water>
                <yun-water width="100" height="100" number="40">
                    <span class="water-number">40%</span>
                </yun-water>
                <yun-water width="100" height="100" number="30" type="drop">
                    <span class="water-number">30%</span>
                </yun-water>
            </div>
        </template>
        <!-- css -->
        .water-number{
            color:rgb(7, 177, 245);
            font-size:20px;
        }
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
          <td>default</td>
          <td>default/drop</td>
          <td>类型</td>
        </tr>
        <tr>
          <td>shadowColor</td>
          <td>String</td>
          <td>#0cffff</td>
          <td>-</td>
          <td>边框投影颜色</td>
        </tr>
        <tr>
          <td>waterColor</td>
          <td>Array</td>
          <td>[#1cf3f3,#0cffffee]</td>
          <td>-</td>
          <td>水波颜色</td>
        </tr>
        <tr>
          <td>width</td>
          <td>String/Number</td>
          <td>20</td>
          <td>-</td>
          <td>宽度</td>
        </tr>
        <tr>
          <td>height</td>
          <td>String/Number</td>
          <td>20</td>
          <td>-</td>
          <td>高度</td>
        </tr>
        <tr>
          <td>number</td>
          <td>String/Number</td>
          <td>50</td>
          <td>-</td>
          <td>水波高度</td>
        </tr>
        <tr>
          <td>radius</td>
          <td>String</td>
          <td>50%</td>
          <td>-</td>
          <td>圆角</td>
        </tr>
    </tbody>
</table>

