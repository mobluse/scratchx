## ScratchX by MOBLUSE

- [ScratchX](http://scratchx.org)

### See demo video on YouTube

- [SpeakTweet: ScratchX Project that uses Twitter & Text to Speech](https://youtu.be/2EpZ1zx6DRU)

### Open sbx-files directly

- [speaktweet.sbx](http://scratchx.org/?url=https://mobluse.github.io/scratchx/speaktweet.sbx)
- [weather-lund-se.sbx](http://scratchx.org/?url=https://mobluse.github.io/scratchx/weather-lund-se.sbx) This is a remix for Lund.
- [snake4sensehat.sbx](http://scratchx.org/?url=https://mobluse.github.io/scratchx/snake4sensehat.sbx) This requires SenseHAT or an emulator.
- [Wormy Snake 4 AstroPi SenseHAT RaspberryPi](https://scratch.mit.edu/projects/172284158/) The above w/o SenseHAT and more instructions.

### Download sbx-files

If you have Raspberry Pi 3 or 2 with Raspbian and want to use Scratch 2: Rename the file extension from sbx to sb2 and open the project in Scratch 2. Copy an URL from from a comment in the project, Shift+click *File* menu, select *Import experimental extension*, paste in the URL, and click Load. Repeat from "Copy an URL..." if you need more ScratchX extensions.
- [speaktweet.sbx](http://mobluse.github.io/scratchx/speaktweet.sbx)
- [weather-lund-se.sbx](http://mobluse.github.io/scratchx/weather-lund-se.sbx) This is a remix for Lund.
- [snake4sensehat.sbx](http://mobluse.github.io/scratchx/snake4sensehat.sbx) This requires SenseHAT or an emulator. You must first add the SenseHAT-extension in the More Blocks category.

### About SpeakTweet in Swedish

Hej,  
jag har gjort en video som visar ett ScratchX-projekt som högläser tweets på Twitter som innehåller ett visst ord -- just nu #RaspberryPi:  
[https://youtu.be/2EpZ1zx6DRU](https://youtu.be/2EpZ1zx6DRU)  
Mer information om projektet som är öppen källkod finns här:  
[https://mobluse.github.io/scratchx/](https://mobluse.github.io/scratchx/)

Man behöver bara klicka på en länk och vänta en stund medan projektet laddas och sen klicka på grön flagga. (Det var en bugg tidigare som gjorde att alla extensions inte laddades, utan man fick ladda in vissa manuellt, men det verkar fungera automatiskt nu.)  
[http://scratchx.org/?url=https://mobluse.github.io/scratchx/speaktweet.sbx](http://scratchx.org/?url=https://mobluse.github.io/scratchx/speaktweet.sbx)  
Instruktioner finns i en kommentar i projektet:  
' Click a green flag. It reads selected tweets aloud. Tweets are selected if they contain a word: now "#raspberrypi", and are not replies. An alarm starts sounding after that and you need to stop it by clicking the bell. Tweets are also stored in a list with the latest on top.

Sometimes Twitter doesn't load automatically, but then you can load it using Load Experimental Extension in More Blocks:  
https://technoboy10.github.io/twitter/extension.js

Text to Speech, in case you need to load that manually:  
http://sayamindu.github.io/scratch-extensions/text-to-speech/text_to_speech_extension.js '

Man måste möjligen också ha installerat något uppläsningssystem i Chrome/Chromium. Jag har SpeakIt! 0.2.995.

ScratchX är ett system för att utvidga Scratch2 med extensions skrivna i JavaScript. Det finns t.ex. en extension för att koppla till Arduino UNO, men jag har inte testat den. Det finns en annan extension för att koppla till en vädertjänst och den har jag testat för Lund.

Det finns ett forum för hur man utvecklar Scratch extensions. Jag skrev frågor här och de problemen är lösta:  
[https://scratch.mit.edu/discuss/topic/265410/](https://scratch.mit.edu/discuss/topic/265410/)  
[https://scratch.mit.edu/discuss/topic/265601/](https://scratch.mit.edu/discuss/topic/265601/)

Det finns en officiell lista med extensions [http://scratchx.org/#extensions](http://scratchx.org/#extensions) och även en inofficiell:  
[http://savaka2.github.io/scratch-extensions-directory/](http://savaka2.github.io/scratch-extensions-directory/)

ScratchX-projekt kan även fungera i Raspberry Pi 2 och 3 om man använder den inbyggda Scratch 2 och byter filändelse från sbx till sb2, samt laddar extensions manuellt. De kan även fungera i webbläsaren Chromium i Raspbian, ty den har inbyggd Flash.

ScratchX är bra för dem som kan Scratch 2 eftersom det gör det möjligt att skriva Scratch-program som kopplar mer till Internet och hårdvara. Man kan skriva egna extensions i JavaScript som t.ex. skickar e-brev via GMail. Det kan motivera mer avancerade elever att lära sig JavaScript, ty man kan hjälpa elever som bara kan Scratch att skriva mer verklighetsnära program.
