# EUserv Renewal
使用 Github Action 自动续期 EUserv 免费 IPv6 VPS

## 说明

自动获取账号内所有的VPS项目，并检测是否需要续期，需要续期会自动续期。

## 使用说明

添加环境变量`USERNAME`和`PASSWORD`。支持同时添加多个帐户，数据之间用半角逗号 `,` 隔开即可，帐户名和帐户密码需一一对应。

```
USERNAME: 你的EUserv账户邮箱或Customer ID,第二个账户
PASSWORD: 第一个账户密码,第二个账户密码
```

