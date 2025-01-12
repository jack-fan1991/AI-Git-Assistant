
#### ❗❗ This version currently supports only macOS

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
- You need to get a Gemini API key from [Gemini API](https://aistudio.google.com/app/apikey?hl=zh-tw) .
- [More](https://ai.google.dev/gemini-api/docs/api-key?hl=zh-tw)


## Download and Install
First, download the setup script.

[Click here to download](https://drive.google.com/file/d/1cJ1Zt9jtLX14jRtkCvrh3sA1n6NceLA0/view?usp=sharing)

### Step 1: Move to the Downloaded Location
After downloading the script, navigate to the directory where the `download.sh` file was saved. You can do this using the terminal.

For example, if the file was saved in your Downloads folder:

```bash
cd ~/Downloads && sh download.sh
```
### Launch AI Assistant GUI
- Make sure to **cd** into your project folder, which must be a Git version-controlled project.

```bash
cd my_project && aiCommit
```

##### Dependencies
- Run the setup script to install required Python packages. This script will check for the flet module and prompt you to install it if necessary:

