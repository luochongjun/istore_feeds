## soruce

ddnsgo https://github.com/sirpdboy/luci-app-ddns-go
alist https://github.com/sbwml/luci-app-alist
pdnsd-alt https://github.com/coolsnowwolf/packages/tree/master/net/pdnsd-alt 
cups https://github.com/Gr4ffy/lede-cups.git

## host tool
sudo apt install libfuse-dev
ln -s /snap/bin/upx staging_dir/host/bin/upx

rm -rf feeds/packages/lang/golang
svn export https://github.com/sbwml/packages_lang_golang/trunk feeds/packages/lang/golang

go get -u github.com/go-bindata/go-bindata/...
export PATH=$PATH:/home/glinet/go/bin
