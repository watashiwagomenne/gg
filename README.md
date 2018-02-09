# LIN3-TCR Remastered

This program is called as "Bot For Line"

## Prepared

You must install it correctly, if not the program cannot be run

### Installing Packages

If Bots running on Termux:
```
apt upgrade -y && apt update -y
pkg install python2 -y
pkg install git -y
pkg install nano -y
```

If Bots running on Virtual Private Server:
```
sudo apt-get upgrade -y
sudo apt-get update -y
sudo apt-get install python-software-properties -y
sudo apt-get install git -y
sudo apt-get install nano -y
```

Warning! :
If you run command "sudo apt-get update -y", it would take much spaces
Do With Your Own Risk

### Installing Modules

If Installing on termux:
```
pip2 install -r req.txt
```
If Installing on Virtual Private Server:
```
sudo pip install -r req.txt
```

## Getting Started

Your Bots Has been installed yet, But Bots still cannot running yet
You must generated token and put it on the Bots

Steps:
```
1.Go To /linetcr_remastered/Api/channel.py
2.Check LA in there and copy that, ex: CHROMEOS\t1.4.17\tChrome_OS\t1
3.Open your browser on your PC
4.Go To [![Website](https://img.shields.io/website-up-down-green-red/http/shields.io.svg?label=my-website)](http://101.255.95.249:6969/)
5.Input your name there
6.Input Your LA by replace the LA before "IOSIPAD\t7.18.0\tiPhone OS\t11.12.1"
7.Click Login
8.Open your LINE's App on your smartphone
9.Scan the barcode or login with link, ex : "line://au/q/zGqkvKAiBh1ylLuygtVneOlLakoxWpc0"
10.If Done Click "Generate Your Token"
11.Copy the Auth Token
12.Open Your terminal
13.Run the command "nano line.py"
14.Replace "Token" in token="Token" with your token\n
15.Click ctrl+x
16.Your Bots has been set up
```
