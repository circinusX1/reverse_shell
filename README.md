# WEB BASED REVERSE SSH

## Enable reverse secured ssh to your linux


```bash

# some dependencies if not already on the device
# sudo apt-get install ssh
# sudo apt install (--reinstall) libssh2-1-dev
# sudo apt install libcurl4-openssl-dev
[[ ! -d ${HOME}/.ssh/ ]] && ssh-keygen
# then
git clone https://github.com/circinusX1/rssh_client
cd rssh_client
arch=$(uname -m)
oss=$(uname)
tar xfv ./meiot-$oss-$arch.tar
sudo ./install.sh
# complete the steps. Choose a strong web password
cat  /etc/.meiot_rev_cred

```
   * Use the above credentials and goto 'https://mylinuz.com/'
   * Click the red terminal in the to right corner.
   * Continue reading on https://github.com/circinusX1/reverse_shell/wiki
   


