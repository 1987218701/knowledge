# 各种软件adb授权代码

## shizuku

```cmd
# adb激活shizuku
adb shell sh /storage/emulated/0/Android/data/moe.shizuku.privileged.api/start.sh
```
## tasker

```cmd
#dumpsys命令权限
adb shell pm grant net.dinglisch.android.taskerm android.permission.DUMP

#dumpsys usagestats 命令权限
adb shell pm grant net.dinglisch.android.taskerm android.permission.PACKAGE_USAGE_STATS

#音量键监听权限
adb shell pm grant net.dinglisch.android.taskerm android.permission.SET_VOLUME_KEY_LONG_PRESS_LISTENER

#LogCat Entry需要的读取日志权限
adb shell pm grant net.dinglisch.android.taskerm android.permission.READ_LOGS

#GPS开关等高级设置权限
adb shell pm grant net.dinglisch.android.taskerm android.permission.WRITE_SECURE_SETTINGS
```

