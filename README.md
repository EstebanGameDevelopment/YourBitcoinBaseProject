--------------------------
--------------------------
YOUR BITCOIN BASE PROJECT
--------------------------
--------------------------

This project is composed with 2 main submodules:

-YourBitcoinController: The basic Bitcoin controller to call to perform any operation

	Available scenes:
	
		Assets\YourBitcoinController\Scenes\BasicManager.unity 
		Assets\YourBitcoinController\Scenes\CreateKeys.unity
		Assets\YourBitcoinController\Scenes\SignTextData.unity
		Assets\YourBitcoinController\Scenes\SignImageData.unity
  
-YourBitcoinScreens: A collection of screens that help you to manager your Bitcoin account and operations

	Available scenes:
	
		Assets\YourBitcoinScreens\Scenes\YourBitcoinWallet.unity

-----------------------
-----------------------
YOUR BITCOIN CONTROLLER
-----------------------
-----------------------

Thanks to this plugin you will be able to include Bitcoin cryptocurreny and Blockchain signning authentication
in your games and applications.

TUTORIAL
--------

 1. SET UP THE RUNTIME:

	First of all, we make sure that the Scripting Runtime Version: ".NET 4.x Equivalent" in order for the NBitcoin DLL to work.
 
 2. INSTALLATION OF NBitcoin DLL:
 
	On Visual Studio open the NuGet console and run the command line: "Install-Package NBitcoin"
	
	After installing the DLL you will be able to run the code without problems.

  3. Run the scene BasicManager.unity and you will be able to perform operations with Bitcoins.
  
	 Follow the instructions on the video tutorial:
	 
		https://youtu.be/5Nj8FKymhjc
		
  4. Run the scene CreateKeys.unity to create new wallets
  
	 Follow the instructions on the last part of the video tutorial (time 2:32):
	 
		https://youtu.be/5Nj8FKymhjc?t=2m32s
		
  5. Run the scenes SignTextData.unity and SignImageData.unity to sign data and document using your keys
  
	 Follow the instructions on the video tutorial:
	 
		https://youtu.be/5Nj8FKymhjc?t=3m16s
		
--------------------------
--------------------------
YOUR BITCOIN SCREENS
--------------------------
--------------------------

Thanks to this plugin you will be able to include Bitcoin cryptocurreny and Blockchain signning authentication
in your games and applications.

TUTORIAL INTEGRATE BITCOINS IN YOUR APP/GAME
-----------------------------------------------

 1. SET UP THE RUNTIME:

	First of all, we make sure that the Scripting Runtime Version: ".NET 4.x Equivalent" in order for the NBitcoin DLL to work.

 2. RUN THE SCENE:
 
		Assets\YourBitcoinController\Screens\Scenes\YourBitcoinWallet.unity
		
 3. OR FOLLOW THE INSTRUCTIONS OF THIS VIDEO TUTORIAL TO INTEGRATE BITCOIN IN YOUR APP/GAME:
 
	https://youtu.be/LLz3_BFcWic

 4. CREATE NEW PROJECT AND IMPORT YourBitcoinController PACKAGE
 
 5. DRAG THE PREFABS TO THE SCENE:
 
		Assets\YourBitcoinController\Screens\Resources\Prefabs\ScreenBitcoinController.prefab
		Assets\YourBitcoinController\Screens\Resources\Prefabs\LanguageController.prefab
		
 6. ADD UI\EventSystem TO THE SCENE.
 
 7. CREATE A NEW GAMEOBJECT AND ATTACH IT A SCRIPT CALLED Example.cs
 
 8. OPEN THE SCRIPT AND ADD THE CODE INSTRUCTION THAT WILL ALLOW YOU TO OPEN THE WALLE SCREEN.
 
 9. FOLLOW THE INSTRUCTIONS IN THE VIDEO TO ADD BITCOIN FUNDS
 
 10. MODIFY THE SCRIPT AND USE THE INSTRUCTION TO OPEN THE SCREEN THAT WILL ALLOW YOU TO SEND CASH
 
 11. AFTER PERFORMING THE OPERATION YOU CAN CHECK IN TRANSACTIONS' SCREEN THAT THE OPERATION HAS BEEN DONE.
 		
 
