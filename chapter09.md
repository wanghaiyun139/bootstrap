## 一．路径组件

路径组件也叫做面包屑导航。

```
<ol class="breadcrumb">
<li><a href="#">首页</a></li>
<li><a href="#">产品列表</a></li>
<li class="active">韩版 2015 年羊绒毛衣</li>
</ol>
```

## 二．分页组件

分页组件可以提供带有展示页面的功能。

```
//默认分页
<ul class="pagination">
<li><a href="#">&laquo;</a></li>
<li><a href="#">1</a></li>
<li><a href="#">2</a></li>
<li><a href="#">3</a></li>
<li><a href="#">4</a></li>
<li><a href="#">5</a></li>
<li><a href="#">&raquo;</a></li>
</ul>
//首选项和禁用
<li class="active"><a href="#">1</a></li>
<li class="disabled"><a href="#">2</a></li>
//设置尺寸，四种 lg、默认、sm 和 xs
<ul class="pagination pagination-lg">//翻页效果
<ul class="pager">
<li><a href="#">上一页</a></li>
<li><a href="#">下一页</a></li>
</ul>
//对齐翻页链接
<ul class="pager">
<li class="previous"><a href="#">上一页</a></li>
<li class="next"><a href="#">下一页</a></li>
</ul>
//翻页项禁用
<li class="previous disabled"><a href="#">上一页</a></li>
```

## 三．标签 

```
//在文本后面带上标签
<h3>标签 <span class="label label-default">new</span></h3>
//不同色调的标签
<h3>标签 <span class="label label-primary">new</span></h3>
<h3>标签 <span class="label label-success">new</span></h3>
<h3>标签 <span class="label label-info">new</span></h3>
<h3>标签 <span class="label label-warning">new</span></h3>
<h3>标签 <span class="label label-danger">new</span></h3>
```

## 四．徽章 

```
//未读信息数量徽章
<a href="#">信息 <span class="badge">10</span></a>
//按钮中使用徽章
<button class="btn btn-success">
提交 <span class="badge">3</span>
</button>
//激活状态自动适配色调
<ul class="nav nav-pills">
<li class="active">
<a href="#">首页 <span class="badge">2</span></a>
</li>
<li><a href="#">资讯</a></li>
</ul>
```

