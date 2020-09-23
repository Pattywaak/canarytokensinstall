## STEP 1:

Download the github package
```
git clone https://github.com/Pattywaak/canarytokensinstall.git
```
## STEP 2:

Change to the canarytokensinstall directory
```
cd canarytokensinstall
```
## STEP 3:

Change the permissions of the canaryinstaller
```
sudo chmod +x canaryinstaller
```
## STEP 4:

Execute the bash file as sudo
```
sudo ./canaryinstaller
```
## STEP 5:

The packages should be installing, wait for these to be finished and provide variables to the questions. If you make an error with the configuration of canarytokens, repeat steps 3 and 4 with canary_reconfig. 

## STEP 6:

Start up the CanaryTokens server 
```
sudo docker-compose up
```
