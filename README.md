# AutoBuild-OpenWrt

## Usage
    
**1. Compile Firmware**
  - Click `[.github/workflows]` folder on the top of repo and you could see few workflow files, Each for one particular architecture(device).
  - Edit the workflow file you desire，uncomment push section 3 lines together and submit the commit.(Other 2 methods wait you to discover)
  - The build starts automatically. Progress can be viewed on the Actions page.
  - When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.

**2. Sync Code**
  - Uncomment 'push-branches-master' 3 lines under **`On`** section and commit changes to let the script sync the code once for you.
  - Uncomment 'schedule-cron' 2 lines under **`On`** section and commit changes to let the script sync the code everyday on 3 am[UTC +8]
