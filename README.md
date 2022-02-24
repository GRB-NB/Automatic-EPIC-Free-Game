# Automatic-EPIC-Free-Game
自动领取EPIC免费游戏

云函数部署
打包epicgames_claimer.py和requirements.txt
文件为zip，上传到云函数。执行方式填`epicgames_claimer.main_handler`

## 环境变量
```
邮箱
EMAIL
密码
PASSWORD
微信应用通知
PUSH_WECHAT_QYWX_AM
是否领取通知（false和true）
PUSH_WHEN_OWNED_ALL
```
## 在控制台输入以下命令（一行一行输入）

```
cd src
pip3 install -r requirements.txt -t .
mv bin/pyppeteer-install .
./pyppeteer-install
cp -r /root/.local/share/pyppeteer/local-chromium/*/chrome-linux .pip3 install -r requirements.txt -t .
```
