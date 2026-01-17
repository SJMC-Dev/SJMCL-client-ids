# SJMCL Client IDs

本仓库用于存储各合作高校皮肤站为 [SJMCL](https://github.com/UNIkeEN/SJMCL)（及衍生发行版本）分配的、用于通过 OAuth 登录添加角色的 Client ID，将在每次发版时同步到 SJMCL 主仓库。

若要添加、删除或更改，请遵循既有格式修改 [ids.txt](./ids.txt) 并提起 PR；请按照皮肤站地址字母序排序。

若不知道如何分配 Client ID，请首先确保皮肤站的 Union 定制版 Yggdrasil 插件已升级至 6.1.0-0.3.0 及以上版本（升级方法可参考[插件使用方法](https://github.com/MUAlliance/yggdrasil-connect/blob/main/README.md#%E6%8F%92%E4%BB%B6%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95)），并且已正确部署 Janus（部署方法可参考[部署指南](https://github.com/bs-community/janus/wiki/%E9%83%A8%E7%BD%B2%E6%8C%87%E5%8D%97)），随后请前往皮肤站“用户中心”-“高级功能”-“OAuth2 应用”创建新的 OAuth2 应用，应用名请填写 `SJMC Launcher`，回调 URL 请参考[为应用启用公共客户端支持](https://github.com/bs-community/janus/wiki/%E4%B8%BA%E5%BA%94%E7%94%A8%E5%90%AF%E7%94%A8%E5%85%AC%E5%85%B1%E5%AE%A2%E6%88%B7%E7%AB%AF%E6%94%AF%E6%8C%81)正确填写，创建完成后即可得到 Client ID。