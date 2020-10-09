## ASSUMPTIONS:
1) You have a Ubuntu VM running either Ubuntu Client or Ubuntu Server 
2) You have root privileges on the machine

## STEP 1:

Download the GitHub package.
```
git clone https://github.com/Pattywaak/canarytokensinstall.git
```
## STEP 2:

Navigate over to the canarytokensinstall directory, should be in the current working directory when you ran the command from the previous step.
```
cd canarytokensinstall
```
## STEP 3:

Change the permissions of the canaryinstaller to have execute prviliges
```
sudo chmod +x canaryinstaller
```
## STEP 4:

Execute the bash file as sudo
```
sudo ./canaryinstaller
```
## STEP 5:

Once the canaryinstaller script has finished, it is now time to prepare the canary-config. Similarly to step 3, the script must be given execute privileges.
```
sudo chmod +x canary-reconfig
```
Run the script and work through the prompts
```
sudo ./canary-config
```
## STEP 6:

Start up the CanaryTokens server 
```
sudo docker-compose up
```
