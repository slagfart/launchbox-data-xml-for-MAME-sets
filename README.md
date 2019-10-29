# launchbox-data-xml-for-MAME-sets
Allows you to instantly import an up-to-date set of MAME Software ROMS and CHDs into Launchbox

## Instructions:

1. Download all MAME sets without their torrent-name subfolders into `<Your LaunchBox Dir>/Games/MAME/`. So, for example, you should have the file `<Your LaunchBox Dir>/Games/MAME/saturn/2taxgold/2tax gold (t-4305g).chd`.
2. Run `git init;git remote add origin https://github.com/slagfart/launchbox-data-xml-for-MAME-sets.git;git fetch;git checkout origin/master -ft` inside your LaunchBox folder. Warning! This will overwrite any existing data files in your LaunchBox folder with this repo, which may be less complete than your carefully curated set!
3. Whenever you like, run `git pull` in your Launchbox folder in order to update your XML to the latest version of this repo's contents

## Contributing:

I'm only one guy so I can't fix all the metadata myself. Each platform needs a 'steward', also to make sure the Launchbox database gets updated with any missing titles.

1. Create a github issue for the platform you want to create to reserve the platform for yourself. This stops others duplicating the same work.
2. Use the Launchbox interfaceto define your XML, making sure you use the folder structure I mention above, and the latest MAME CHD sets.
3. Create a pull request with the updated XML file. I'll check the folder structure, and will accept ASAP.
4. If you want to do a rough cut first, and then do another update later, please feel free. Anything is better than nothing.
