<div align="center">
    <img src="/img/PoleStar.png" width="160px" />
    <h1>✨  PoleStar Chat</h1>
    <p>
        <strong>提高人类智能的助手</strong>
    </p>
    <h4>
        <a href="https://mcousdyt7h.feishu.cn/wiki/wikcn1bcFiMEwq6ucwowFsERjkb">用户手册</a>
        <span> · </span>
        <a href="https://discord.gg/esyCEGhmq9">Discord</a>
    </h4>
</div>

<h2> 💻 下载 </h2>

| MacOS  | Windows | Linux |
| ------------- | ------------- | ------------- |
| [Mac Intel](https://github.com/thinkingjimmy/PoleStarChat/releases/download/V0.0.10/PoleStarChat_x86_v0.0.10_zh_CN.dmg) · [Mac M1/M2](https://github.com/thinkingjimmy/PoleStarChat/releases/download/V0.0.10/PoleStarChat_arm64_v.0.0.10_zh_CN.dmg) | 敬请期待 | 敬请期待 |

## 🤖 预设 100 多个 Bot
你可以像使用其他 IM 软件一样，使用 @ 的方式快速调用 AI 指令，就像是在群聊里 @ 人一样便捷。我们目前支持 100 多个 AI Bot，涵盖教育、写作、娱乐等主题，比如你可以使用塔罗牌大师给你测试今日运势，这样你就不用去学习和设置繁琐的 AI Prompt：

| 预设 100 多个 Bot  | 塔罗牌大师 Bot  |
| ------------- | ------------- | 
| <img width="600" src='https://github.com/thinkingjimmy/PoleStarChat/assets/37492595/720642fc-29ab-4556-a845-d225ebf75329'/> | <img width="600" src='https://github.com/thinkingjimmy/PoleStarChat/assets/37492595/45ece994-2181-4cec-909b-6a8e36bfa4f4' /> |

另外，PoleStar Chat 跟其他同类产品还有一个区别，你可以在一个 Channel 里 AT 多个 Bot，这样你可以基于一个问题，与多个虚拟 Bot 进行讨论，比如跟柏拉图和加缪等人，来一场关于虚无主义的讨论。亦或者是让 Blog Writer 写一段中文稿，然后让 English Translator 翻译成英文：
| 什么是虚无主义?  | Blog Writer  |
| ------------- | ------------- | 
| <img width="600" src='https://github.com/thinkingjimmy/PoleStarChat/assets/37492595/e3283608-d06c-4613-8246-3cbbd0cfd5a8'/> | <img width="600" src='https://github.com/thinkingjimmy/PoleStarChat/assets/37492595/35b209d1-3e81-48f2-8adf-450f828a2684' /> |

## 🌅 支持文生图模型
另外，我们除了支持文本模型外，还支持文生图模型，并且为了降低各位的学习成本，默认预设了一些图片风格，无需输入太长的命令就能生成不错的效果图：

| 线性风格  | 漫画风格  |
| ------------- | ------------- | 
| <img width="600" src='https://github.com/thinkingjimmy/PoleStarChat/assets/37492595/e1aaef72-f265-4efc-881e-b0d90b63a8c5'/> | <img width="600" src='https://github.com/thinkingjimmy/PoleStarChat/assets/37492595/98f7b805-cdd6-4ab2-a12c-ef16148b6b4f' /> |

目前我们使用的模型是 Stable Diffusion XL，你无需研究如何安装 SD 模型，即可像使用 Midjourney 那样使用 SD 出图。

## 💬 消息支持引用
虽然 AI 支持上下文聊天功能，但我们发现有的时候，要想准确地让 AI 理解「这个」或「上述」这些指令非常难。所以在 PoleStar Chat 里我们提供了引用的功能。让你能准确地向 AI 下达指令。

另外，你还可以使用引用的功能，将 Bot 连起来用，比如可以用 Midjourney 指令生成器生成指令，然后引用该指令，并 AT 文生图 Bot。比如像这样：


https://github.com/thinkingjimmy/PoleStarChat/assets/37492595/bd9983e0-4ea1-4a45-98ad-bcafe3768160

## 🔖 结果支持 Retry，并以 tab 的方式显示在一个消息气泡内

目前 AI 技术还处于早期阶段， AI 产出的内容还不太稳定，常常需要让 AI 重新输出。但现在市面上的产品，大多数采用的是覆盖或重新发送的方式解决 Retry 需求，前者会丢失历史数据，后者则会打乱上下文。

为了解决这个问题，PoleStar Chat 支持在同一个气泡内显示多条结果，方便比对：
| Image  | Text  |
| ------------- | ------------- | 
| <img width="600" src='https://github.com/thinkingjimmy/PoleStarChat/assets/37492595/c46b7440-c1e8-4b78-a171-864726de4de9'/> | <img width="600" src='https://github.com/thinkingjimmy/PoleStarChat/assets/37492595/ef7ed39c-be4c-4f36-8a94-60b520c36a28' /> |


## 🔥 开源代码

俗话说，众人拾柴火焰高。我们深知要想让更多人使用上 AI ，个人的力量是远远不够的，所以我们决定引入开源社区的力量。我们预计会在 7 月左右开源我们的代码（不包含服务端代码），届时，大家可以使用我们产品进行二次开发。

## 💰 支持 Pay as you go 模式

最后一个，比较影响各位使用的，可能就是价格了。OpenAI 会员每月 20 美元，Midjourney 每月 30 美元，但个人使用的话，可能根本用不完，每个月 50 美元的费用对于很多人来说还是比较贵的。
为了解决这个问题，后续我们会支持付费购买 Token ，并且会以 Pay as you go 的方式支付模型调用费用。简单说来，就是用多少付多少，从而降低各位的使用成本。



