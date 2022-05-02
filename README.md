# GMeet-Slack integration

> Improve workplace communication with Google Meet-Slack integration!

**GMeet-Slack automatically updates your slack status in real time, when you join and exit meetings, even for unscheduled meetings or overflowing meetings.**

<br><br>

# Demo

![demo](https://user-images.githubusercontent.com/26523871/158046509-96d508f7-fbeb-424e-9268-3d18cd791ec7.gif)

<br><br>


# Installation
<a href="https://chrome.google.com/webstore/detail/meet-slack-status/kddjlbegfaiogihndmglihcgommbjmkc" target="_blank">
<img src="https://storage.googleapis.com/web-dev-uploads/image/WlD8wC6g8khYWPJUsQceQkhXSlv1/iNEddTyWiMfLSwFD6qGq.png" />
</a>

## Configure chrome extension
Once installed, open a new tab and type `meet.new` in the address bar, to join a test meeting. Now find and open the extension that has been installed from extensions list (puzzle icon).

![extension-screenshot](/extension_screenshot.png)

Chrome extension requires three inputs:
### 1. Slack API key
Click `GET SLACK API KEY` to install the slack app and generate your Slack API key.
> Slack API key starts with `xoxp-` 

> Make sure to install the slack app to the correct workspace, where you want your status to be automatically updated. Select the workspace on top right corner before clicking "Allow".

See [FAQs](#faqs)  for more help.

### 2. Choose meeting status text
This will be the text displayed in your slack status, during the meeting. Default text is `On a meet call • Reply may be delayed`.

### 3. Choose meeting status emoji
This will be the emoji displayed in your slack status, during the meeting. Default emoji is 📞.


> Custom emojis available in your slack workspace are supported. They must be directly copy pasted from slack in text format, with both the colons like `:bowtie:`. Read more in this [FAQ](#slack-status-is-not-updating).

![image](https://user-images.githubusercontent.com/26523871/164879068-b9cf8fcf-7d50-4a33-9856-0dc3cd94bd64.png)


**Click save** for the extension to start working. You should see a green banner which indicates that the extension is working.

<br><br>


# Usage
Join a meeting to test that your slack status updates automatically. Refresh meeting lobby page, if the extension does not load for the first time.

> **Pro-tip**: You can also use these keyboard shortcuts (even on a Mac)
> 
>  `CTRL+V` to join a meeting
> 
> `CTRL+Q` to quit a meeting


<br><br>


# Contributors
[Vivek G](https://github.com/yakshaG) and [Aditya Gannavarapu](https://github.com/aditya-67)

<br><br>

# FAQs

### I am unable to install the slack app

Try re-installing. Make sure you are logged in to the right slack workspace.


### Slack app installation needs admin permission
Your slack workspace admin has made it mandatory to take their approval before installing any app to the workspace. Request them to approve your request by sending a note during the installation process.

You can assure them that this app is safe and does not collect or store any data. See [privacy policy](#privacy-policy).

### I am unable to generate Slack API key
Try re-installing the slack app and make sure you click allow during the installation.

### Slack status is not updating
1. Check if you have actually pasted the Slack API key. Generate and paste again, if in doubt.
2. Check if you have installed the slack app to the correct workspace, where you want your status to be automatically updated. Select the workspace on top right corner before clicking "Allow".
3. Try a different emoji.
4. Check status emoji format, if you are using a custom slack emoji. `:smile:` will work whereas `:smile` or `smile:` will not work. To prevent confusion, copy paste the emoji directly from a slack chat.
5. The custom emoji used is not available in your slack workspace. Use only those emojis that are available in your slack workspace.

### Extension does not work sometimes
Refreshing the meeting page should bring the extension back.

### I want to uninstall this extension and slack app
1. Unistall slack app first, by using the **Revoke Slack API key** available within the extension.
2. Right click on the extension icon and remove the extension.

<br><br>

# Privacy policy
This extension or the slack app do not store any keys or data in any form. All data is stored locally inside chrome browser. Slack status API calls are made directly to Slack servers and no intermediate servers are used.

<br><br>

# Change log and Wiki
Take a look at the project's wiki at https://github.com/yakshaG/gmeet-slack-integration/wiki


