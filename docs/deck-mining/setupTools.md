# Tools

## To extract text as you play the game
If you know what the game needs, you can just get that. Or grab them all to be well-prepared for a variety of games.

### Textractor
Download Textractor [here](https://github.com/Artikash/Textractor). You can also get the latest unofficial alpha build from [this thread](https://github.com/Artikash/Textractor/issues/868) that has updates and should support more games.  
Unzip and keep it in a folder you remember. We'll need this path later.  

### Agent
Download Agent [here](https://github.com/0xDC00/agent). Get both the Windows and Linux versions. Unzip them and keep them in a folder you remember, we'll need the paths later.  
I personally don't use their OCR server, but other OCR tools below.

### OCR
Some options:
- [owocr](https://github.com/AuroraWright/owocr) - my personal recommendation on SteamOS for now. You just need python (already available by default) to install it.
- [YomiNinja](https://github.com/matt-m-o/YomiNinja) - for advanced Linux users (you need to know what you're doing with pacman). This tool is still fast-evolving and currently installation on SteamOS (Linux) is still a bit more complicated (and there's a risk of breaking SteamOS with conflicting dependencies). You can follow news updates on their Patreon to get a sneak peek of the upcoming features.
I personally haven't installed YomiNinja on SteamOS, so no guarantees or help there.  

## To display and look up text:
### A browser that supports Yomitan extension (eg. Firefox, Chrome, Chromium browsers)
I installed flatpaks through the Discover store.

### Yomitan extension
Download the extension from your respective browser store, and refer to the [Yomitan main page](https://github.com/themoeway/yomitan) for instructions on migrating from Yomichan/setting up etc.  
If you already have a working Yomichan/Yomitan setup on another device, you can export the dictionaries and settings, and import on the Steam Deck.  
If you're starting from scratch and want a quick setup, you can consider using [Xelieu's Lazy Guide](https://xelieu.github.io/jp-lazy-guide/setupYomitanOnPC/) (I highly recommend this guide as a whole as well.)

### A browser texthook page
Pick one you like. I recommend pages that use websocket instead of relying on clipboard inserter (old and inferior method):  
- [exSTATic](https://github.com/KamWithK/exSTATic) has historical stats visualization in addition to the texthook page. Remember to install the TextractorSender dll as well as listed in the instructions.
- [Renji-XD's texthooker-ui page](https://github.com/Renji-XD/texthooker-ui). Also install a websocket hook (eg. textractor-websocket or TextractorSender).

## To mine vocab to Anki:
### Anki
Install Anki from Discover store.

### Anki addons
Install [Ankiconnect](https://ankiweb.net/shared/info/2055492159). You'll need this to add Anki cards from Yomitan.

### Mining with Yomitan 
Make sure your Yomitan settings are correct and it's able to see the Anki deck you'll add cards to, all fields are correct, etc.

## Optional: offline and more audio sources for Yomitan
Follow the guide [here](https://github.com/themoeway/local-audio-yomichan) to enable offline and more audio sources for Yomitan.  
Note: by default, this uses Anki to run, but you can also host it locally using Python 3.9 or above. Also, this will take up ~2.5 to 5GB of disk space depending on the audio format you choose, please ensure you have enough space.
