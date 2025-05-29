# Kitboga Code Jam
"I'm not a robot!"

This GitHub repository contains a template you should fork, modify to include your captcha, and then submit to us. Please read all the information in this readme before getting started!
**The deadline for submissions is 27th June 2025!**

## Rules
1. Follow the guidelines in `captcha/captcha.html` as to where and how your code should be written.
2. It goes without saying, but no malicious code. We want to frustrate and anger scammers, but it's no fun if we just crash their browser, and we're not interested in doing anything illegal. Specifically:
    - No resource-hogs
    - No crypto mining
    - No fork bombs or similar
    - No attempting to reveal their personal information
    - No exploits
    - No payload deployment
    - No attempts to collect or display personal information
3. Please try to match the tone of the Kitboga community. You are very unlikely to be selected if your submission contains:
    - Bad language (this will spook a scammer right away)
    - Racism, or basically any other -ism
    - Vulgarity or anything NSFW
    - Anything which would violate the Twitch or YouTube TOS. If you are unsure where this line is, then better to stay on the safe side.
4. Please don't use copyrighted logos or brand names in your submission. If you have an idea for something incredible which only works with a particular brand, check with us in Discord.
5. No obfuscation. If we can't read or understand the code, we're probably not going to run it.
6. No requests for resources outside of your repository. Include all the assets you need in your repository, including any JS libraries, fonts, icons and everything else. If you have a specific idea which requires access to the Internet, perhaps to fetch live stock market data for example, then try to fake it. If it's important to you to make external requests, talk to us about it in Discord.
7. When submitting your code, please tell us about every feature, even "easter eggs". No surprises!
8. WebAssembly and Web Workers are not allowed

## Getting Started
1. Create a GitHub repository from the template: https://github.com/new?template_name=codejam25&template_owner=The-Kitboga-Show
2. Clone the new repository locally to your machine.
3. Run the command in the terminal to start a web server: `python3 -m http.server 8000`
4. Open [http://localhost:8000](http://localhost:8000) in your browser.
5. Create your game in `captcha/captcha.html`!

## Advice
1. Scammers are often using iPhones, so make sure your CAPTCHA works properly in that format. They also use desktops, usually with Chrome or Edge, so it's a good idea to make sure it works well in a desktop format also.

2. The best submissions will be ones which are fun to watch, and also irritating for the scammer. They should be designed so that the scammer finds them difficult or confusing to complete, but they should eventually be completable, within around 5 minutes. Having some element of skill (rather than only chance) is more likely to keep a scammer hooked and actively trying to pass your CAPTCHA.

3. If you want to go the extra mile, having some configuration in the code which increases or decreases the difficulty could be a nice touch.

## Forbidden APIs and functions
Please don't use any of the following:
- navigator.geolocation
- navigator.getUserMedia()
- RTCPeerConnection
- navigator.connection
- navigator.clipboard
- navigator.bluetooth
- navigator.usb
- navigator.serial
- navigator.requestMIDIAccess
- window.showOpenFilePicker()
- window.showSaveFilePicker()
- navigator.serviceWorker
- window.open()
- window.print()
- navigator.permissions
- navigator.credentials
- XMLHttpRequest, WebSocket, etc.

## How to submit
**Remember, the deadline is 27th June 2025!**
Go here: https://kitboga.com/codejam

## Further help
Drop into the Kitboga discord server, and check out the #code-jam channel. Please don't ask questions via email, as we might not see them before the deadline.
