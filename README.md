<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#features">Features</a></li>
    <li><a href="#commands">Commands</a></li>
  </ol>
</details>

<!-- Features -->
### Features

- Generate skins with the known `!gen` and `!gengl` commands
- Edit skins directly with some helper commands e.g. changing the seed with `!pho seed` (See more under commands)
- Generate any skin from an inspect url by just pasting the url into the chat.

- This plugin does not save any skin to play with it multiple rounds and it will stay like this! This is not a classical skin changer. Its for previewing skins!

<!-- Commands -->

## Commands

Info: `!gen` and `!gengl` are supported but are just aliases for `!pho gen`<br/>
For `!i <inspect-url>` you should just paste the inspect url into the chat!

| Syntax| Description |
|---------|-------------|
|`!pho help` | Shows you a list of all commands in a similar fashion|
|`!pho gen <defIndex> <paintIndex> <paintSeed> <paintWear> [<stickerslot1> <stickerslot1wear>...]`|Generate a skin - `!gen` and `!gengl` are still available!|
|`!pho skin <paintIndex>`|Set skin index of the weapon you are currently holding|
|`!pho seed [paintSeed]`|Set seed of the weapon you are currently holding to a specific one or leave the paintseed blank for a random one|
|`!pho float <paintWear>`|Set float of the weapon you are currently holding|
|`!pho sticker [<stickerslot1> <stickerslot1wear>...]`|Set stickers of the weapon you are currently holding (without arguments will remove any stickers)|
|`!pho rename [newName]`|Add or remove nametag of weapon you are currently holding (without newName argument will remove the nametag)|
|`!pho stattrak <1\|0> [count]`|Enable/Disable stattrak of weapon you are currently holding|
|`!pho gloves skin <paintIndex>` |Set gloves skin|
|`!pho gloves float <paintWear>` |Sets gloves float to a specific float|
|`!pho gloves seed [paintSeed]` |Set gloves seed to specific one (without argument will choose a random seed)|
