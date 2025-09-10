# 电池

## 电池健康度

Windows 系统下电池健康度可以通过以下方式查看。

右键 Windows 开始菜单按钮 - 终端（Win 11） / Windows Powershell（Win 10）/ 命令提示符（Win 7）

（可选）让生成的电池健康度报告变得好找，输入：

```shell
cd C:\
```

之后输入：

```shell
powercfg /batteryreport
```

系统会在当前工作目录（若输入了可选命令则为C盘根目录）下生成一个名为`battery-report.html`的文件。双击打开，如果需要选择打开方式则选择浏览器打开，即可查看电池使用情况。

在 `Installed batteries` 中的 `DESIGN CAPACITY` 为电池的设计容量，`FULL CHARGE CAPACITY` 为当前的电池满电容量。二者相除即为“电池健康度”。
 
## 更换电池

（待补充）