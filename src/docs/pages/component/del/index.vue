<template>
    <doc-component
        :page="page"
        :hasPadding="true"
    >
    <script type="text/markdown">
    # 删除的文本 `<ui-del>`
    
    <doc-component-status page="del"></doc-component-status>

    <doc-component-not-recommended date="2019年4月6日" plan="使用<del>标签替代"></doc-component-not-recommended>

    [[[开始]]]

    将一段内容标记为废弃的，这是内联元素。

    :::vue
    @name:使用
    ---
    #demo
    >tpl
    <ui-del>删除的文本</ui-del>
    :::

    [[[形态]]]

    #### 支持

    |类型|支持|默认|
    |-|-|-|
    |尺寸|不支持|-|
    |色彩|不支持|-|
    |状态|不支持|-|

    <a href="/guide/status.html">查看形态文档</a> / <a href="/design/color.html">查看色彩文档</a>


    [[[源码]]]

    <iframe src="/report/coverage/lib/components/del/index.vue.html" name="codeFrame" frameborder="0" onload="this.height=codeFrame.document.body.scrollHeight"></iframe>
    </script>
    </doc-component>
</template>
 
<script>
import DocComponent                from 'Docs/common/DocComponent.vue';

export default {
    data : function () {

        return {
            page : 'del'
        };

    },
    components : {
        'doc-component' : DocComponent
    }
};
</script>

<style lang="less">
</style>
