# launchbox-data-xml-for-MAME-sets
Allows you to instantly import an up-to-date set of MAME Software ROMS and CHDs into Launchbox

## Instructions:

0. Make a backup of your Launchbox Data folder in case it all goes pear-shaped!
1. Download all MAME sets without their torrent-name subfolders into `<Your LaunchBox Dir>/Games/MAME/`. So, for example, you should have the file `<Your LaunchBox Dir>/Games/MAME/saturn/2taxgold/2tax gold (t-4305g).chd`.
2. Run `git init;git remote add origin https://github.com/slagfart/launchbox-data-xml-for-MAME-sets.git;git fetch;git checkout origin/master -ft` inside your LaunchBox folder. Warning! This will overwrite any existing data files in your LaunchBox folder with this repo, which may be less complete than your carefully curated set!
3. Whenever you like, run `git pull` in your Launchbox folder in order to update your XML to the latest version of this repo's contents

## Platforms done:

* Sega CD
