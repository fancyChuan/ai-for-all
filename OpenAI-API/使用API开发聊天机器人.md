

### 需要用到的网址
- 基于GPT-3的 [PlayGround](https://platform.openai.com/playground/p/default-chat)
- openai的python库：[https://anaconda.org/conda-forge/openai](https://anaconda.org/conda-forge/openai)
- API key生成：[https://platform.openai.com/account/api-keys](https://platform.openai.com/account/api-keys)

### 补充一些 OpenAI API 的基础概念
- OpenAI 提到一个理念：「设计提示语，就相当于在用一些指令和少量例子给模型编程」
- OpenAI 还强调了在目标任务上的区别，就是 OpenAI 的 NLP 模型与其他 NLP 模型很大的一个区别是，
  它不是设计用来解决单一类型任务的，而是可以解决几乎各种类型的 NLP 任务，包括但不限于:
  - 文本生成（content generation）
  - 代码生成（code generation）
  - 总结（summarization）
  - 扩写（expansion）
  - 对话（conversation）
  - 创意写作（creative wrting）
  - 风格转换（style transfer）
  
- token：我们理解和处理文本，是把文本先打碎成 token
> 一个大概的经验是，通常英文文本里 1 token 有 4 个字母或者 0.75 个单词。使用时的一个限制是，最好你的提示（prompt）或生成内容，不要超过 2048 个 tokens，大概相当于 1500 个单词。

### 关于模型
模型系列 | 适用场景 | 说明
--- | --- | ---
Turbo | 对话、文本生成 | 接收定期模型更新，针对对话式聊天输入和输出进行了优化
Davinci | 复杂意图、因果分析、Summarization for Audience、创意内容生成 | 是最有能力的模型系列、API更贵、模型也没那么快
Curie | 机器翻译、复杂分类任务、情感分析、Summarization | 能够胜任许多细微的任务，例如情感分类和摘要
Babbage | 审核分类、语义搜索分类 | 
Ada | 文本解析、简单分类、地址修正、关键词 | 


### 参考资料
- [AI 应用大爆发！一文学会 ChatGPT 官方 API](https://mp.weixin.qq.com/s/mtiUuALbtDbvSd32z6uw5g)