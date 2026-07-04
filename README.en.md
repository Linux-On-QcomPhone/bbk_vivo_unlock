# bbk_vivo_unlock
Unlock the bootloader for bbk_vivo old devices.
### support devices:
| CodeName | DeviceName |
|-----|-----|
| PD1304CL | vivo Y13L |
| PD1304CF | vivo Y613F |
| PD1304CV | vivo Y913 |
| PD1309F | vivo Y21L |
| PD1403L | vivo Y28L |
| PD1403F | vivo Y628 |
| PD1403V | vivo Y928 |
| PD1410L | vivo Y27L |
| PD1410F | vivo Y627 |
| PD1410V | vivo Y927 |
| PD1419L | vivo Y23L |
| PD1419F | vivo Y623 |
| PD1419V | vivo Y923 |
| PD1505W | vivo Y31 |
| PD1505F | vivo Y31A |
| PD1510 | vivo Y51A |
| PD1510F | vivo Y51 |


## Usage Instructions

1. Clone this repository.
2. Choose the appropriate version for your system: Windows or Linux.
3. Put your phone into fastboot mode, then use the unlock command to unlock it.

### How to Enter Fastboot Mode

1. With the phone powered off, press and hold the Power button and Volume Down button simultaneously.
2. While the phone is booted into Android, use the following command:
```
adb reboot bootloader
```

### Unlock bootloader:
```
fastboot bbk unlock_vivo
```
## File Sources
- [Windows Version](https://github.com/shmilee/vivo-Y13L/blob/master/tools%2FAdbAdapter.rar)
- [Linux Version](https://drive.google.com/file/d/1SA-6FcUHnwZRzKky720Wx5zIwoq0vE-E/view)
- [Source Code](https://github.com/naveensingh/vivo_fastboot)


