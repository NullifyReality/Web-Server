# Web-Server
Some interesting ways I customized and optimised my personal website(s)
# Goals
`Host everything securely in-house`
`low-power, low-cost`
`not exposing home-ip`
`host multiple sites using multiple domains` 
`host my transparrent comunicator platform`
`isp wont let me portforward :( bypass it`



# what i used
raspberry pi model B+ running `Raspberry pi OS (32 bit)` with 64Gb SD card
docker container to run my vpn cause my provider nolonger provides linux downloads for their vpn client they used to :/
Cloudflair tunneling to mannage DNS so when my ip changes it will update on its own
apache webserver to run the page

# Seting up a private vpn with static ip so i dont expose my home ip
this was the easy part
I installed docker engine and then this docker image by [@tmcphee](https://github.com/tmcphee/cyberghostvpn)
# cloudflair tunneling

# 
