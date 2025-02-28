# Thre steps to load personal DeepSeek

## Introduction

***DeepSeek*** refers to a series of large language models (LLMs) developed by the company 深度求索 (DeepSeek) , which is based in China. These models are designed to handle a wide variety of tasks across different domains, including natural language processing (NLP), code generation, and multi-modal tasks.

DeepSeek is a open source platform and you can see the source code in [GitHub](https://github.com/) on [Project](https://github.com/deepseek-ai/DeepSeek-V3).

But our project will be simple and will not be necessary build some code. Only go to way the steps.

## Step 1

Software requirement. You need download of the some softwares before all. I recommend last version from the softwares.

 - **Ollama**: [https://ollama.com/download](https://ollama.com/download)
 - **ChatBox**: [https://chatboxai.app/pt-PT](https://chatboxai.app/pt-PT)

## Step 2

### Ollama

The Ollama is a tool used to facility the management of the LLMs (Large Language Models) on local environments.

> Execute OllamaSetup.exe downloaded in computer. After install check if the software is started in the computer. In the windows you can check in tray icons, left on the clock. See the image.

<div align="center">
  <img src="https://github.com/user-attachments/assets/9f0e3272-d44e-440b-9403-4ce51c4219b7" width="300" alt="Descrição da imagem">
</div>

On the Ollama website, go to the Model menu and choose the preferred. Have attention to memory requirement. To my first test I chose the 7b, was a fast training before use a big data.

<div align="center">
  <img src="https://github.com/user-attachments/assets/cd3c958a-b7fe-4399-91af-259ec5903865" width="300" alt="Descrição da imagem">
</div>

After choose the model execute in your prefer command line software the line like `ollama run deepseek-r1:7b`. After load model you will be result like the image below.

![img](https://github.com/user-attachments/assets/4b283365-3493-4817-a896-9ef022251449)

Now you can put data in the command line application e receive the response like in ChatGpt DeepSeek or QWen, but the response precision depends on the loaded model.
After running the model, which is previously trained, you can start using it. I asked some basic questions in Portuguese and English and got coherent answers in both languages.

## Step 3

Finally, I added a UI tool for better interaction.

### UI Interface

In the last step install `Chatbox-1.10.2-Setup.exe` and execute.

 - When opening the application, click on Settings
 - In the model provider selection field, select Ollama API
 - In the URL, enter the URL to which your Ollama is responding

![image](https://github.com/user-attachments/assets/78d895c1-2e96-4025-8adc-6471cc0ddac6)
