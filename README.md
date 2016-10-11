# adb-support-scripts
Shell scripts to aid using adb with multiple devices.

## adbalias
This bash script will alias `adb` to always target a specified device. 

#### Requirements 
Bash, adb (in path)

#### Usage
`source adbalias`

Follow the interactive prompts

#### Example of use

```bash
$ source adbalias 
```
```
This script will alias adb to always use the following device:
1) CLEAR ALIAS
2) ABCDEFGHIJKLM          device usb:1318912X product:nemo model:LG_Watch_Urbane device:nemo
3) WX123456820394         device usb:1245184X product:g3_global_com model:LG_D855 device:g3
4) MQB7N38205914235       offline usb:1327104X
Select the device to use, <Q> to quit: 2
Creating adb alias to LG_Watch_Urbane (ABCDEFGHIJKLM).
To remove the alias, simply run 'unalias adb' or select option (1) in this script.
Done.
```
