# OCR
I'll be going through [OwOcr](https://github.com/AuroraWright/owocr) here. If you're comfortable with installing software through pacman, you can also check out YomiNinja.

## Install OwOcr
1. install pip first. Open Konsole and type or paste in following:
```console
python -m ensurepip --upgrade
```
This will install pip into ~/.local/bin. We need to add this to PATH as well.   
2. edit `~/.bashrc` in something like Kate, add this to the end of the file:
```bash
if [ -d "$HOME/.local/bin" ]; then
  PATH="$HOME/.local/bin:$PATH"
fi
```
3. Test it's working:
```console
~/.local/bin/pip -V
```
4. Now we can install owocr:
```
pip install owocr
```

Reference: (https://www.reddit.com/r/SteamDeck/comments/x4ct1r/how_do_i_do_a_pip3_install/)

## Using OwOcr
`To be added`
