# ai-agent-Content-Hub
目前最齐全的ai-agent学习资料，从paper、原理、新出项目以及ai-agent使用到各种奇怪的用法，持续更新中.....

# LLM API（调试免费额度管够，别说找不到API了）

[Google Gemini](https://ai.google.dev/aistudio) [[官方文档]](https://ai.google.dev/gemini-api/docs/ai-studio-quickstart)（需要科学上网）
给了很多免费额度，gemini系列每天1500 个免费请求额度，每分钟限速 （100万token ） 15个请求，目前个人用户每天是够用的。

[groq](https://console.groq.com/home)  [[官方文档]](https://console.groq.com/docs/overview)（需要科学上网）
提供gemma系列的免费额度，很多模型都有500k tokens每天的额度。

[【OpenRouter 每日免费调用200次】](https://openrouter.ai/)  [[官方文档]](https://openrouter.ai/docs/quickstart)
每分钟最大请求次数20次，每天200次，日常使用应该是完全够了。(随时可能调整)

[siliconflow 硅基流动](https://siliconflow.cn/zh-cn/)   [[官方文档]](https://docs.siliconflow.cn/cn/userguide/introduction)
提供免费的SD（文生图）、Qwen（阿里）、gemma、系列模型，国内直接访问。



# 学术前沿
[【复旦大学 全面梳理了基于大型语言模型的智能代理现状（一文纵览AI智能体的现状与未来）】](https://arxiv.org/abs/2309.07864) [[github]](https://github.com/WooooDyy/LLM-Agent-Paper-List)


[【斯坦福研究院 斯坦福小镇（在这个小镇上,25 个 AI 智能体正常生活、工作、社交,甚至谈恋爱】](http://arxiv.org/pdf/2304.03442) [[paper]](http://arxiv.org/pdf/2304.03442)   [[github]](https://github.com/joonspk-research/genagents) 

[【普林斯顿博士/清华学霸/openai 姚顺雨（反思：具有言语强化学习的Language Agents）】](https://arxiv.org/abs/2303.11366) [[paper]](https://arxiv.org/abs/2303.11366)   [[github]](https://github.com/noahshinn/reflexion) 

[【普林斯顿博士/清华学霸/openai 姚顺雨（如何对 AI agent进行基准测试）】](https://arxiv.org/abs/2406.12045) [[paper]](https://arxiv.org/abs/2406.12045)   [[github]](https://github.com/sierra-research/tau-bench)[[blog]](https://sierra.ai/blog/benchmarking-ai-agents) 

# 开源项目
[【MetaGPT: The Multi-Agent Framework（用于多智能体协作框架的元编程）】](https://docs.deepwisdom.ai/v0.4/zh/guide/get_started/introduction.html)  [[paper]](https://arxiv.org/abs/2308.00352) [[github]](https://github.com/geekan/MetaGPT)  [[官方文档]](https://docs.deepwisdom.ai/v0.4/zh/guide/get_started/introduction.html)

MetaGPT是一个突破性的框架,它将多个 AI 模型整合在一起,共同工作,模仿现实世界公司的运作。


[【AutoGPT: Build, Deploy, and Run AI Agents】](https://github.com/Significant-Gravitas/AutoGPTl)   [[github]](https://github.com/Significant-Gravitas/AutoGPT)  [[试用地址]](https://tryfastgpt.ai/)

openai推出，AutoGPT是一个强大的平台，允许您创建、部署和管理连续的人工智能代理，使复杂的工作流程自动化。


## 开源LLM相关库

[【anythingllm】](https://anythingllm.com/)   [[github]](https://github.com/Mintplex-Labs/anything-llm/tree/master)  
全栈应用程序，可以将任何文档、资源（如网址链接、音频、视频）或内容片段转换为上下文，以便任何大语言模型（LLM）在聊天期间作为参考使用。此应用程序允许您选择使用哪个LLM或向量数据库，同时支持多用户管理并设置不同权限。

[【ollama】](https://ollama.com/)   [[github]](https://github.com/ollama/ollama)  
一个开源的大型语言模型服务工具，旨在帮助用户快速在本地运行大模型。

[【ragflow】](https://ragflow.io/)   [[github]](https://github.com/infiniflow/ragflow?tab=readme-ov-file)  
RAGFlow 是一个基于深度文档理解的开源 RAG（检索增强生成）引擎（开源工作流），精简的 RAG 编排可满足个人和大型企业的需求。。配置要求：- CPU >= 4 核、 内存 >= 16 GB、 磁盘 >= 50 GB。


[【cherry studio】](https://cherry-ai.com/)   [[github]](https://github.com/CherryHQ/cherry-studio)    [[官方文档]](https://docs.cherry-ai.com/)
 Cherry Studio 自带多种文生图模型，实现快捷在本地部署知识库与AI助手。

 [【dify】](https://dify.ai/)   [[github]](https://github.com/langgenius/dify)    [[官方文档]](https://docs.dify.ai/en/introduction)
Dify 是一个开源的 LLM 应用开发平台。其直观的界面融合了 Agentic AI 工作流、RAG 流水线、代理功能、模型管理、可观察性功能等，让您能够快速从原型开发过渡到生产环境。

[【LlamaIndex】](https://www.llamaindex.ai/)   [[github]](https://github.com/run-llama/llama_index)    [[官方文档]](https://docs.llamaindex.ai/en/stable/module_guides/loading/documents_and_nodes/)
LlamaIndex 赋予了开发者深入数据、精雕细琢的能力，用于构建复杂、高性能 AI 应用，更偏向于开发者使用。如果你是一位开发者且需要高度定制化，比如文档解析分块自定义元数据。

# 行业前沿ai agent平台应用
## 国内版本
[【字节跳动 国内版 扣子 coze】](https://www.coze.cn)  [[官方文档]](https://www.coze.cn/docs/guides/quickstart)
初学者很容易上手，对于技术开发者也是非常好用

[【文心一言 agentbuilder】](https://agents.baidu.com)  [[官方文档]](https://agents.baidu.com/docs/intelligent-agent/zero_code_develop/)
百度定位AI原生应用的平台，定位企业级、商业化的AI应用开发

[【苏州语灵人工智能科技公司 dify （开源）】](https://github.com/langgenius/dify)  [[官方文档]](https://docs.dify.ai/)
具有完善的Agent开发各项功能，并支持非常多的国内外大模型，且提供云服务和本地部署两种方式，主要面向海外市场。

[【 环界云计算公司 FastGPT （开源）】](https://github.com/labring/FastGPT)  [[官方文档]](https://doc.tryfastgpt.ai/docs/intro/)  [[官方文档]](https://doc.tryfastgpt.ai/docs/intro/)  [在线试用地址](https://tryfastgpt.ai/)
FastGPT 是一个基于 LLM 大语言模型的知识库问答系统，提供开箱即用的数据处理、模型调用等能力。同时可以通过 Flow 可视化进行工作流编排，从而实现复杂的问答场景！


[【 Monica manus 】](https://manus.im/) 
Manus定位于一位性能强大的通用型助手，对于用户不仅仅是提供想法，而是能将想法付诸实践，真正解决问题。

## 国外版本

[【Google Gemini（新版本主推原生多模态输入输出+Agent）】](https://dialogflow.cloud.google.com/) [[官方地址]](https://gemini.google.com/app)   [[官方文档]](https://ai.google.dev/gemini-api/docs/quickstart?hl=zh-cn&lang=python)  
Gemini可以原生生成图像和音频，同时支持文本生成，还可以使用第三方应用程序和服务，使其能够访问谷歌搜索、执行代码等功能。

[【字节跳动 国外版 扣子 coze】](https://www.coze.com) [[官方文档]](https://www.coze.com/docs/guides/quickstart)

[【Google Dialogflow（构建自然语言理解的对话界面，与Google Assistant无缝集成。）】](https://dialogflow.cloud.google.com/) [[官方文档]](https://cloud.google.com/dialogflow/docs)

[【Microsoft Bot Framework（一个全面的框架，用于构建企业级的会话AI体验，支持多种语言和平台。）】](https://www.ibm.com/watson/ai-assistant/) [[官方文档]](https://cloud.ibm.com/docs/assistant)

[【Amazon Lex（使用与Alexa相同的技术构建聊天机器人和语音界面，轻松集成到任何应用程序中。）】](https://aws.amazon.com/lex/) [[官方文档]](https://docs.aws.amazon.com/lex/)

[【IBM Watson Assistant（利用IBM的AI技术，创建能够理解自然语言并提供深入洞察的虚拟助手。）】](https://www.ibm.com/watson/ai-assistant/) [[官方文档]](https://cloud.ibm.com/docs/assistant)

[【Rasa（开源的对话AI平台，用于构建和部署自定义的聊天机器人和虚拟助）】](https://rasa.com/) [[官方文档]](https://rasa.com/docs/)



# AI平台

注意：免费额度策略随时可能改变

[【suno（每日可以免费通过AI生成五首歌的积分额度）】](https://suno.com/) [[官方文档]](https://help.suno.com/)

[【stablevideo（免费的AI视频生产服务）】](https://www.stablevideo.com/welcome) [[官方文档]](https://www.stablevideo.com/welcome)

[【Midjourney（每日可以免费生成25张图）】](https://www.midjourney.com/) [[官方文档]](https://www.midjourney.com)

[【DALL-E 2（由openai推出 第一次可以免费生成50张图，后每个月可以免费生成15张）】](https://openai.com/dall-e-2) [[官方文档]](https://platform.openai.com/docs/overview)

[【Runway ML Gen-3 (免费额度可以生成二十个约4秒的视频)】](https://runwayml.com/) [[官方文档]](https://help.runwayml.com/hc/en-us/sections/30265301423635-Gen-3-Alpha)

[【Claude Sonnet (优秀的辅助编程能力，低版本免费)】](https://claude.ai/) [[官方文档]](https://docs.anthropic.com/en/docs/welcome)



# 人工智能风投

[【Venture Capital Journal】](https://www.venturecapitaljournal.com/) 
一家领先的出版物，提供风险投资行业的最新新闻和情报，并日益关注人工智能领域的投资。

[【Crunchbase News】](https://news.crunchbase.com/) 
提供关于私募市场、初创公司、创始人和投资者的数据驱动报告，并设有专门的人工智能新闻版块。

[【PitchBook】](https://pitchbook.com/news/venture-capital) 
提供全球风险投资、私募股权和并购的全面新闻与分析，并越来越重视包括人工智能在内的科技领域。

[【a16z】](https://a16z.com/news-content/) 
Andreessen Horowitz (a16z) 是一家著名的风险投资公司的官方新闻和内容平台，对人工智能及相关技术领域有深入的见解和投资。

[【VC News — Tech Funding News】](https://techfundingnews.com/category/vc/) 
一个专注于技术融资的新闻网站，设有专门的人工智能新闻类别，报道融资轮次和市场趋势。

[【VC News Daily】](https://vcnewsdaily.com/) 
每日更新风险投资融资和技术初创公司的新闻，频繁报道人工智能公司的融资情况。


|   |   |   |   |   |
|---|---|---|---|---|
|公司名称|融资额|日期（如有）|简要描述|备注|
|Perplexity AI|15亿美元（寻求中）|2025年3月|人工智能驱动的搜索引擎||
|Nerdio|5亿美元|2025年3月|利用人工智能的云管理初创公司||
|Lambda|4.8亿美元|2025年2月|提供优化人工智能训练的计算服务和硬件||
|Together AI|3.05亿美元|2025年2月|开发用于构建开放和定制人工智能模型的云平台||
|Inspiren|3500万美元|2025年3月|为老年生活行业提供人工智能驱动的解决方案||
|Hunted Labs|300万美元|2025年3月|利用人工智能的软件安全公司||
|Apptronik|3.5亿美元|2025年2月|人工智能驱动的人形机器人公司||
|Celesta|未提及|2025年3月|专注于印度-美国科技走廊的人工智能投资||
|Sesame AI|未提及|2025年3月|a16z投资的人工智能公司||
|Raspberry AI|未提及|2025年3月|a16z投资的人工智能公司||
| **SplxAI**    | €6.5M        | 2025年3月26日 | AI聊天机器人安全           |       |
| **Lumi AI**   | $3.7M | 2025年3月26日 | 从非结构化数据中获取AI洞察 |  |
| **Nexthop AI** | $110M | 2025年3月25日 | AI网络基础设施 |  |
| **Arondite** | $12M | 2025年4月30日 | AI国防技术 |  |
| **AI Bob** | €2M | 2025年4月23日 | AI建筑项目规划 |  |
| **Solena Materials**| £6.7M | 2025年4月 | AI驱动的新一代纺织材料 |  |
| **MarvelX** | $6M | 2025年5月2日 | 保险业智能体AI |  |
| **Perplexity AI** | $500M | 2025年5月 | AI驱动的搜索引擎 |  |
| **CAST AI** | $108M | 2025年5月 | AI云成本优化 |  |
| **Anysphere (Cursor)**| $900M | 2025年5月 | AI编码 |  |
| **Grammarly** | $1B | 2025年5月30日 | AI写作与生产力工具 |  |
| **Neuralink** | $600M (据报道) | 2025年5月30日 | 脑机接口/神经科学 |  |
| **Snorkel AI** | $100M | 2025年5月30日 | AI系统评估与调优 |  |
| **Hex Technologies**| $70M | 2025年5月30日 | AI赋能的数据分析平台 |  |
| **Pactum** | $50M | 2025年6月初 | AI企业采购 |  |
| **Scale AI (潜在投资)**| $10B+ (Meta探索投资) | 2025年6月8日 | AI数据标注与训练 |  |

