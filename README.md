# OpenAI_WLH ✨

欢迎来到 **openai_wlh**，一个让你在博客上展现个性 ChatGPT 网站的独特项目。简单快速，同时也轻松在你的服务器上进行部署。

## 特别功能

1. [利用prompt专业翻译](https://www.bilibili.com/read/cv28100058/?jump_opus=1) 对比其他翻译方法详细内容
2. **自制部署pdf识别内容**
   - 并可对pdf进行提问，有时候转不出来请换更大的模型比如从 18k --> 36k 这是上下文限制，后续会继续改进

## 😊 已有模型

在这里添加已有的模型：

1. **gpt-3.5-turbo**: GPT-3.5 Turbo 模型
   - 应用领域：
     - 文本生成
     - 问题回答
     - 对话生成

2. **gpt-3.5-turbo-16k**: GPT-3.5 Turbo 模型的 16k 变体

3. **gpt-4**: GPT-4 模型
   - 更智能、更强大的能力
   - 提升了对上下文的理解和生成自然语言的能力
   - 适用于各种复杂的自然语言处理任务

4. **gpt-4-1106-preview**: GPT-4 模型的 1106 预览版本

5. **gpt-4-32k**: GPT-4 模型的 32k 变体

6. **code-llama-34b**: Code Llama 模型，34亿参数

7. **code-llama-13b**: Code Llama 模型，13亿参数

8. **llama-2-70b**: Llama 2 模型，70亿参数

9. **llama-2-13b**: Llama 2 模型，13亿参数


-------------------**以上模型均可联网**-------------------

## 🚀 快速上手

1. **免费获取 API**
   - 利用第三方 OpenAI API，费用仅为 OpenAI 官方标价的 0.2 倍（gpt-3.5-turbo 其余模型价格不一 但是已经低于官网价格了）。
   - 摆脱繁琐的外网信用卡或银行卡租凭步骤，简单快捷。

2. **获取你的 API 密钥**
   - 在 [OhMyGPT](https://www.ohmygpt.com?aff=BDnMSilC) 获取你的 API 密钥（还有好几个准备就是加强整个网站稳定性的时候分别使用，避免对某个api形成依赖性，在不可预知情况下可保证用户体验）。
   - 将密钥嵌入项目，详细填写方法我们会提供，无需担心。

3. **流式输出**
   - 完成

3. **数据库**
   - 未完成

4. **后端**
   - flask 
   -- /chat --> 流式输出
   -- /extract_text --> 识别pdf内容

## 🌐 项目体验

立刻 [体验 W-GPT](http://8.138.104.244)，项目正在阿里云上运行，稳定可靠。

## 🛠️ 软件架构

详尽的软件架构说明，让你更深入了解项目的构建和设计。帮我美化一下这段 markdown 文件，添加部署标题，内容如下：

## 🚀 项目部署
【Flask项目部署（阿里云服务器Ubantu操作系统）】
```bash
https://www.bilibili.com/video/BV1kX4y1N7u9?vd_source=86128f0caacbd1f48d8ba64b076f5197
```

在 git 上运行以下命令进行项目克隆：

```bash
git clone https://gitee.com/developer-father/openai_wlh.git
```

然后在 openai_wlh 目录运行以下命令安装所需依赖：

```bash
pip install -r requirements.txt
```

最后，在 shell 中运行 openai_flask.py 文件，指定端口号（默认为 5000）：

```bash
python openai_flask.py
```