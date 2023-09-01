Description -
An Easy, Lightweight add-on for Metagameswap's blockchain services allows access to various web services through a unity application.
Ships with a modifiable GUI to allow for customization that suits your needs.

System Requirements -
Unity 2020.3 or later
Built for WebGL, Windows, MacOS, Android & iOS platforms

Important notes & limitations -
Heavily dependent on Vuplex's WebView package, and therefore introduces certain UI-based limitations. (For example, disallows scaling the canvas down to (0, 0, 0).)

Technical Details -
Canvas overlay-based GUI.
Lightweight add-on for Metagameswap's blockchain services.
Cross-platform.

Dependencies -
https://assetstore.unity.com/packages/tools/gui/2d-webview-for-webgl-web-browser-iframe-202522

Developer integration & Tutorial -

Video documentation - https://youtu.be/-3MhREGFFnM
Steps to generate an API key -
1. Navigate to https://app.metagameswap.io/signin
2. Register your email address and verify your email
3. Login at https://app.metagameswap.io/login
4. The profile page includes your API key, and all transactions perfomed using that API key.

Steps to Integrate Unity plugin -
1. Install dependencies.
    a. Webview WebGL - https://assetstore.unity.com/packages/tools/gui/2d-webview-for-webgl-web-browser-iframe-202522
    (Native versions of the webview package would work as well.)
2. Navigate to the Releases folder and install the latest package in your Unity project.
3. Navigate to the Metagameswap folder in the Unity project, drag and drop the MetagameswapContainer prefab into the scene.
4. Paste in your API key within the component.

User demo - 
Video - https://youtu.be/MZA-pLC6i4M

How to navigate on Metagameswap -
How to connect your Wallet - Use the connect wallet button to connect your external wallets.
How to change the network - Use the network button to select the network. (Currently supports Polygon, Ethereum and Binance)
How to select tokens to swap - Use the token drop down to select the tokens to include in the swap.
How to adjust slippage - Use the cog wheel (Settings icon) to adjust the slippage.

