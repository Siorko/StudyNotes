# 关于git遇到的问题

## 1.git 在ided 克隆时遇到 github.com port 443: Timed out
- 取消http/https的代理
 ```cmd
git config --global --unset http.proxy
git config --global --unset https.proxy
 ```