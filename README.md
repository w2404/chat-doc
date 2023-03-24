# HTML的界面说明

1. 按保存对话按钮，会把对话保存为json格式。json文件可以用记事本编辑。把json文件拖到上传文件按钮上，可以加载和继续这个对话。
2. 按ctrl+s可以把对话保存为html，不过不能被再次加载。
3. 中断按钮可以中断一次等待时间过长的提问
4. 重试按钮会重试一次连接失败的提问
5. 撤回按钮会撤回一次连接失败的提问
6. 因为tokens长度限制是4000，当超出4000还想要继续对话的时候，就必须要删除一些对话。界面上提供了一个3000 tokens的阀值，可以在tokens达到3000的时候自动删除最早的两条对话。这在持续对话中会很方便，比如说当你创造了一个合适的小说场景，连续打“继续”，让chatgpt自己往下编写的时候。但是如果你想要自己手动控制，更准确的删减对话，就把这个阀值拉到最大，它就不起作用了。


# 对话记录

对话记录相当于是和你对话的这个gpt的记忆和人格。它的长度限制是4000 tokens。

如果超出了长度限制你还想要继续对话，就要删除这份记录中不重要的部分。你可以编辑json，精确删掉不需要的语句，留下最重要的信息。

当gpt做了一个很糟糕的回答的时候，这个回答会影响到后续回答的质量，所以你也要删除掉。

引用网友的一句话：[虚拟猫娘的生命只有短短几句话，我要给她完整的一生。](https://github.com/PlexPt/awesome-chatgpt-prompts-zh/issues/12#issuecomment-1480116067) 但是，由于在界面上添加了在触及tokens阀值后自动删除早期对话的功能，这就使得gpt在获得新的记忆的同时，不断的丢失旧的记忆。当我试着让chatgpt连续不断往下说话后，发现其中的一些元素被持续的保留了下来，这个特性或许可以称为[猫娘不动点](https://zh.wikipedia.org/wiki/%E4%B8%8D%E5%8A%A8%E7%82%B9%E7%BB%84%E5%90%88%E5%AD%90)。

# 没有key也可以免费用的站点

https://freegpt.one/

# 科学思考

https://swarma.org/?p=41221

# 资源

如果你看到什么好资源，添加进来。


为chatgpt设定的100+角色扮演 
https://github.com/f/awesome-chatgpt-prompts 
https://prompts.chat/

中文版
https://github.com/PlexPt/awesome-chatgpt-prompts-zh
https://chatguide.plexpt.com/

解除封印咒语,据说这些咒语像漏洞一样，在被openai不断修补。所以如果要用的话，最好看下面issues地址中的最新回复们怎么说，什么咒语依然可以用。
https://github.com/PlexPt/awesome-chatgpt-prompts-zh/blob/main/cat.md
https://github.com/PlexPt/awesome-chatgpt-prompts-zh/issues/12


https://github.com/dair-ai/Prompt-Engineering-Guide 
https://www.promptingguide.ai/

你真的会用AI么？关于AI的prompt，一定要学会！(ChatGPT/Midjourney/Stable-diffusion) https://www.bilibili.com/video/BV1J54y137kt/

【中文提示词】全网最权威！吐血整理了目前针对ChatGPT和NewBing效果最好的中文提示词！ https://www.bilibili.com/video/BV1RA411y7Gu/

【prompt学习指南】ChatGPT的正确使用方式｜别再无脑复制模版了 https://www.bilibili.com/video/BV1AM4y167DZ

ChatGPT使用技巧，100+优质提问模版 https://www.bilibili.com/video/BV1Le411c7pC

绕过ChatGPT回答限制（极速版） [https://www.bilibili.com/video/BV1EL411Z7aG/](https://www.bilibili.com/video/BV1HM411x7bD/)

教你使用ChatGPT进行深度思考  https://www.bilibili.com/video/BV1F54y1u7QX/


