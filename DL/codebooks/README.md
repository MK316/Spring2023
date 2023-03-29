# Code we've learned (to be updated)

1. gTTS

```
!pip install gtts
from gtts import gTTS

def tts(text):
  tts = gTTS(txt, lang='en')
  tts.save("myaudio.mp3")
  return Audio("/content/myaudio.mp3")
  
```
