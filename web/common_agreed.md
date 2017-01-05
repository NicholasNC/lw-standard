# html中class的命名顺序

1. 主要以 [团队规范文档](http://alloyteam.github.io/CodeGuide/#css-declaration-order) 中的css属性声明顺序为参照
2. 在 1 的基础上，在最后加上一些特殊功能的class，例如：形状、自定义标识等等
3. 举个栗子： `<header class="flex-box jc-ce ai-ce fd-col b-border font-c1 bg-c1 oct-read-header">`
   * `flex-box jc-ce ai-ce fd-col b-border font-c1 bg-c1` ，这几个都是按照css属性声明顺序来写的，从左到右分别是，display、border、color、background
   * `oct-read-header` 这个class是自定义标识，用于对前面的class进行修改，或者添加新的css属性，或者作为css的上下文，或者给js使用
4. 再来一个栗子： `<em class="linewidth4 expression thanks"></em>`
   * `linewidth4` 是定义了通用的行间距（用margin-bottom定义）
   * `expression thanks` 都是自定义标识
5. **特别注意：**上述栗子中的通用class会有表动，详细参考下面介绍的 `public.scss` 和 `comm.scss` 两个文件

# 通用样式文件

## ----public.scss----

```
// ********说明********
// public.scss，这份文件主要定义了一些通用的布局样式，
// 以及一些特殊的功能性样式
// 
// 定义的顺序：
//      1. reset
//      2. 按照规范文档中，css属性声明顺序
// 
// 注：
//      本文件使用的是scss的语法
//        
// ********
```

## ----comm.scss----

```
// ********说明********
// comm.scss，这份文件主要定义了一些通用的数值样式
// 使用前应该和设计沟通好整个设计稿的主题颜色、字体大小、行间距等
// 
// 定义的顺序：
//      1. 按照规范文档中，css属性声明顺序
//      
// 要求：
//      1. 颜色必须标注大概是什么颜色
// 
// 注：
//      本文件使用的是scss的语法
//        
// ********
```

## ----说明----

**具体代码见** [附录](./commom_agreedAnnex.md)

## ----各级title----

# 我是H1

## 我是H2

### 我是H3

#### 我是H4

##### 我是H5

###### 我是H6



