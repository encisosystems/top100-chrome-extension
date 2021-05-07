# top100-chrome-extension

This extension takes a random image from our collection of 100 best images
and renders it when the user opens a new browser tab. In the lower left corner
the logo of our official site is displayed next to the title and image credit.

### Directory tree
```
• LICENSE      
• manifest.json
• README.md
+ icons/
    • ESA-Hubble128.png
    • ESA-Hubble32.png
    • ESA-Hubble64.png
+ top100/
    • popup.css
    • popup.html
    • popup.js
    • top100.css
    • top100.html
    • top100.js
    • xmlToJSON.js
    + img/
        • logo.png
        • popup.jpg
```

## Development ##

### Manifest ###

Every extension has a JSON-formatted [**manifest**](https://developer.chrome.com/docs/extensions/mv3/manifest/)
file, named manifest.json, that provides important information. Using
[manifest.json](manifest.json), you specify basic metadata about your extension
such as the name and version, and can also specify aspects of your
extension's functionality (such as background scripts, content scripts, and browser actions).

> We strongly recommend you check this [link](https://developer.chrome.com/docs/extensions/mv3/devguide/)

### How to get this repository ###

Clone the repository, and update your origin url: 
```
git clone https://github.com/encisosystems/top100-chrome-extension
```

### Main feature overview ###

Our [extension](https://chrome.google.com/webstore/detail/esahubble-top-100-images/nkhniebockeoppojmcbcgphpmpdladgo) 
modifies the new tab of the Google Chrome browser to render an image from the 
Top 100 collection from the ESA/Hubble [site](https://esahubble.org/). The images 
are obtained with a query to an API that provides the information in XML format 
from which the image title and the url of the resource are extracted.

### Unpacked extension ###

Once the repository is cloned, you can start developing new
features or customizing our source code. To test the extension
in development you must access the extensions panel of your
Google Chrome browser and enable developer mode. With the
developer mode active you must load the unzipped extension
and perform the corresponding tests

### Main feature overview ###

## Production ##