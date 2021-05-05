# vscode-snippets
Official [nanos world](nanos.world/) Snippets for [VSCode](https://code.visualstudio.com/)!

![demo](https://i.imgur.com/hWMLlSk.mp4)


## How to Contribute


### General rules

All **Events** should be named as `CLASSNAME:SubscribeEVENTNAME`, e.g.: `"Client:SubscribeKeyUp` & `Character:SubscribeDeath`.

All **Methods** should be named as `CLASSNAME:METHODNAME`, e.g.: `"Player:GetControlledCharacter` & `Server:BroadcastChatMessage`.


### Static Classes

All [Static Classes](https://docs.nanos.world/scripting/static_classes/index.html) can follow the example of `Server.json`.

The prefixes of **Static Classes Methods** must contain the Class name and the method separated with `:`, e.g.: `Package:GetDirectories` & `Package:Subscribe("Load")`.

The prefixes of **Static Classes Events** should be named following the pattern `CLASSNAME:SubscribeEVENTNAME`, e.g.: `"Client:SubscribeKeyUp`.


### Classes

All [Classes](https://docs.nanos.world/scripting/classes/index.html) can follow the example of `WebUI.json`.

The prefixes of **Classes Methods** must contain only the method started with `:`, e.g.: `:SetViewMode` & `:SetHealth`.

The prefixes of **Classes Events** should be following the pattern `:SubscribeEVENTNAME`, e.g.: `":SubscribeTakeDamage`.'