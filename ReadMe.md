### Connecting to Linux VM from Windows
* [Download putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)
* Using puttygen convert .PEM file to .ppk
* Use Auth to set the ppk file
* Enter Host

### Some useful commands
* get version **cat /etc/os-release**
* file hierarchi **man hier**
* physical memory **ls -lh /proc/kcore**
* log messages **/var/log/messages**
* To find out whether a command given to the shell will be executed as an external command or as a builtin command, use the __type__ command
    * type cd
    * type cat
* to view alias
    * **alias**
* **set -x** and **set +x** shell expansion
* **&** at the command will run in background.
    * sleep 20 &
* **$?** is exit code of previous command
* **#** is comment

