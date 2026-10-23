# 达人绑定佣金 Skill

团队复用的去品牌安装包。保留抖音达人佣金绑定、主链接、双佣金、报团、明确要求的发票豁免和截图／产品链接交付流程，按平台和定制规则分层维护。

## 下载与安装

1. 登录已获邀请的 GitHub 账号，下载 [v0.1.0 安装包](creator-commission-link-v0.1.0.zip?raw=true)。如先进入文件页，点击 **Download raw file** 下载。
2. 完整解压安装包，进入包含 `install.ps1` 和 `creator-commission-link` 的目录。
3. Windows 在该目录运行 `powershell.exe -NoProfile -File .\install.ps1`；已有同名技能时脚本会停止，避免覆盖。也可手动把整个 `creator-commission-link` 文件夹复制到用户主目录的 `.agents/skills/`。
4. 新开 Codex 对话，输入下面的初始化请求。技能未出现时重启 Codex。

```text
使用 $creator-commission-link 初始化。
请让我选择本机业务工作目录和商品来源表，核对店铺规则；本次先不操作真实后台。
```

如果使用 **Code → Download ZIP** 下载整个仓库，解压后再解压里面的技能安装包，随后按上述步骤安装。完整操作说明和分层技能文档均在安装包内。Codex 官方安装位置说明见 [Build skills](https://learn.chatgpt.com/docs/build-skills)。

## 使用边界

这是供 Codex 执行的操作规范。使用者需配置自己的商品表、目标店铺规则、后台登录和浏览器控制工具。安装验证已通过；不同店铺和页面版本仍需实际核对。包内标明了既有流程验证范围，未将未验收的新策略或新商品创建标成已完成能力。

包内不包含真实品牌、店铺商品表、达人名单、业务ID、后台截图、凭据或本机运行资料。原始业务资料应留在使用者自己的工作目录；更新共享包前也须去品牌化并检查敏感信息。

仓库为个人私有仓库。所有者邀请的同事接受邀请后可下载和写入，仓库权限不代表店铺后台权限。

## 版本校验

v0.1.0 安装包 SHA-256：

```text
8d5512e00b10fee4434fd482fa93599741ae6d35b1ca304da681e715e7362635
```
