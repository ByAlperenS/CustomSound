# CustomSound V1

# NOTE: Sound Files In This Pack Are Not Mine!
# Links:
 - https://mcpedl.com/ambient-sounds-add-on/



# How to Install
**Add CustomSound.zip file from this project to resource_packs folder. Then open resource_packs.yml and type CustomSound.zip in resource_stack**

# Use:
```php
use pocketmine\network\mcpe\protocol\PlaySoundPacket;
use pocketmine\Player;
```

# Usage:

```php
$packet = new PlaySoundPacket();
$packet->soundName = "custom.sound.cave";
$packet->x = $sender->getX();
$packet->y = $sender->getY();
$packet->z = $sender->getZ();
$packet->volume = 1;
$packet->pitch = 1;
$sender->sendDataPacket($packet);
```

# Contact:
**If you want more sounds added, you can contact me on Discord!**

**Discord:** ByAlperenS#2447

**Team Discord Server:** <a href="https://discord.gg/DPMkdKyEWW">![Discord](https://img.shields.io/discord/810589153276198972?label=Fear-Team&logo=Discord&style=flat-square)</a>
