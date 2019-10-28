# launchbox-data-xml-for-MAME-sets
Allows you to instantly import an up-to-date set of MAME Software ROMS and CHDs into Launchbox

## Instructions:

1. Download all MAME sets without their torrent-name subfolders into `<Your LaunchBox Dir>/Games/MAME/`. So, for example, you should have the file `<Your LaunchBox Dir>/Games/MAME/saturn/2taxgold/2tax gold (t-4305g).chd`.
2. Download this torrent as a zip
3. Extract the torrent to your LaunchBox directory. You may want to take a backup of your existing platform XML if you have any defined.

Alternatively, you can use git commandline tools to git pull these files before starting Launchbox, if you update your MAME sets as they're released.

## Contributing:

I'm only one guy so I can't fix all the metadata myself. Each platform needs a 'steward', also to make sure the Launchbox database gets updated with any missing titles.

1. Create a github issue for the platform you want to create to reserve the platform for yourself. This stops others duplicating the same work.
2. Use Launchbox to define your XML, making sure you use the folder structure I mention above, and the latest MAME CHD sets.
3. Create a pull request with the updated XML file. I'll check the folder structure, and will accept ASAP.
4. If you want to do a rough cut first, and then do another update later, please feel free. Anything is better than nothing.
