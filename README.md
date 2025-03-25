# 🚀 SubsCheck-Win-GUI
首先声明，这款软件并非我原创开发。Subs-Check是由 [bestruirui](https://github.com/bestruirui/BestSub) 原创、由 [beck-8](https://github.com/beck-8/subs-check) 进行二次开发，而我所编写的 GUI 仅是在这两位开发者的原始版本基础上进行的 **二次开发**。

- **Telegram交流群：[@CMLiussss](https://t.me/CMLiussss)**

# ⚠️ 免责声明
本项目仅供学习、研究与安全测试使用，请勿用于任何非法活动。使用前请确保您已了解并遵守所在地的法律法规。

### 📋 使用条款

- **教育与研究用途**：本软件仅可用于网络技术和编程领域的学习、研究和安全测试。
- **禁止非法使用**：严禁将 **SubsCheck-Win-GUI** 用于任何非法活动或违反使用者所在地区法律法规的行为。
- **使用时限**：基于学习和研究目的，建议用户在完成研究或学习后，或在安装后的**24小时内，删除本软件及所有相关文件。**
- **免责声明**：**SubsCheck-Win-GUI** 的创建者和贡献者不对因使用或滥用本软件而导致的任何损害或法律问题负责。
- **用户责任**：**用户对使用本软件的方式以及由此产生的任何后果完全负责。**
- **无技术支持**：本软件的创建者不提供任何技术支持或使用协助。
- **知情同意**：使用 **SubsCheck-Win-GUI** 即表示您已阅读并理解本免责声明，并同意受其条款的约束。

> [!WARNING]
> **请记住**：本软件的主要目的是促进学习、研究和安全测试。作者不支持或认可任何其他用途。使用者应当在合法和负责任的前提下使用本工具。

---

![GUI](./gui.png)

## 💾 测速结果 保存方法

- **本地**：将结果保存到本地,默认保存到可执行文件目录下的 output 文件夹
- **r2**：将结果保存到 cloudflare r2 存储桶 [配置方法](https://github.com/beck-8/subs-check/blob/master/doc/r2.md)
- **gist**：将结果保存到 github gist [配置方法](https://github.com/beck-8/subs-check/blob/master/doc/gist.md)
- **webdav**：将结果保存到 webdav 服务器 [配置方法](https://github.com/beck-8/subs-check/blob/master/doc/webdav.md)

## 📁 GUI 文件结构
```shell
subs-check.win.gui.exe      # GUI本体
subs-check.exe              # subs-check x86_32位 内核本体  
subs-check_Windows_i386.zip # subs-check x86_32位 内核压缩包  
config
 └─ config.yaml             # subs-check 配置文件  
output
 ├─ all.yaml                # yaml格式 测试结果
 ├─ node.exe
 ├─ root.json
 ├─ sub-store.bundle.js
 ├─ sub-store.json
 └─ sub-store.log
Newtonsoft.Json.dll         # 验证版本信息组件
Newtonsoft.Json.xml         # 验证版本信息组件
YamlDotNet.dll              # yaml读写组件
YamlDotNet.xml              # yaml读写组件
```

## Star 星星走起
[![Stargazers over time](https://starchart.cc/cmliu/SubsCheck-Win-GUI.svg?variant=adaptive)](https://starchart.cc/cmliu/SubsCheck-Win-GUI)

# 🙏 致谢
[beck-8](https://github.com/beck-8/subs-check)、[bestruirui](https://github.com/bestruirui/BestSub)、[Sub-Store](https://github.com/sub-store-org/Sub-Store)、GPT
