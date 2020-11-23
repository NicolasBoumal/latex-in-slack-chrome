# latex-in-slack-chrome
Modified version of latex-in-slack chrome extension

https://chrome.google.com/webstore/detail/latex-in-slack/pfcfelfnpbnboelkjedecjipaibpnfja?hl=en#:~:text=LaTeX%20in%20Slack&text=Render%20LaTeX%20in%20Slack%20chat,the%20latest%20version%20of%20Slack.

https://github.com/KaTeX/KaTeX/blob/master/contrib/auto-render/auto-render.js

https://katex.org/docs/autorender.html

https://chrome.google.com/webstore/detail/chrome-extension-source-v/jifpbeccnghkjeaalbbjmodiffmgedin/related

# Following the steps from stack overflow:
https://stackoverflow.com/questions/16680682/how-to-modify-an-extension-from-the-chrome-web-store#:~:text=Go%20to%20the%20page%20in,wanted%20to%20change%20edit%20config.

## Getting the source and modifying it
1. Install the Chrome extension source viewer.
1. Go to the page in the Chrome Web Store of the extension you want to modify.
1. Click on the yellow CRX button, and choose Download (screenshot).
1. Extract the zip file.
1. Read the source code, and change what needs to be changed (in your particular case, I had quickly identified that you wanted to change edit config.js and change the "channel" property). Save the changes.

## Using the modified version of the extension.
1. Visit the Chrome extension page (chrome://extensions/).
1. Enable Developer mode, by activating the switch in the upper-right corner.
1. Click on the "Load unpacked extension" button.
1. Select the folder of your extension (to know which folder is correct, check whether the folder contains a file called manifest.json).
1. Confirm. You're done.
