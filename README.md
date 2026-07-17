
## ⚠️ 重要声明
**此项目及工具仅供测试用途。使用风险自负。生产环境请使用官方授权版本。**

## 架构：x86、arm64 
- **主页：** https://mikrotik.ltd/ 
- **演示：** https://demo.mikrotik.ltd/
- **授权： 安装OPTION.NPK后将自动授予最高级别许可证。**
- **源代码：** https://github.com/elseif/MikroTikPatch
- **授权BOT：** https://t.me/ROS_Keygen_Bot
- **Docker：** `docker pull ghcr.io/elseif/chr:latest`

## 架构：arm64, arm, mipsbe, mmips, ppc, smips, x86 
- **主页：** https://routeros.ltd/
- **授权： 需要赞助**，*CHR版本(x86/Arm64)支持在线直接获取授权。*
- **功能：** 支持在线自定义制作品牌包

## 支持的云功能
| 功能 | 命令 |
|------|------|
| 在线升级 | `system/package/update/install` |
| DDNS | `ip/cloud/set ddns-enabled=yes` |
| 云备份 | `/system/backup/cloud/upload-file action=create-and-upload password=any` |

## 启用容器模式（无需物理重启）
1. 安装 `option.npk` 包。
2. 打开终端执行：`system/device-mode/update container=yes`
3. 打开新终端执行：`system/shell cmd="reboot -f"`

### 更多关于RouterOS的信息请查看: https://manual.mikrotik.com/
