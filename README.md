# homeassistantcontinousdelivery
Continuous Delivery Instructions for Home Assistant running on a docker container running on raspberry pi using a docker Jenkins setup

# Outline
1. Requirements
2. Git Setup
3. Jenkins Prep
⋅⋅* Host
⋅⋅* Container
4. Raspberry Pi Setup
5. Pipeline Code
6. Home Assistant Configuration
7. Config Update & Pipeline Execution
8. Future Enhancements

# 1. Requirements

# 2. Git Setup
App Credentials

# 3. Jenkins Prep
While jenkins will run on docker, I had it running on a separate host

1. install docker
2. install docker-compose
3. create jenkins docker-compose.yaml
4. Start service
5. install plugins
    git (github/bitbucket,etc)
    ssh-agent
6. setup 1st user
7. install credentials
    to pi
    to git repo
8. setup 1st pipeline
    poll SCM every minute
    run from Jenkins file at git address

# Raspberry Pi Setup
0. On Rapsbian
1. Install Docker
2. install docker-compose

# Pipeline Code
Jenkinsfile

# Home Assistant Configuration
configuration files

# Config Update & Pipeline Execution
1. Clone repo
2. Make config change
3. Check in with comments, stage, sync
4. Trigger build, or wait until poll triggers
5. Watch execution

# Future Enhancements
Raspberry Pi Image / Hass.io
Better Verification steps
