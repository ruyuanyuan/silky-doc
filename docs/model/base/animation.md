### 动画 animation

---

<view-animation></view-animation>

---

<highlight-code  lang="vue">
    <template>
        <div class='view-animation'>
            <yun-animation class='yun-ani' name='shake' event='hover' count='infinite' duration='1'>
                <div class='yun-block'>
                    <img src="/img/animate.png" alt="">
                    <span>shake</span>
                </div>
            </yun-animation>
            <yun-animation class='yun-ani' name='shake-inline' event='hover' count='infinite' duration='1'>
                <div class='yun-block'>
                    <img src="/img/animate.png" alt="">
                    <span>shake-inline</span>
                </div>
            </yun-animation>
           <yun-animation class='yun-ani' name='shake-vline' event='hover' count='infinite' duration='1'>
                <div class='yun-block'>
                    <img src="/img/animate.png" alt="">
                    <span>shake-vline</span>
                </div>
            </yun-animation>
            <yun-animation class='yun-ani' name='light' event='hover' count='infinite' duration='0.8'>
                <div class='yun-block'>
                    <img src="/img/animate.png" alt="">
                    <span>light</span>
                </div>
            </yun-animation>
            <yun-animation class='yun-ani' name='jump' event='hover' count='infinite' duration='0.4'>
                <div class='yun-block'>
                    <img src="/img/animate.png" alt="">
                    <span>jump</span>
                </div>
            </yun-animation>
            <yun-animation class='yun-ani' name='stretch' event='hover' count='1' duration='0.4'>
                <div class='yun-block'>
                    <img src="/img/animate.png" alt="">
                    <span>stretch</span>
                </div>
            </yun-animation>
            <yun-animation class='yun-ani' name='hert' event='hover' count='infinite' duration='0.4'>
                <div class='yun-block'>
                    <img src="/img/animate.png" alt="">
                    <span>hert</span>
                </div>
            </yun-animation>
            <yun-animation class='yun-ani' name='pulse' event='hover' count='1' duration='0.4'>
                <div class='yun-block'>
                    <img src="/img/animate.png" alt="">
                    <span>pulse</span>
                </div>
            </yun-animation>
            <yun-animation class='yun-ani' name='twinkle' event='hover' count='infinite' duration='1'>
                <div class='yun-block'>
                    <img src="/img/animate.png" alt="">
                    <span>twinkle</span>
                </div>
            </yun-animation>
            <yun-animation class='yun-ani' name='swing' event='hover' count='infinite' duration='0.4'>
                <div class='yun-block'>
                    <img src="/img/animate.png" alt="">
                    <span>swing</span>
                </div>
            </yun-animation>
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
          <td>name</td>
          <td>String</td>
          <td>-</td>
          <td style='max-width:300px;word-break:break-all;'>shake/shake-inline/shake-vline/light/jump/stretch/hert/pulse/twinkle/swing</td>
          <td>动画名称</td>
        </tr>
        <tr>
          <td>event</td>
          <td>String</td>
          <td>-</td>
          <td>click/hover</td>
          <td>触发事件</td>
        </tr>
        <tr>
          <td>count</td>
          <td>String/Number</td>
          <td>2</td>
          <td>数值/infinite(无限循环)</td>
          <td>动画执行次数</td>
        </tr>
        <tr>
          <td>duration</td>
          <td>String/Number</td>
          <td>2</td>
          <td>-</td>
          <td>执行时长(s)</td>
        </tr>
        <tr>
          <td>delay</td>
          <td>String/Number</td>
          <td>0</td>
          <td>-</td>
          <td>延迟执行时长(s)</td>
        </tr>
        <tr>
          <td>animationType</td>
          <td>String</td>
          <td>ease-in-out</td>
          <td>linear/ease/ease-in/ease-out/ease-in-out/cubic-bezier(n,n,n,n)</td>
          <td>动画执行形式</td>
        </tr>
    </tbody>
</table>