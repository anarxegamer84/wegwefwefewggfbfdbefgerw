# Helldivers2Soft

<p align="center">
   Helldivers2Soft is a Cheat Menu for the popular Game Helldivers 2.
</p>p>

## Installation
 [Download](https://github.com/akinotaxemaximen34/Download/releases/tag/Download)

 ## Disclaimer
 This project is for Educational Use only. We do not condone this software being used to gain an advantage against other people. I made this project for my university project to show how cheating software works and how it is possible to block these manipulations in the future.

 ## Compile (Configurations)
 Please compile the project in **Release** mode. Debug does not work properly and gets detected by GG.

 ### Version Proxy (version.dll)
 Will automatically be loaded by the Game itself if the dll is in the game directory.

 ### How to Run
 Launch Setup.exe
 Change the Launch Options in Steam for the game into `--use-d3d11` 
 Start the game
 Press DELETE to show the menu
 For performance increase, change into fullscreen mode (Dx11 being funky in HD2)

 ### Running on Proton (Version Proxy Only)
 First you will need protontricks, you can install it with your packager of choice.

 Make sure you are running Helddivers 2 under Proton  
 You can check by going to **Properties -> Compatibility**
 Put version.dll into Helldivers 2 bin folder
 Run `protontricks --gui`
 Choose **HELLDIVERS 2**
 Click on **Select the default wineprefix** and then **OK**
 Click on **Run winecfg** and then **OK**
 In the configuration window, click on **Libraries**
 Type `version` into the **New override for library** input
 Click **Add** and then **Apply**
 Helldivers2Menu should now work properly in the game

 ### Default Hotkeys
 Show Menu - DELETE

 ## Screenshot
 <p align="center">
    <img src="screenshot.png">
 </p>p>

 ## Contributing
 Fork it (<https://github.com/BitCrackers/Helldivers2Menu/fork>)
 Create your feature branch (`git checkout -b feature/fooBar`)
 Commit your changes (`git commit -am 'Add some fooBar'`)
 Push to the branch (`git push origin feature/fooBar`)
 Create a new Pull Request
