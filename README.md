# 个人博客开发日志

该日志主要用于记录使用Hydejack 9模板时的自定义规则。

## 分类
### 关于大类blog和list
对于blog大类，我尚不明确；

list是用于定义新的分类标签的。

### 关于分类标签categories和tags
* 相同点：

1. 两者都可以以标签的形式标注在每一篇post标题下的说明文字中；
2. 点击说明文字中的标签，可以自动跳转至相应的界面，列出所有隶属于该标签下的所有posts。并且可以在'_featured_categories'或'_featured_tags'文件夹下的配置文件中选择是否按年份整理posts；
3. 两者都可以在侧边栏中设置选项以快速跳转。

* 不同点：

1. posts可以通过在根目录直接放入文件夹中（文件夹的名字需要与'_featured_categories'文件夹中配置文件名以及配置文件中对应名字相同）以自动加入某一个categories分类，而tags不可以（待考证）。
2. 两者在说明文字中的先后顺序和修饰词不同，categories在前，修饰词可以在'_data/strings.md'中自定义。

* 我将以categories作为侧边栏的快速跳转，而tags作为以posts内容为根据的分类标签。
