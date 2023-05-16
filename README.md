# Ptero-VM Ubuntu 22.04 fork release [TukangM/Ptero-VM-JAR/releases/tag/lastest](https://github.com/TukangM/Ptero-VM-JAR/releases/tag/lastest)

Root-Instance inside of pterodactyl's docker container with Proot.

## Issue
 - i dont know how compile java server.jar so idk how
 - server.js not working for some reason due newer node.js. so try lower version like 10.x 12.x 
 - if you get this error. idk how to fix. if you trying install xfce4. the error will be apt not usable
![image](https://github.com/TukangM/Ptero-vm/assets/91467886/b293d4bf-2156-4540-8c0f-2ed24d71b081)


## ✨ Features

- Root well, inside the docker container.
- idk whatelse

## 💁‍♀️ How to use

- first make a server (js/py/java server)
- then download the [`server.py`](https://raw.githubusercontent.com/TukangM/Ptero-vm/main/server.py) (`pip install aiohttp`), `server.jar`not available due not having knowledge compile java or [`server.js`](https://raw.githubusercontent.com/afnan007a/Ptero-vm/main/server.js) (`npm i shelljs`)file  
- then upload the files to your server via file manager or sftp
- then go to startup section of the server and name it `server.py` (if u made python server and downloaded the server.py file) or `server.js` (if u made js server and downloaded the server.js file)  `server.jar` (if u made java server and downloaded the server.jar file)
- now start the server and it will install the files for you and run PteroVM
- you're done

## ✨ Preinstalled Packages

- Htop

- Neofetch

- Nano

- Gotty

- Ngrok


## ✨ Addons

 __GoTTY:__
 
 _GoTTY is a simple GoLang based command line tool that enables you to share your terminal(TTY) as a web application. It turns command line tools into web applications._

- to run gotty just type `gotty -p <port> -w bash`in your terminal.

- now it will be up and running, and it will show the ip and port of it in the console. copy paste it in ur browser and there you have remote terminal with gotty

__Ngrok:__
 
 _Ngrok is a tunneling software to portforward your server  to custom domains other than the numeric ip_

- to run ngrok just type `ngrok http <port>` or `ngrok tcp <port>` ie: `ngrok tcp 22`  in your terminal and continue the steps. if you have any doubts [[Read this docs!]](https://ngrok.com/docs)


## ✨ Credits

- Triassic - Made PteroVM Jar

- Chirag - Rewrote PteroVM

- Io.Netty - Original Idea of PteroVM

- Me - For making PteroVM lol!

## ✨ Note

**Please use a host which have atleast 3GB disk space or it will messup the installation.**

## Disclaimer

This script is made for educational purposes (obviously lol, not like you're gonna abuse it)  
We are NOT responsible for any consequences,  
As stated in the LICENSE:
```
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
