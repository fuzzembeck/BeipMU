# How to install on MacOS using Wineskin

## Install Fonts

If you don't already have it, find and download the Segoe UI and the Segoe UI Emoji ttf files. Any friend with a Windows PC can give these to you. I don't know a guaranteed safe place for it. (Or ask on our Discord and we can send it to you)

These should be manually dragged to the Mac (Or Macintosh HD)/Library/Font folder and dropped there. That should be all it takes to activate them. It seems to be more reliable than dragging it into the user one.

## Install Homebrew

Install Homebrew: https://brew.sh/

Click on the link and the rest is self-explanatory. You'll need to paste the command string it gives you on that page into your MacOS Terminal shell prompt.

## Install Sikarugir

Install Sikarugir: https://github.com/Sikarugir-App/Sikarugir
* You can paste this into your MacOS Terminal shell prompt:
 
`brew upgrade
brew trust Sikarugir-App/sikarugir
brew install --cask Sikarugir-App/sikarugir/sikarugir`

## Using Wineskin

* Download the latest x64 version of Beipmu: https://github.com/BeipDev/BeipMU/releases
  * Unzip it and put the folder in a convenient location. You'll need it later.
 
* Open Sikarugir creator. Where it says 'No engine selected', click change. Then click the download icon next to WS11WineCX21.2.0. 

* After that, you'll want to click 'Create'. 
  * Name it 'beipmu' (it'll append .app to it)
  * Press save. It'll take a few moments, with wine-preloader popping up and closing several times. 
 
* When it finishes, a popup will appear. Select 'Show in Finder'
  * Move it to an easily accessible location.
  * Click it and select 'Install Software' in the bottom left.
  * In the new window, select 'Copy a Folder Inside'.
  * Find the unzipped Beipmu folder (like beipmu_323_x64 or whatever) and select it.
  * In the new 'Choose Executable' menu, select beipmu.exe. Press OK.
  * Close the 'Configure' window.

# Running BeipMU

Open beipmu.app again. It should now launch Beipmu.

At this point, you'll definitely find out if you have the correct font file or not. There won't be any icons in the bottom left corner.

Even if there are icons, you might not see the burger menu (you can click on it, you just can't see the icon for it). Either way, hit the option key (which is the alt key equivalent for Macs), navigate to where you can see the Font button for the UI Interface, and then select another font, like Segoe UI. Or anything really. Beipmu defaults to Calibri, and that doesn't seem to be a font that comes with most Macs.

Everything else should work as expected!
