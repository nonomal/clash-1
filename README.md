# clash for linux 一键使用

1. 切换到.config文件夹
`cd ~/.config`
2. 下载clash文件
`git conle https://github.com/herobrine19/clash.git`
3. 根据订阅链接(假设为`https://xxx`)下载yaml文件
`wget https://xxx&client=clash -O config.yaml`
4. 运行clash
`./clash`
5. 设置系统代理
`export http_proxy=http://127.0.0.1:7890 https_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890`
6. 测试是否连上
`curl -I www.google.com`
