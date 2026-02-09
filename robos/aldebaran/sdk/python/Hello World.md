Depois de ter seguido as instruções de instalação.
```python
from naoqi import ALProxy
tts = ALProxy("ALTextToSpeech", "<IP do robo>", 9559)
tts.say("Hello, world!")
```