# OCR
> :heavy_exclamation_mark: CURRENTLY DOES NOT WORK. Steps below are for reference only of what I've tried.
manga_ocr currently does not work due to missing xclip or wl-paste. It used to work but looks like some SteamOS update broke it.
Also I'm having trouble installing owocr in a Python venv, but I need venv to install OCR services like Google Lens or EasyOCR, so I'm currently stuck.

<details>

<summary>Just for my reference, does not work</summary>

I'll be going through [OwOcr](https://github.com/AuroraWright/owocr) here. If you're comfortable with installing software through pacman, you can also check out YomiNinja.

## Install OwOcr
1. Create a Python virtual env (need this for manga_ocr on the Steam Deck, or it'll complain about externally managed environment and possibility of breaking the OS if you try to override it). Open Konsole and type or paste in following:
```console
python3 -m venv ocr
source ocr/bin/activate
```
2. install pip 
```console
python -m ensurepip --upgrade
```
This will install pip into ~/.local/bin. We need to add this to PATH as well.   
3. edit `~/.bashrc` in something like `Kate` or `vim`, add this to the end of the file:
```bash
if [ -d "$HOME/.local/bin" ]; then
  PATH="$HOME/.local/bin:$PATH"
fi
```
4. Test it's working:
```console
~/.local/bin/pip -V
```
5. Now we can install owocr:
```console
pip install owocr
```
6. And install manga_ocr:
```console
pip install manga_ocr
```
Reference: (https://www.reddit.com/r/SteamDeck/comments/x4ct1r/how_do_i_do_a_pip3_install/)

## Using OwOcr
`To be added`
</details>
