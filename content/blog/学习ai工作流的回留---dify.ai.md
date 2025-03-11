---
title: 学习AI工作流的回留 - Dify.ai
date: 2025-03-11T10:06:51.236Z
---

```
git项目：
https://github.com/svcvit/Awesome-Dify-Workflow?tab=readme-ov-file
```

*这个项目是一些Dify工作流的应用。其实，我开始接触Dify也是有些2年多了，是一早在小破站关于AI应用上的相关视频，进行模仿使用的，当时因为官网需要翻墙，所以就本地搭建了一下，但是本地部署的模型真的太慢了，使用的是ollama跑的Qwen4B模型，自己的电脑配置不足（尤其是GPU这块几乎于没有，完全使用CPU来运行），所以导致使用上非常有限，最终在完成了一个知识库搭建后，在界面和其他网页上引入弹窗插件，基本上就没有再动了。*

***👇图1：使用科学上网方式进入Dify官网进行知识库部署+简单问答（RAG初体验）***
![1E9D6C3C-3256-4B65-9625-3AF2EA3FA479.png](https://github.com/Apecice/tinymind-blog/blob/main/assets/images/2025-03-11/1741686956813.png?raw=true)

***👇图2：市面上常见的单独聊天界面（OpenAI ｜ 豆包 ｜ DeepSeek等）***
![B460DC33-4D14-4548-B147-3FFE2D994E7C.png](https://github.com/Apecice/tinymind-blog/blob/main/assets/images/2025-03-11/1741686857200.png?raw=true)

***👇 图3：嵌入到WebView视图***
![4B55F427-F42D-4CCB-BA90-F69B1616016A.png](https://github.com/Apecice/tinymind-blog/blob/main/assets/images/2025-03-11/1741686722758.png?raw=true)

> 小插曲：
当时还为了绕开网络，使用*oneapi*提供API调用

参考资料：
# 1. [dify+ollama构建本地大模型平台 - 知乎](https://zhuanlan.zhihu.com/p/697386670)
# 2. [oneapi：强大而易用的OpenAI接口管理和分发系统 - 知乎](https://zhuanlan.zhihu.com/p/685664484)