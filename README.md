# automator-GetScreenshotTextEnglish
[Mac Automator](https://support.apple.com/en-mt/guide/automator/welcome/mac) service that will try to grab English text from a screenshot selection.  Please note that [Optical Character Recognition (OCR)](https://en.wikipedia.org/wiki/Optical_character_recognition) technology is not perfect and can only make a best guess. 

## Requirements
- Have [Tesseract](https://github.com/tesseract-ocr/tesseract) [OCR](https://en.wikipedia.org/wiki/Optical_character_recognition) [installed on your Mac](https://www.oreilly.com/library/view/building-computer-vision/9781838644673/95de5b35-436b-4668-8ca2-44970a6e2924.xhtml).  

## Installation
- Save `.workflow` file to `{YOUR HOME DIRECTORY}/Library/Services`.
- Go to `System Preferences > Keyboard > Shortcuts > Services`.
- In the list of services shown, select `General > Get Screenshot Text (English)`.
- Click on `Add Shortcut` button next to it, and type in any sequence of keys you want as a trigger for this new service.
  - Make sure it's unique and not an existing keyboard shortcut for anything else.
  - If you want to follow the existing pattern for the built-in screenshot shortcuts, refer to `System Preferences > Keyboard > Shortcuts > Screenshots`.

## Usage
- Type in the keyboard shortcut you created during workflow installation.
- This should prompt you select a screenshot.
- For best accuracy, try to select an area that only has English words -- no other icons, symbols, or pictures.
- The detected English text will be pasted onto a new [TextEdit](https://support.apple.com/en-mt/guide/textedit/welcome/mac) document.
- If there are any mistakes in text recognition, you can tweak it as needed before using the data as you need.
