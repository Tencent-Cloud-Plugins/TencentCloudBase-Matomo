<p align="center">
  <img height="100px" src="./logo.png" />
</p>

# [Matomo](https://github.com/matomo-org/matomo)

Matomo是一款开源免费的网站分析平台，可用于实时跟踪网站访问并进行统计分析。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-Matomo&branch=master)
### 配置
- `DB_IP`: 数据库地址
- `DB_PORT`: 数据库端口
- `MYSQL_USERNAME`: 数据库用户名
- `MYSQL_PASSWORD`: 数据库密码
- `ADMIN_USER`: 后台管理系统管理员账号
- `ADMIN_PASS`: 后台管理系统管理员密码

### 依赖

- CynosDB：使用 CynosDB 数据库存储数据

## 注意事项

