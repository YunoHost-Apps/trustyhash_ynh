<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 TrustyHash

[![集成程度](https://apps.yunohost.org/badge/integration/trustyhash)](https://ci-apps.yunohost.org/ci/apps/trustyhash/)
![工作状态](https://apps.yunohost.org/badge/state/trustyhash)
![维护状态](https://apps.yunohost.org/badge/maintained/trustyhash)

[![使用 YunoHost 安装 TrustyHash](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=trustyhash)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 TrustyHash。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

TrustyHash is a small [client-side](https://unhosted.org/) web application that
computes SHA-256 hash values on both local files and on remote URLs, with a
strong emphasis on a process that will allow you to trust the results.


**分发版本：** 2016.06.17~ynh2

**演示：** <https://sprin.github.io/TrustyHash/>
## 文档与资源

- 上游应用代码库： <https://github.com/sprin/TrustyHash>
- YunoHost 商店： <https://apps.yunohost.org/app/trustyhash>
- 报告 bug： <https://github.com/YunoHost-Apps/trustyhash_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/trustyhash_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/trustyhash_ynh/tree/testing --debug
或
sudo yunohost app upgrade trustyhash -u https://github.com/YunoHost-Apps/trustyhash_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
