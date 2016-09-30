# 设计稿目录结构
    项目名称
    │
    ├── 【11】首页
    │   ├── 【A】首页【v0.1】.psd
    │   └── 【A】首页【v0.1】.jpg
    ├── 【12】全部商品分类
    ├── 【13】最新揭晓
    ├── 【14】个人中心
    │   ├── 【14-21】我的钱包
    │   │   ├── 【14-21-31】我的账户
    │   │   │   ├── 【A】我的账户【v0.1】.psd
    │   │   │   └── 【A】我的账户【v0.1】.jpg
    │   │   ├── 【14-21-32】我的佣金
    │   │   │   ├── 【14-21-32-41】邀请明细
    │   │   │   │   ├── 【A】邀请明细（有状态）【v0.1】.psd
    │   │   │   │   ├── 【B】邀请明细（无状态）【v0.1】.psd
    │   │   │   │   ├── 【A】邀请明细（有状态）【v0.1】.jpg
    │   │   │   │   └── 【B】邀请明细（无状态）【v0.1】.jpg
    │   │   │   └── 【14-21-32-42】佣金明细
    │   │   │       ├── 【A】佣金明细（有状态）【v0.1】.psd
    │   │   │       ├── 【B】佣金明细（无状态）【v0.1】.psd
    │   │   │       ├── 【A】佣金明细（有状态）【v0.1】.jpg
    │   │   │       └── 【B】佣金明细（无状态）【v0.1】.jpg
    │   │   ├── 【14-21-33】充值
    │   │   └── 【14-21-34】佣金
    │   ├── 【14-22】幸运记录
    │   ├── 【14-23】我的团购
    │   └── 【14-24】收货地址
    └── 【15】购物车
**具体说明：**
1. 每一层都创建一个文件夹，叶子文件夹（直接包涵设计稿的文件夹，创建两个文件夹，一个是jsp，一个是psd，分别给产品和前端看）
1. `【11】首页` 表示是第一层的第一个，`【13】最新揭晓` 表示第一层的第三个，`【14-21】我的夺宝` 表示第一层第四个里面的第二层第一个。
1. 如果一个跳转按钮要跳转回到首页，直接在按钮旁边标注 `跳转到【11】` *（在jpg文件中标注）*
1. 每个psd文件的命名规则：
  - 【A】佣金明细（有状态）【v0.1】.psd
  - 【状态代号】文件名字（状态描述）【版本号】.psd
    - 【状态代号】——从A开始命名，就是只有一种状态，也要写上【A】，并且字母必须**大写**
    - 文件名字（状态描述）——状态描述，描述状态的具体信息，可写可不写
    - 【版本号】——以**小写**字母v开头，分两段，第一段是大版本，第二段是小版本，用`.`号分割
  - jpg文件与psd文件同名
1. **特别说明**：前端不保留设计稿的迭代版本，只保留最新版本，设计稿的版本管理由设计师负责。
1. 如下图所示（待完善）


# 设计稿规范
开始做设计稿前，先出规范文档。规范文档包括网站的主要用到的颜色、主要字体大小、主要豆腐块之间的上下左右间距。

# 颜色规范
写出整个网站主要用到的颜色，颜色编号直接用颜色的值，例如 `#f5f5f5` ，并且在设计稿中标明。
例子如下图：（待完善）

# 字体大小规范
写出整个网站主要字体大小，字体编号直接用字号，例如 `24px` ，并且在设计稿中标明，**如果是加粗、斜体等也要特别标注**
例子如下图：（待完善）

# 豆腐块间距规范
标出整个网站主要豆腐块的间距大小，编号要以L-开头，例如 `L-1  12px      L-2  16px      L-3  20px` 
例子如下图：（待完善）