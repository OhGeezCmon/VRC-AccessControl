# Access Control
Author: OhGeezCmon

Description: Allows a set of predefined Admins to give admin access to a range of game objects.  Useful for ensuring only certain players can access certain objects.

## Installation Guide
Simply download and import the latest **Unity Package** from [**Releases**](https://github.com/OhGeezCmon/VRC-AccessControl/releases) on GitHub

Relies on TextMeshPro so if you get a popup click at least "Import TMP Essentials".

## How to Use
- Any players that you would like to have permanent access add to the "Players With Starting Access" variable on "AccessController"
- Set which objects are privileged to the "Controls" variable on "AccessController".  Ensure they are disabled before you upload the world
- Once in the world follow the directions on the control pad.  Click on a player to enable Admin access.  Admins will see not only the "Control" objects but also the Controller itself
- **NOTE** Admins can remove or add other Admins and Players, but not themselves.  This is to prevent accidentally removing your own access
- Instance Owners (Red), Master (Green) and Permanent Players (Yellow) **cannot** be removed

## Attribution

The following assets were used under the Creative Commons license:

- SimpleIcon http://www.simpleicon.com/, CC BY 3.0 <https://creativecommons.org/licenses/by/3.0>, via Wikimedia Commons
- Eurostile Font (https://freefontsfamily.com/eurostile-font-free/)
- Special mention to AudioLink for their Controller design.  I designed my controller the same way.

## Contacting Me
Feel free to contact me on Discord (ohgeezcmon) or leave a suggestion or issue on the [Issues](https://github.com/OhGeezCmon/VRC-AccessControl/issues) page.
