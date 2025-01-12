# AI Git Script

This repository contains a script to assist with Git commits, featuring a graphical user interface (GUI) built using the `flet` library.

## **Git AI Assistant**

Git AI Assistant is an AI-powered tool that helps developers generate clear and meaningful Git commit messages. With a user-friendly GUI built using the `flet` library.

## **Features**  
- ⚙️ **Simple Setup:** Quick and easy deployment for immediate use  
- 🔄 **Automatic Version Update Detection:** Stay up-to-date effortlessly  
- 🚀 **AI-Powered Commit Message Generation:** Intelligent suggestions for clear commit messages  
- 📚 **Contextual Suggestions:** Analyze code changes for precise commit recommendations  

## **Supported AI Engines**

| **AI Engine** | **Status** |
|---------------|------------|
| Gemini AI     | ✅ Supported |
| Other AI Engines | ❌ Not Supported |

###  Gemini API key
- You need to get a Gemini API key from [Gemini API](https://aistudio.google.com/app/apikey?hl=zh-tw) and add it to the `config.py` file.
- [More](https://ai.google.dev/gemini-api/docs/api-key?hl=zh-tw)

## Getting Started
command:

```bash
git clone https://github.com/jack-fan1991/ai_git_script.git &&
cd ai_git_script
sh sh/setup.sh
# Flow the setup script to install required Python packages.
# After setup done use aiCommit in project directory to run the script.
# For example:
cd my_project && aiCommit

#For Help
aiCommit --help
#For CLI
aiCommit
#For GUI
aiCommit --gui
```

### Setup and Install Dependencies
- Run the setup script to install required Python packages. This script will check for the flet module and prompt you to install it if necessary:

### Flet
- [Flet](https://flet.dev/docs/)
- [Flet gallery](https://flet-controls-gallery.fly.dev/navigation)

