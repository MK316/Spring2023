# Code we've learned (to be updated)

```
x = 12
y = "Mary"
print(x)
type(y)
```

```
# Commenting
y + y # This is a comment too: only humans read this.
```


1. gTTS

```
!pip install gtts
from gtts import gTTS

def tts(text):
  tts = gTTS(txt, lang='en')
  tts.save("myaudio.mp3")
  return Audio("/content/myaudio.mp3")
  
```
2. display Audio (audio play)

```
from IPython.display import Audio

Audio("myaudio.mp3", autoplay = True)
# The audio file should be in the colab platform /content/myaudio.mp3
```

[More] Google Mount on Colab

```
from google.colab import drive
drive.mount('/content/drive')
```

```
# Unmount drive
drive.flush_and_unmount()
```

