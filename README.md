OTP-Generator
=========================

An Alfred workflow that enters the current one-time password (OTP) into current active window.


It will overwrite the contents of the clipboard, and uses the [OATH
Toolkit](http://www.nongnu.org/oath-toolkit/)'s oathtool to generate the
token.


Using
=====

- Install [Homebrew](http://mxcl.github.com/homebrew/)
- ```brew install oath-toolkit```
- Open the edit interface for Alfred workflow
- Double click to open the square in the middle of 'Hotkey' and 'Runscript'
- Enter your secret base right to the 'token'.
- Open the 'Hotkey' bubble and enter the key combination you want to use.
- Each Hotkey and Token combination can be used for one OTP Generation.
