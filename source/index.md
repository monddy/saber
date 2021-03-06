title: Saber
nav: about
---

{% rawblock %}
<section class="intro">
    <div class="slogan">
        <h2>模块化、组合式的前端移动框架</h2>
        <p>包含JavaScript模块、样式库、开发平台的完整解决方案</p>
    </div>

    <div class="feature">
        <p class="title">我们为您提供：</p>
        <ul>
            <li>16+个符合AMD规范的JavaScript模块</li>
            <li>基于Stylus与Autoprefixer的样式框架（rider）</li>
            <li>项目管理、包管理、代码检测、调试、构建等工具（edp）</li>
            <li>基于最佳实践快速构建应用的脚手架工具（edpx-mobile）</li>
        </ul>
        <p>
            <!--
            <a class="btn" href="#">入门教程</a>
            -->
            <a class="btn" href="#modules">获取模块</a></p>
        <div class="demo"></div>
    </div>

</section>

<section class="package">
    <a name="modules"></a>
    <h3>小而美的JavaScript模块</h3>
    <p class="sub-text">拥抱开源社区，符合AMD规范，根据业务场景自由组合</p>

    <a class="module" href="https://github.com/ecomfe/saber-dom" target="_blank">
        <strong>saber-dom</strong>
        DOM处理模块。
    </a>
    <a class="module" href="https://github.com/ecomfe/saber-emitter" target="_blank">
        <strong>saber-emitter</strong>
        事件发射器。
    </a>

    <a class="module" href="https://github.com/ecomfe/saber-lang" target="_blank">
        <strong>saber-lang</strong>
        提供对象合并、继承、柯里化、函数绑定的语言增强模块。
    </a>

    <a class="module" href="https://github.com/ecomfe/saber-string" target="_blank">
        <strong>saber-string</strong>
        字符串处理模块。
    </a>

    <a class="module" href="https://github.com/ecomfe/saber-env" target="_blank">
        <strong>saber-env</strong>
        设备环境探测模块，基于Zepto detect部分代码构建。
    </a>

    <a class="module" href="https://github.com/ecomfe/saber-tap" target="_blank">
        <strong>saber-tap</strong>
        解决移动端点击延迟问题，基于FastClick项目创建。
    </a>
    
    <a class="module" href="https://github.com/ecomfe/saber-promise" target="_blank">
        <strong>saber-promise</strong>
        Promise/A+实现，遵循1.1规范。
    </a>

    <a class="module" href="https://github.com/ecomfe/saber-uri" target="_blank">
        <strong>saber-uri</strong>
        URI处理模块。
    </a>

    <a class="module" href="https://github.com/ecomfe/saber-ajax" target="_blank">
        <strong>saber-ajax</strong>
        Promise风格的ajax封装，支持XMLHttpRequest2。
    </a>

    <a class="module" href="https://github.com/ecomfe/saber-run" target="_blank">
        <strong>saber-run</strong>
        Promise风格的动画效果模块。
    </a>

    <a class="module" href="https://github.com/ecomfe/saber-cookie" target="_blank">
        <strong>saber-cookie</strong>
        Cookie操作模块。
    </a>

    <a class="module" href="https://github.com/ecomfe/saber-matchmedia" target="_blank">
        <strong>saber-matchmedia</strong>
        判断Media Queries或监听其变化的模块。
    </a>

    <a class="module" href="https://github.com/ecomfe/saber-router" target="_blank">
        <strong>saber-router</strong>
        hash路由控制模块。
    </a>

    <a class="module" href="https://github.com/ecomfe/saber-viewport" target="_blank">
        <strong>saber-viewport</strong>
        页面视口管理模块，提供页面转场功能。
    </a>

    <a class="module" href="https://github.com/ecomfe/saber-scroll" target="_blank">
        <strong>saber-scroll</strong>
        提供区域滚动功能。
    </a>

    <a class="module" href="https://github.com/ecomfe/saber-firework" target="_blank">
        <strong>saber-firework</strong>
        简单MVP模式实现。
    </a>
</section>

<section class="package">
    <h3>基于Stylus的样式框架</h3>
    <p class="sub-text">自动处理浏览器兼容性、拥有众多便捷工具以及更易维护的代码组织方式</p>
    <img class="preview" src="pic/preview-archer-1.png" width="300" height="240" alt="众多使用的速写方法与工具Mixin" />
    <img class="preview" src="pic/preview-archer-2.png" width="300" height="240" alt="使用模块化的方式组织代码" />
    <img class="preview" src="pic/preview-archer-3.png" width="300" height="240" alt="通过Autoprefixer自动添加私有前缀" />
</section>
{% endrawblock %}
