# 藏品管理系统
>ajax需要把get改成post的地方都已经做了标注

## filter.json
>filter_name => 筛选项的名字 <br/>
>filter_active => 当前激活的筛选项 <br/>
>前三项为固定需要的 热门/最新/全部 其他为动态
## currentPage.json
>total => 分页总条数  <br/>
>pageSize => 一页显示几条数据

## collection.json
>imgUrl => 图片地址 <br/>
>url => 链接地址 <br/>
>title => 图片标题 <br/>
>author => 作者 <br/>
>department => 系别 <br/>
>proportion => 用来判断图片高宽比例 默认为 true

## hotCollection.json
>热门藏品不超过8个 否则不予显示
