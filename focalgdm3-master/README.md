
# focalgdm3

_**This script assumes that the Installation of Ubuntu 20.xx is a fresh install. If you tried to change the GDM background with someother scripts, you first need to reset those changes. Other scripts may have the option --reset.**_

_**Recommended: Please have a look on the 'TrailRun' Branch for single line commands like below**_
````
sudo ./focalgdm3 /absolute/path/to/Image
sudo ./focalgdm3 \#aAbBcC
````

_**Change the login screen background for Ubuntu 20.04 only.**_

this script is to change the login screen background of Ubuntu 20.04 only.

you can download the `focalgdm3` file via command line

    wget -qO - https://github.com/PRATAP-KUMAR/focalgdm3/archive/master.tar.gz | tar zx --strip-components=1 focalgdm3-master/focalgdm3

Once you downloaded the script `focalgdm3`. cd to the downloaded script file.

run the below command with root priviliges and follow the prompts.
`./focalgdm3 --set`

to reset everything that the script made
run the below command with root priviliges
`./focalgdm3 --reset`

![setting of login screen background with Image](https://i.stack.imgur.com/OeuO5.gif)

![result of Image](https://i.stack.imgur.com/ssYjj.png)

![result of Image with OSK](https://i.stack.imgur.com/xcpwT.png)

![result of color](https://i.stack.imgur.com/KmliD.png)

![result of color with OSK](https://i.stack.imgur.com/TFWP5.png)
