
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
