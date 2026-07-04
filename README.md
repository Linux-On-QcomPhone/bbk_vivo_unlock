# bbk_vivo_unlock
解锁vivo,旧设备的bootloader锁 |[View the English instructions](README.en.md)
---
## 支持设备：
| 代号 | 机型 |
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

## 使用方法
1. 克隆本仓库
2. 根据系统选择Windows版本和linux版本
3. 手机进入fastboot,使用解锁命令解锁

### 进入fastboot方法
1. 在关机状态下，按电源键和音量下键
2. 在Android开机状态下，使用:
```
adb reboot bootloader
```

### 解锁命令
```
fastboot bbk unlock_vivo
```
## 文件来源
- [Windows版本](https://github.com/shmilee/vivo-Y13L/blob/master/tools%2FAdbAdapter.rar)
- [Linux版本](https://drive.google.com/file/d/1SA-6FcUHnwZRzKky720Wx5zIwoq0vE-E/view)
- [源码](https://github.com/naveensingh/vivo_fastboot)