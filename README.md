Python bindings for whisper.cpp
===============================

# Note this is Fork used for private use only. Please see the original for your uses.

---
`pip install git+https://github.com/ysenarath/whispercpp.py`

```python
from whispercpp import Whisper

w = Whisper('tiny')

result = w.transcribe("myfile.mp3")
text = w.extract_text(result)
```

Note: default parameters might need to be tweaked.
See Whispercpp.pyx.
