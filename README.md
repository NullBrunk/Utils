# Utils - the penetration testing toolbox
**Utils is a toolbox for pentesters written in python3. He allow you to do things like get a tty & stabilize a shell, generate reverse shell payloads  easely, launch python3 server ...**
**Basically, his goal is to make your pentests/ctfs easier.**


- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#how-to-install-it-">Installation</a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#global-help-">The global help</a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#netpy-">the Netpy listenner</a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#revshell-generator-">Reverse shell generator </a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#ip-">Show all local ips </a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#websearch-">Launch the web browser easely</a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#wordlists-">List all your wordlists</a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#serv-">Launch a python3 server</a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#Credits-">Credits</a>

# How to install it ?
- **Install ``netcat`` or ``ncat``**
- **Install ``stty``**
- 
```bash
# Install : 
pip3 install netifaces termcolor pexpect
git clone https://github.com/NullBrunk/Utils/
cd Utils && sudo chmod 755 utils && sudo mv utils /usr/bin

# Launch :
$ utils --help 
```

# How to use it ? 

## Global help :
![DeepinScreenshot_select-area_20220705184408](https://user-images.githubusercontent.com/106782577/177376676-8d3cfe40-c086-4118-a031-070ba8c5a127.png)

## Netpy :
This option allow you to listen for incomming connection, get a TTY, and then fully stabilize the shell.

### Help :
![image](https://user-images.githubusercontent.com/106782577/177377018-2ffd69ae-b4a7-4ad7-af8a-a85a57f428fd.png)

### Example :


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


## Wordlists :

This option list all the wordlists in the /usr/share/wordlists directory.

![image](https://user-images.githubusercontent.com/106782577/176955481-3685079d-49c1-4c1c-8e86-338fe6070421.png)

## Serv :

This option allow you to launch an http server in the directory of your choice.


https://user-images.githubusercontent.com/106782577/177181810-56bf362e-20a3-4007-af1e-becd73544b25.mp4



# Credits

- **https://www.kali.org/tools/wordlists/ inspired me for the "Graphical" interface**   
- **https://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet for the reverse shell generator**     
- **https://github.com/RoqueNight/Reverse-Shell-TTY-Cheat-Sheet for the listenner**





