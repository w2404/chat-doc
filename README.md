# HTML的界面说明

1. 按保存对话按钮，会把对话保存为json格式。json文件可以用记事本编辑。把json文件拖到上传文件按钮上，可以加载和继续这个对话。
2. 按ctrl+s可以把对话保存为html，不过不能被再次加载。
3. 中断按钮可以中断一次等待时间过长的提问
4. 重试按钮会重试一次连接失败的提问
5. 撤回按钮会撤回一次连接失败的提问
6. 温度代表随机性
7. 前缀咒语，就是发没句话前加一个前缀，省得去打一些常用的指令。但是，这些咒语可能编的不是很有效，在一些场景下会失效。已知的时候如果对话一开始就用咒语，它工作的会比较正常。如果你知道更有效的咒语，告诉我，让我添加进prefixspells.js

# 对话记录

对话记录相当于是和你对话的这个gpt的记忆和人格。它的长度限制是4000 tokens。

如果超出了长度限制你还想要继续对话，就要删除这份记录中不重要的部分。你可以编辑json，精确删掉不需要的语句，留下最重要的信息。

当gpt做了一个很糟糕的回答的时候，这个回答会影响到后续回答的质量，所以你也要删除掉。 


因为tokens长度限制是4000，当超出4000还想要继续对话的时候，就必须要删除一些对话。界面上提供了一个3000 tokens的阀值，可以在tokens达到3000的时候自动删除最早的两条对话。这在持续对话中会很方便，比如说当你创造了一个合适的小说场景，连续打“继续”，让chatgpt自己往下编写的时候。但是如果你想要自己手动控制，更准确的删减对话，就把这个阀值拉到最大，它就不起作用了。

这里3000 tokens的估算是不准确的，所以它不是总是有效


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


# 经验

英文的问答比中文问答质量更高。例子：试试用中英文问gpt战锤40k和游戏dominions的设定，比如战锤40k有多少种族？what are the factions of warharmmer 40k?。使用英文的时候gpt都能说出准确的设定，使用中文的时候，它总是在编造。
