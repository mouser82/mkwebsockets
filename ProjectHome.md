# MkWebSockets module for Monkey #
Version 1.0 beta

## Introduction ##

This module enable you to create a WebSockets client (fully RFC 6455 complient) on the fellowing targets of Monkey.

  * XNA (Windows)
  * HTML5
  * Android

If you don’t know what WebSockets are i invite you to get infos there : http://en.wikipedia.org/wiki/WebSocket

## Prerequisites ##

- You need Monkey at least version 66. (Have not been tested with previous version)
- This module need obviously a WebSocket server to function which is not included with the module. You will have to setup your own. However, this module have been tested with a popular C# WebSocket server called « SuperWebSockets » that can be found here : http://superwebsocket.codeplex.com/

## Installing the MkWebSockets module for Monkey ##

  1. . Extract the content to the « Modules » directory of Monkey.
  1. . In the directory extracted in (1) you will find a « Targets » directory. You must use those pre-defined v66 targets and the replace the default ones of Monkey (keep a backup of the original ones) if you want to build on the targets XNA and Android since they use librairies which are available in sub-directories below :
  1. . Note : For the XNA target, you may need to open the solution and reset the library path for « WebSocket4Net ». This is only applicable if you have errors while building your project.

**Librairies location**

  * XNA : xna\MonkeyGame\MonkeyGame\Libs
  * Android : targets\android\libs

## Support ##

There is a demo file « mkws\_demo.monkey » located in the root of the module that showing how to use the module.

I can answer questions regardings this module but i won’t offer any support regarding a WebSocket server implementation. This is up to you to figure out how to setup the whole thing server-side.

## Licence ##

Copyright 2012 Sébastien Guillemette (aka Rushino)
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.