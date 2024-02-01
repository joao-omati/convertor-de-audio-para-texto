from gtts import gTTS
from playsound import playsound
import os

print('Lendo Texto...')
with open('texto.txt', 'r') as file_to_read:
    my_text = file_to_read.read().replace('\n', ' ')
language = 'pt-br'
tts = gTTS(text=my_text, lang=language, slow=False)
filename = 'audio.mp3'
tts.save(filename)
playsound(filename)
os.remove(filename)
print('Finalizando...')
