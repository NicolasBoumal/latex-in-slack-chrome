# Using this extension in Chrome

1. Clone this repo to your hard drive.
1. Visit your Chrome extensions page (chrome://extensions/).
1. Enable Developer mode, by activating the switch in the upper-right corner.
1. Click on the "Load unpacked extension" button.
1. Select the folder containing the cloned repo (the folder contains a file called manifest.json).
1. Confirm. You're done.


# What this is: Latex-in-Slack modified for single dollars

This is a tiny modification of the extension latex-in-slack v0.4.3 by Sophie Huiberts and Bento Natura (2019), available here:

https://github.com/sophiehuiberts/katex-with-slack

https://chrome.google.com/webstore/detail/latex-in-slack/pfcfelfnpbnboelkjedecjipaibpnfja?hl=en

The original authors do not endorse this modification. The modification is available under the same license as the original code.

For all the bad reasons, code here was obtained from the chrome store directly rather than from the github repo, using the _chrome extension source viewer_.

https://chrome.google.com/webstore/detail/chrome-extension-source-v/jifpbeccnghkjeaalbbjmodiffmgedin/related

Then, code was modified so that we can use single dollars and double dollars for math in the usual LaTeX way.

Original fork: Nov. 22, 2020


Update on July 18, 2025: Manifest.json was updated with ChatGPT to conform with Chrome's new rules. (It had become impossible to use the extension because of it.)


# Random notes

Below is (essentially) a copy-paste of instructions found on Stack Overflow to modify an existing Chrome extension. This is a terrible way of doing things, but it was quick.

https://stackoverflow.com/questions/16680682/how-to-modify-an-extension-from-the-chrome-web-store#:~:text=Go%20to%20the%20page%20in,wanted%20to%20change%20edit%20config.

1. Install the Chrome extension source viewer.
1. Go to the page in the Chrome Web Store of the extension you want to modify.
1. Click on the yellow CRX button, and choose Download (screenshot).
1. Extract the zip file.
1. Read the source code, and change what needs to be changed.
