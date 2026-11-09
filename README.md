# Dao Browser — Windows 构建产物

非官方 Windows 构建，基于 [msgbyte/dao-browser](https://github.com/msgbyte/dao-browser) 源码（Chromium 155.0.8059.86）。

## 下载

- [v1.0.134-windows-x64-debug](https://github.com/ac1269277935/chromium-release/releases/tag/v1.0.134-windows-x64-debug)

## 校验

```
fcba632a838226e9d020b026ff44461f379370e590fd70573cda79b494bedc73  dao-browser-1.0.134-windows-x64-debug.exe
```

## 说明

- debug / component build，未签名，Windows SmartScreen 可能提示
- 安装包由 NSIS 封装 Chromium 原生 mini_installer，支持自定义安装目录与卸载
- 默认安装到 `%LOCALAPPDATA%\Dao`（已有安装时沿用原路径）

## 许可证

源码遵循 BSD 3-Clause License，版权归 Dao Browser Authors；本仓库仅分发构建产物。
