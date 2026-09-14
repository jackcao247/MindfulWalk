# Mindful Walk

Currently only Temple University area with integration of Philadelphia street lights data

## How to run

From this folder, with Python installed:

```powershell
py -3.12 -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000/.

## Quick description

At current stage, it fetch street lights data in a small rectangle around Temple, each light return x, y coordinates, then apply it on Leafleet
