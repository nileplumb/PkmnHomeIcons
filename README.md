Pokémon Home style Icons for various Pokémon Go Map and Bot Projects

Most modern projects you will want to use a UICONS link such as 

128x128 Optimized, with outlines and shadows

https://raw.githubusercontent.com/nileplumb/PkmnHomeIcons/master/UICONS_OS_128/index.json

512x512 Outlined and Shadows

https://raw.githubusercontent.com/nileplumb/PkmnHomeIcons/master/UICONS_OS/index.json

512x512

https://raw.githubusercontent.com/nileplumb/PkmnHomeIcons/master/UICONS/index.json

RDM now uses local hosted UICONS format, periodically git pull to your server and configure appropriately

PMSF Outlined + Shadows (128x128) Optimized.

iconRepository = 'https://raw.githubusercontent.com/nileplumb/PkmnHomeIcons/master/pmsf_OS_128/';

or download if using locally

PMSF 512x512

iconRepository = 'https://raw.githubusercontent.com/nileplumb/PkmnHomeIcons/master/pmsf/';

PMSF Outlines and shadows 512x512

iconRepository = 'https://raw.githubusercontent.com/nileplumb/PkmnHomeIcons/master/pmsf_outline_shadow/';


The PMSF folder should also be compatible with some popular reporting bots (hence some duplicate images and sub folders.)

Currently PMSF still uses some local static files (eggs, grunts etc) so you may want to manually replace some of the images you host locally inside the following PMSF folder

/PMSF/static/

Simply replace / rename any images you want from the Alternative Egg designs, grunts subfolder, or misc etc (eg Slider images for nests and stardust)

You may need to rebuild PMSF after replacing images, same as when you update your build.

npm install && npm run build


Any donations very welcome if you want to support my personal morale / upkeep of image repo's

Paypal:

https://paypal.me/NilePlumb

Bitcoin:

1L6XpE4AU8XfRGyxPWWaLA4VacSw9vCBRx
