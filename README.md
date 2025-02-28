
# Three Steps to Load Personal DeepSeek

## Introduction

**DeepSeek** refers to a series of large language models (LLMs) developed by 深度求索 (DeepSeek), a company based in China. These models are designed to handle a wide variety of tasks across different domains, including natural language processing (NLP), code generation, and multi-modal tasks.

DeepSeek is an open-source platform, and its source code can be found on [GitHub](https://github.com/deepseek-ai/DeepSeek-V3) . However, this guide focuses on using pre-built tools to interact with the model locally without needing to build the code from scratch.

----------

## Step 1: Software Requirements

Before proceeding, ensure you have the following software installed on your system. Download the latest versions for optimal performance:

-   **Ollama** : A tool for managing LLMs on local environments.  
    Download: [https://ollama.com/download](https://ollama.com/download)
-   **ChatBox** : A user-friendly interface for interacting with LLMs.  
    Download: [https://chatboxai.app/pt-PT](https://chatboxai.app/pt-PT)

----------

## Step 2: Setting Up Ollama

### What is Ollama?

Ollama simplifies the process of downloading, running, and managing LLMs on your local machine.

#### Installation and Setup:

1.  **Install Ollama** :
    
    -   Run the `OllamaSetup.exe` file downloaded from the official website.
    -   After installation, verify that Ollama is running. On Windows, check the system tray (near the clock) for the Ollama icon.

<div align="center">
  <img src="https://github.com/user-attachments/assets/9f0e3272-d44e-440b-9403-4ce51c4219b7" width="300" alt="Descrição da imagem">
</div>

-   **Choose a Model** :
    
    -   Visit the [Ollama Models page](https://ollama.com/library) and select a DeepSeek model that fits your hardware capabilities. For example:
        -   **deepseek-r1:7b** (lightweight, suitable for testing)
        -   **deepseek-r1:33b** (more powerful, requires more memory)
    -   Ensure your system meets the memory requirements for the selected model.

-   **Run the Model** :
    
    -   Open your preferred command-line interface (CLI) and execute the following command:

        ```bash
        ollama run deepseek-r1:7b
        ```
    -   Wait for the model to load. Once loaded, you should see a prompt indicating the model is ready.
    ![img](https://github.com/user-attachments/assets/4b283365-3493-4817-a896-9ef022251449)

2.  **Test the Model** :
    
    -   Start interacting with the model directly in the CLI. You can ask questions in multiple languages (e.g., Portuguese, English) and receive coherent responses.

----------

## Step 3: Adding a UI Interface with ChatBox

To enhance your interaction with DeepSeek, use **ChatBox** , a graphical user interface (GUI) tool.

### Installation and Configuration:

1.  **Install ChatBox** :
    
    - Run the `Chatbox-1.10.2-Setup.exe` file downloaded earlier.

2.  **Configure ChatBox** :
    
    -   Open the ChatBox application.
    -   Navigate to **Settings** .
    -   In the **Model Provider** field, select **Ollama API** .
    -   Enter the URL where your Ollama instance is running (usually `http://localhost:11434`).

    ![image](https://github.com/user-attachments/assets/78d895c1-2e96-4025-8adc-6471cc0ddac6)

3.  **Start Interacting** :
    
    -   Return to the main ChatBox interface and begin chatting with the DeepSeek model. The GUI provides a more intuitive and visually appealing way to interact compared to the CLI.

----------

## Conclusion

By following these three steps, you can successfully set up and interact with the **DeepSeek** LLM on your local machine:

 > 1. Install **Ollama** and **ChatBox** .
 > 2. Use Ollama to download and run the desired DeepSeek model.
 > 3. Configure **ChatBox** to provide a user-friendly interface for interacting with the model.

This setup allows you to leverage the power of DeepSeek for various tasks, such as answering questions, generating text, or experimenting with code, all within a local environment.

----------

### Additional Notes:

-   **Hardware Considerations** : Ensure your system has sufficient RAM and GPU resources (if applicable) to handle the chosen model. For example:
    -   **7B models** : Require ~8–16 GB of RAM.
    -   **33B models** : Require ~32–64 GB of RAM.
-   **Troubleshooting** : If you encounter issues, consult the [Ollama documentation](https://ollama.com/docs) or the [DeepSeek GitHub repository](https://github.com/deepseek-ai/DeepSeek-V3) .
