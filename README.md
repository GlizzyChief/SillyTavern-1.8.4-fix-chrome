# SillyTavern-1.8.4-fix

This is a patched version of SillyTavern 1.8.4 which adds support for Poe using selenium webdriver.
It can be used the same way as SillyTavern 1.8.4. Just input your p-b cookie and have a blast!

NOTE: this is an alternate version of the fix, using chrome instead of firefox. Please use it if the firefox version doesn't work for you.

# Instructions

NOTE: Please select ChatPGT as the model. Choosing Assistant automatically switches to ChatGPT, but still please do so manually.

## Android

If you've never ran SillyTavern, run:
- pkg install git
- pkg install nodejs

To install, run the following commands in Termux:
- pkg install x11-repo
- pkg install tur-repo
- pkg instal chromium
- pkg install libexpat
- git clone https://github.com/GlizzyChief/SillyTavern-1.8.4-fix
- cd SillyTavern-1.8.4-fix
- ./start.sh

If start.sh causes issues, then please run:
- npm install
- node server.js


## Windows
For using on Windows, simply make sure to install chrome/chromium and chromedriver.
Then, download the project either as .zip or using git (same as above)
Afterwards, simply run start.bat


## Other OSes
For any other operating systems, please contact me

## Known issues
- Streaming responses and suggestions currently don't work.

## Recent fixes
- Fixed issues with characters responding with '{'reply': 'some text'}'
- Fixed characters responding with unfinished messages or triple dots
- Fixed issues caused by Poe putting an ad modal when opening some bots
- Temporarily fixed issues with Assistant by simply using ChatGPT instead
- Managed to get it running on low-end phones via using chromium
- Fixed sending chunked messages when using large context window

## Contact
Please drop me a message on [Matrix](https://matrix.to/#/@glizzychief:catgirl.cloud) or Discord (glizzychief#1048) if you have any questions or just want to say hi.

## Credits
All credits go to the SillyTavern team and vfnm here at github.
