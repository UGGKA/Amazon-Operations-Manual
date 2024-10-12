# 😈 亚马逊算法介绍

亚马逊搜索的核心逻辑就是让好的产品更容易被发现，也许现在已经是 A10 算法了，最近还加入了 AI 搜索 [COSMO](https://mp.weixin.qq.com/s?\_\_biz=MjM5NDQ3OTYyMg==\&mid=2247484324\&idx=1\&sn=adbd7b53232ee221b5c6c47b1a5c4cb1\&chksm=a68668cd91f1e1db5163c8bbea50d47814079df27324a78fbd0352e706523f04e88a1052eef3\&token=913595085\&lang=zh\_CN#rd)，但是核心逻辑是没变的，可以观看之前我发布的[《浅谈亚马逊A9算法》](https://www.bilibili.com/video/BV1EE411c7CW)

## COSMO 算法解读

点击阅读[《关于亚马逊 COSMO 算法的非官方解读》](https://mp.weixin.qq.com/s?\_\_biz=MjM5NDQ3OTYyMg==\&mid=2247484324\&idx=1\&sn=adbd7b53232ee221b5c6c47b1a5c4cb1\&chksm=a68668cd91f1e1db5163c8bbea50d47814079df27324a78fbd0352e706523f04e88a1052eef3\&token=913595085\&lang=zh\_CN#rd)

### 挖掘用户意图

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p><strong>挖掘用户意图</strong></p></figcaption></figure>

比如：一个孕妇想要购买一双鞋子，在亚马逊的搜索框里搜索“孕妇鞋”，COSMO 算法会基于 GPT 或者 OPT 等大语言模型中存储的大量“人类常识”以及询问“用户购买或共同购买的原因”，分析得出“防滑等功能对于孕妇的重要性”，然后推荐了防滑鞋等能够抓住孕妇需求痛点的产品从而提高转化率。

### 多轮导航

<figure><img src="../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption><p><strong>多轮导航</strong></p></figcaption></figure>

例如：对“露营”的搜索可能会引导到“充气床垫”的选择，然后细化为“露营用充气床垫”。COSMO 接着会提供各种类型的露营用充气床垫，以满足不同需求，如湖边露营、山地露营或者 4 人露营等。

### 亚马逊搜索常识图谱

<figure><img src="../.gitbook/assets/image (2) (1) (1).png" alt=""><figcaption><p><strong>亚马逊搜索常识图谱</strong></p></figcaption></figure>

看完上图，我们会发现这些内容和 SD 广告中的人群投放选择非常相似。分别从功能、场景、受众、季节、兴趣等方向入手。

我们以后可以在写 Listing 的适合可以加入也可以多考虑这些因素。

### 基于会话的购物

这个功能应该是指的前段时间曝光的 Rufus，以“问答”的方式，帮助顾客搜索、发现、研究和选购商品。

Rufus 在亚马逊 APP 顶部搜索框和商品详情页都有入口。比如我当我进入一件连衣裙的详情页之后，我懒得看详情页，我可以直接提问这件衣服适合一米八的人穿吗？Rufus 会根据买家评论、QA、Listing 等信息进行回答和推荐。

### 卖家优化方向

* 仔细挖掘产品的使用场景和人群，在 Listing 中要详细描述产品细致特点和使用场景；
* 挖掘更多细分的垂直赛道，满足客户个性化需求的产品，这样可以有效的避免同质化竞争；
* 利用 AI 工具进行 Listing 优化，基于 AI 逻辑让 COSMO 更加容易找到我们并推荐给客户；
* 布局好独立站，把自己的品牌“伪装”成一个让买家放心的品牌，让 COSMO 在调取数据的时候更容易发现我们的产品。
