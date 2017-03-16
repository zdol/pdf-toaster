PDF Toaster
=====

A simple-as-possible gui for compressing pdf files using ghostscript on macOS. Made with Applescript.

Compress those huge pdf files away! Minimal command line work is needed to setup and then compressing one or multiple pdf's is one click away.

## Setup

- Open Terminal.app
- Install [homebrew](https://brew.sh). Just copy/paste the long command found on homebrew's homepage.
- Install ghostscript:
 
```
$ brew install ghostscript
```

- [Download PDF Toaster](https://github.com/zdol/pdf-toaster/archive/master.zip), run it and follow the onscreen instructions. Best way to use it, is to press `⌘Command` and drag the app to the Finder toolbar (or drag to the dock) and use it as a droplet.

### Options

You can tweak some options for this app by directly editing the script: 

- Open `Script Editor.app` (found in /Applications/Utilities)
- Drag `PDF Toaster.app` on the Script Editor icon on the dock

You will now see some `property` items you can change:


```javascript
MOVE_ORIGINAL_TO_TRASH : false // whether or not to keep the original file
GS_PDFSETTINGS_OPTIONS : {"ebook", "printer", "prepress"} // the options you will have when running the app; from smaller to larger file size
GS_PDFSETTINGS_DEFAULT : "printer" // the default ghostscript compression setting
```


## Acknowledgements

Original ghostscript command found on [Max Lenister's blog](https://blog.omgmog.net/post/compressing-pdf-from-your-mac-or-linux-terminal-with-ghostscript/)

Original icon: [Toaster Icon by Greg Barnes](http://www.iconarchive.com/show/vintage-kitchen-icons-by-greg-barnes/Toaster-icon.html)




**This script is provided for free, as-is with no warranties.**
   

