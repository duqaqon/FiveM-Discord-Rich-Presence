[lisence]: https://github.com/duqaqon/FiveM-Discord-Rich-Presence/blob/master/LICENSE
[version]: https://github.com/duqaqon/FiveM-Discord-Rich-Presence/blob/master/version.md




[lisence-shield]: https://img.shields.io/github/license/duqaqon/FiveM-Discord-Rich-Presence
[version-shield]: https://img.shields.io/badge/version-1.1-success


[ ![lisence-shield][] ][lisence]
[ ![version-shield][] ][version]



<img align="right" src="https://cdn.discordapp.com/attachments/617625850111852545/757669418045276320/a.png" height="200" width="200">

### Status: Working 2021, supported.
# FiveM Selfhosted Rich Presence
This project is made for people/clients who wants a rich presence for their own FiveM server. Pictures and design needs to be made by yourself in the developer portal.

## Setup

Firstly, [download](https://github.com/duqaqon/FiveM-Discord-Rich-Presence/releases/tag/v1.1) this repo as a zip or .torrent file. 

**ZIP:** Un-extract the .zip file using WinRAR or an another extractor.

**TORRENT:** Download the .torrent file. Then use your torrent client to download it. (Recomended torrent clients. Windows: µTorrent. Mac: qBittorent. Linux: Transmission)

Second, put the downloaded folder in your server resources folder.

Third, go to **fxmanifest.lua** and change the manifest version to your server manifest version.

Fourth, go to [discord developer portal](https://discord.com/developers/applications) and make an rich presence with your pictures. 
**REMEMBER THE NAME OF THE BIG IMAGE AND SMALL IMAGE**

Now the big part. Go to **SetDiscordAppId** and replace "0" with your application client id.

Next, head over to **SetDiscordRichPresenceAsset** and replace "hi big" with the picture name you gave the big image. 

**(REMEMBER, KEEP THE "")**

Last but not least, locate to **SetDiscordRichPresenceAssetSmall** and replace "hi small" with the picture name you gave the small image. Keep the "".

Well thats all. If you have any issues please create an issue on this repo or join the discord server.


## Contributing
Pull requests are welcome.
Fork this project then send a pull request. 

*For major changes, please open an issue.*

Tutorial on how to make pull requests, click [here](https://github.com/DV8FromTheWorld/JDA/wiki/5%29-Contributing#creating-a-pull-request)
**Tutorial made by the JDA group, [Credits](https://github.com/DV8FromTheWorld)**

## Lisence
You may use this project under the [MIT](https://choosealicense.com/licenses/mit/) lisence.
If you remove any credits in the project/source code, I will take legal actions.

``©2021 duqaqon. All rights reserved``
