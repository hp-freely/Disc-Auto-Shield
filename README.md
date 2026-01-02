# Disc Auto Shield
Automatically engages the shield pack when shooting disclauncher.

### Summary
This script will automatically engage the shield pack when shooting the disclauncher. However, the true purpose of this script is to engage the shield pack when you perform discjump. This will ensure you use the least amount of energy / take the least amount of damage. There is obviously no way to differentiate  between shooting your disc into the air or performing a discjump, so the shield pack will just always engage.

This is a modification of the original script "borShieldSki.vl2". The following items describe behavior.
* If you have a shield pack equipped, and you fire your spinfusor, and your shield pack *is not* currently enabled, then this script will auto-enable your shield pack for a brief moment so that you don't take damage (granting that you have enough energy available). The shield will be automatically disabled after the DJ action.
* If you have a shield pack equipped, and you fire your spinfusor, and your shield pack *is* currently enabled, then no action will be taken. Your shield pack will continue to be enabled without change.
* This script modified the borShieldSki.vl2 script as follows:
  
1. You could enable / disable the original script via keybind. We have enough keybinds. We don't need more. I have moved the configuration to a Script UI. I suppose I can see an argument for wanting to quickly enable / disable it depending on the situation in game, but that seems quite unlikely.
2. The original script automatically turned on the script for *all* weapons. This script only enables it for the spinfusor.
3. In the original script, once the shield was turned on, it remained on until you manually turned it off. This in itself makes no sense. If you're performing a DJ, then you want to use as little energy as possible for that action. For example, if you turn on the shield to DJ, and then immediately jet after, but you do not turn off the shield, then you're wasting an enormous amount of energy.
