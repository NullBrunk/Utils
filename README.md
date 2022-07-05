# Utils
Utils is a toolbox for pentesters written in python3. He allow you to do things like shell stabilization, easy reverse shell generation, launching python3 server and much more.     
Basically, his goal is to make your **pentests/ctfs easier**.


- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#how-to-install-it-">Installation</a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#global-help-">The global help</a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#presentation-of-a-few-options-">Presentation of some options</a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#netpy-">the Netpy listenner</a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#revshell-generator-">Reverse shell generator </a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#Credits-">Credit</a>

# How to install it ?

**With your package manager, you will need to install :**
- ``netcat`` **or** ``ncat``
- ``stty``
 
**Then you can git clone :**
```bash
# Install : 
pip3 install netifaces termcolor pexpect
git clone https://github.com/NullBrunk/Utils/
cd Utils && sudo chmod 755 utils && sudo mv utils /usr/bin

# Launch :
$ utils --help 
```

# Global help :
![DeepinScreenshot_select-area_20220705184408](https://user-images.githubusercontent.com/106782577/177376676-8d3cfe40-c086-4118-a031-070ba8c5a127.png)


# Presentation of a few options : 

## Netpy :
This option allow you to listen for incomming connection, get a TTY, and then fully stabilize the shell.

https://user-images.githubusercontent.com/106782577/177378816-17e83dd9-d055-4784-9b31-6a716522bdc1.mp4


## RevShell generator :

This option allow you to generate a payload for a reverse shell easely.

### Help :

![image](https://user-images.githubusercontent.com/106782577/176953560-34d9e058-5e46-4bd5-a624-b023215608ee.png)

### Example :

![image](https://user-images.githubusercontent.com/106782577/177144664-85fd12a1-5a76-4430-9ad6-666b7499c13c.png)

## Ip :

This option allow you to list the ip of all your interfaces.

![image](https://user-images.githubusercontent.com/106782577/176953789-80c2ac59-a59c-4639-a70b-3b085c49c3df.png)

## WebSearch :

This option allow you to launch a google/duckduckgo research in a single command, from your terminal.

https://user-images.githubusercontent.com/106782577/176956311-4786bf03-4f27-41e5-8992-1b7e700ea1eb.mp4



# Credits

- **https://www.kali.org/tools/wordlists/ inspired me for the "Graphical" interface**   
- **https://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet for the reverse shell generator**     
- **https://github.com/RoqueNight/Reverse-Shell-TTY-Cheat-Sheet for the netpy listenner**





