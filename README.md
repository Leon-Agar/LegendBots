# Credits to Jimboy's 3100 developer
Free open source agar.io normal.
## Changelog
* Bypass recaptcha v3

## PartyBots
* Note: The bots may not appear so try to reconnect until the bots appear.

## Usage method Repl.it
1. [usage bots with repl.it](https://www.youtube.com/watch?v=xIupgFR7ZTY)

## Download and install Node
1. [Node.js 12.13.0 LTS](https://nodejs.org/)

# ##Local host windows
1. Download and extract the 'zip' file
2. Run Install.bat and wait for the installation and the window to close.
3. Run Start.bat and leave the window open.
4. Go Agario with LegendMod extension. (https://legendmod.ml/) (you need tampermonkey extension installed)
5. Choose the name and number of bots (Do not abuse the server so that people can grow)
6. in the ws it has to be put; ws://localhost:1337 or 8083
7. Click Connect and wait for the "captcha token" to load around 30-60 then run start bots.
8. Have fun :D

##VPS
-------
1. I recommend using a Ubuntu 18.04 LTS from DigitalOcean. You can get one for $5/month and you can use this [link](https://m.do.co/c/fa7a805f6e60) to get $50 on the platform
2. Run `sudo apt install git` command
3. Run `git clone https://github.com/Leon-Agar/LegendBots` command
4. Run `cd LegendBots` command
5. Run `sudo chmod +x install.sh` command
6. Run `sudo ./install.sh` command
7. Run `node server` command and leave the process running
8. Go to Agario and place your VPS IP in the `ws` panel and click on the" Connect "button (the ip of vps must have 8083 at the end. example; `ws://12.264.84.94:8083`
9. On the top right of your browser you will see a shield with a red mark, click there and then click on "Load unsafe scripts"
10. After loading agar.io, click on the "Connect" button again, the status should read "Connected" in green and wait for 'captcha tokens' to load as I said before.
11. Create a party and make sure you are logged into your agar.io account, then click on the "Start Bots" button, if the VPS IP does not have captcha, the button should turn red and say "Stop Bots" if you get an alert that says the IP has captcha, you must change the IP of VPS in some way to one without captcha
12. To stop bots click the "Stop Bots" button and wait 30 seconds for process to close you will see a countdown there
13. To run the bots again just run `node server`, make sure you "Load unsafe scripts", click "Connect" button and then click "Start Bots" button if you did everything right bots should start again
14. Always make sure you wait the 30 seconds for process to close or you are gonna get captcha on the VPS ip.
