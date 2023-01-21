# Anycubic Kobra Dark UI
A dark and improved UI for the Anycubic Kobra 3d printer (ONLY the Anycubic Kobra)

### Disclaimer
I am not responsible for any damage or malfunction caused to your printer because of those files. Any modding made to your printer is made at your own risk, this includes any damage that could happen in real life.

### Description
I happened to use the printer quite often in the dark and the default white UI was occasionally killing my soul so I decided to make this improved dark UI. It provides better translations, more explicit buttons and much more...

![Preview 1](https://i.ibb.co/pRTJzXQ/121.png)
![Preview 2](https://i.ibb.co/fMq9QhM/122.png)
![Preview 3](https://i.ibb.co/zfGxMkp/128.png)
![Preview 4](https://i.ibb.co/XWwMxmf/135.png)
![Preview 5](https://i.ibb.co/txrfPN1/137.png)
![Preview 6](https://i.ibb.co/jvkBcLq/153.png)

### Features
- Brand new UI look with a dark theme
- Starting animation shortened to remove the fading to white
- Improved buttons placements and size (bigger buttons for those who were too small and hard to tap)
- Improved translations for less ambiguity
- Much better image compression for less artifacts (The default UI was really bad)

### Known issues
Note: These issues are not planned to be fixed (The first two requires motherboard firmware modification from my understanding which is beyond my knowledge)
- The file selection menu text becomes blue after being deselected instead of white
- The number input page input text is blue instead of white
- The language button was disabled (This is not an issue in itself but I put it here so people can see it's no an issue)

### Other things to know
You can build the UI yourself using the DGUS Editor software and by opening the project in it. The .icl file contains all the compressed images, so if you want to update the images you only need to rebuild the .icl file.

# How to install
### Updating your printer screen to the latest version
1. Go to your printer -> Settings -> About -> UI Version -> If you're on Anycubic_20211220 you can skip to installing the modded firmware
2. Head on to the official page of the Anycubic Kobra (https://www.anycubic.com/products/kobra)
3. Scroll down and download the Firmware V2.7.9 OR you can build your own firmware from the Anycubic Github repository (V2.8.2).
4. Follow the instructions in the Read Me.txt of their file
5. If the installation succeed you should see `SD card Process... END !` at the top, you can then turn off the printer and remove the SD card

 ### Installing the modded UI firmware
 1. Download the latest release in the release tab (https://github.com/jojos38/ancubic-kobra-dark-ui/releases)
 2. Unzip the DWIN_SET folder at the root of your SD card (make sure to use a reliable SD card, the one shipped with the printer is not), do not put anything else but this folder, if you had the old folder from the official firmware, **remove it before**
 3. Turn off your printer put the SD card **under the screen**, not in the printer the body. Make sure to leave it unplugged for 10 - 20 seconds to make sure the caps can discharge (Thanks to SineVVAVz for the tip)
 4. Turn on your printer and wait until you see `SD card Process... END !` on the second line, do NOT turn off the printer before this line appears. The process shoudn't take more than 5 minutes unless your SD card is broken or very slow
 5. Make sure the number next to .BIN Files shows `003` and the number next to .ICL Files `001`
 6. Turn off your printer, remove the SD card
 7. Done, you can turn it on
 
 # FAQ
 ### Can I revert to the old version if I don't like it?
 Yes you can, just follow the steps to update the screen firmware to the latest version above
 
 ### Are there any risk in doing that?
 I have no idea if updating the screen firmware by itself is risky or not, maybe turning off the printer while it's updating could brick it, I don't know.
 That being said, the potentials risks of using the custom UI itself could be that I did something wrong causing the printer to not behave as expected. You should always keep that in mind when installing this UI and read the disclaimer at the beginning.
 
 ### I was using your firmware and I saw a gray page with a number on the top left
 This means that I forgot to make a page. If this happens please open a bug report on Github and provide the number that you saw on the top left and **what you did so that it happened**.
 
 ### Can I modify your files to make my own version?
 Yes you can, but please credit me if you publish it (unless you changed everything of course)
 To use my files, simply change the HTML code and execute index.js to generate all the .BMP files automatically.
 You need to at least know how to use HTML and CSS in order to make your own version from my files.
 Please note that I made all of this very quickly, I know the code is bad.
 
 ### I made my own version, I have the .BMP files, how do I go from that to a usable .bin and .icl files?
 Please refer to `Other things to know`
