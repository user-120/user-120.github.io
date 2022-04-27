<!-- _coverpage.md -->

# Docsify使用指南 

> 💪Docsify使用指南，使用Typora+Docsify打造最强、最轻量级的个人&团队文档。

 简单、轻便 (压缩后 ~21kB)
- 无需生成 html 文件
- 众多主题
- 试试


[开始使用 Let Go](/README.md)

<div id="example">
<!-- 在docsify中隐藏，在其他地方显示（如GitHub）。 -->
<p v-if="false">Text for GitHub</p>

<!-- Sequenced content (i.e. loop)-->
<ul>
  <li v-for="i in 3">Item {{ i }}</li>
</ul>

<!-- JavaScript expressions -->
<p>2 + 2 = {{ 2 + 2 }}</p>
</div>
<!-- Vue 2.x  -->
<script type="text/javascript">
  new Vue({
    el: '#example',
    // Options...
  });
</script>
