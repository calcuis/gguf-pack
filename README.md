# gguf-pack
clone the pack and install the dependencies required
```
pip install -r requirements.txt
```

## cuda user
uninstall torch (if you executed the command above)
```
pip uninstall torch
```
install it again with nvidia cuda
```
pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cu126
```

### run it with (if no py command, use python/python3)
```
py main.py
```
for dry running, you could use the portable pack under **releases**

![screenshot](https://raw.githubusercontent.com/calcuis/comfy/master/gguf-pack.png)

metadata inside the sample picture above (drag to browser for workflow)

### major difference between gguf-pack and gguf-comfy
- gguf is a core node in gguf-pack
- gguf is a custom node in gguf-comfy

### references
- ui-codebase: comfy
- base: llama.cpp
- gguf-node
- gguf-connector
