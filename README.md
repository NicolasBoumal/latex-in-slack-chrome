# Latex-in-Slack modified for single dollars

This is a tiny modification of the extension latex-in-slack is by Sophie Huiberts and Bento Natura (2019), available here:

https://github.com/sophiehuiberts/katex-with-slack

https://chrome.google.com/webstore/detail/latex-in-slack/pfcfelfnpbnboelkjedecjipaibpnfja?hl=en

For all the bad reasons, code here was obtained from the chrome store directly rather than from the github repo, using the _chrome extension source viewer_.

https://chrome.google.com/webstore/detail/chrome-extension-source-v/jifpbeccnghkjeaalbbjmodiffmgedin/related

Then, code was modified so that we can use $...$ and $$...$$ the way it was intended in latex.

See steps below for installation.

Surely, there is a clean way to do this...


# Following the steps from stack overflow

Below is (essentially) a copy-paste of instructions found on Stack Overflow to modify an existing Chrome extension. This is a terrible way of doing things, but it was quick.

https://stackoverflow.com/questions/16680682/how-to-modify-an-extension-from-the-chrome-web-store#:~:text=Go%20to%20the%20page%20in,wanted%20to%20change%20edit%20config.

## Getting the source and modifying it (you can skip this)
1. Install the Chrome extension source viewer.
1. Go to the page in the Chrome Web Store of the extension you want to modify.
1. Click on the yellow CRX button, and choose Download (screenshot).
1. Extract the zip file.
1. Read the source code, and change what needs to be changed.

## Using the modified version of the extension (read here to install modified code)
1. Visit the Chrome extension page (chrome://extensions/).
1. Enable Developer mode, by activating the switch in the upper-right corner.
1. Click on the "Load unpacked extension" button.
1. Select the folder containing the modified extension code (the folder contains a file called manifest.json).
1. Confirm. You're done.
