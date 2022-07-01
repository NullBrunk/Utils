# Utils
**Utils is a simple script written in python3, his goal is to make the life of the pentester easier with some useful commands.**

- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#how-to-install-it-">Installation</a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#global-help-">The global help</a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#revshell-generator-">reverse shell generator </a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#ip-">Show all local ips </a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#websearch-">Launch the web browser easely</a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#wordlists-">List all your wordlists</a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#serv-">Launch a python3 server</a>
- <a href="https://github.com/NullBrunk/Utils/blob/main/README.md#Credits-">Credits</a>

# How to install it ?

```bash
# Install : 
pip3 install netifaces termcolor
git clone https://github.com/NullBrunk/Utils/
cd Utils && sudo chmod 755 utils && sudo mv utils /usr/bin

# Launch :
$ utils --help 
```

# How to use it ? 

## Global help :

![image](https://user-images.githubusercontent.com/106782577/176953467-032e1ff0-b3fe-4c35-82bb-8f2b5885f185.png)

## RevShell generator :

This option allow you to generate a payload for a reverse shell easely.

### Help :

![image](https://user-images.githubusercontent.com/106782577/176953560-34d9e058-5e46-4bd5-a624-b023215608ee.png)

### Example :

![image](https://user-images.githubusercontent.com/106782577/176953904-85a027c1-3171-4890-92ce-021fffc0dd47.png)


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

https://user-images.githubusercontent.com/106782577/176956133-41096c61-64f7-42a5-944f-10b7f5bd7bce.mp4


# Credits

-**https://www.kali.org/tools/wordlists/ inspired me for the "Graphical" interface**   
-**https://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet for the reverse shell generator**     






