# Parallels Desktop 16 无法联网和 USB 连接问题

打开路径 `/Library/Preferences/Parallels`

### 网络问题
- 打开 network.desktop.xml 文件，找到 `<UseKextless>1</UseKextless>` 或 `<UseKextless>-1</UseKextless>`, 修改为 `<UseKextless>0</UseKextless>`

### USB 连接问题
- 打开 dispatcher.desktop.xml 文件，找到 `<Usb>0</Usb>`，修改为 `<Usb>1</Usb>`
