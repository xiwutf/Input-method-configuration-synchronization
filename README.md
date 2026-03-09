# 小狼毫输入法配置同步

这是我的小狼毫输入法配置的同步仓库。

## 配置内容

- 基于 [雾凇拼音](https://github.com/iDvel/rime-ice) 配置
- 支持全拼和多种双拼方案
- 包含自定义词库和配置

## 使用方法

1. 安装小狼毫输入法
2. 将此仓库克隆到小狼毫配置目录：
   ```bash
   git clone https://github.com/Lijing327/Input-method-configuration-synchronization.git %APPDATA%\Rime
   ```
3. 运行小狼毫部署工具重新部署

## 同步更新

修改配置后，执行以下命令同步：
```bash
cd %APPDATA%\Rime
git add .
git commit -m "更新配置"
git push
```
