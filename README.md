只能下载自己网盘目录下的文件，不限速，支持https，支持分段下载，支持断点重连
(网址前面加d.生成的是外链,8小时有效)
pcs.baidu.com/rest/2.0/pcs/file?method=download&app_id=①&path=②



非外链,不能使用迅雷下载等第三方软件下载，除非软件能在下载时能传递浏览器cookie才能使用，idm可以。

直链解析(8小时有效期)

pcs.baidu.com/rest/2.0/pcs/file?method=locatedownload&path=②&app_id=①
以流媒体的方式打开视频文件(必须是有效的视频文件，有效期8小时)
d.pcs.baidu.com/rest/2.0/pcs/file?method=streaming&app_id=③&path=②

转码为流畅(不保证有效)d.pcs.baidu.com/rest/2.0/pcs/file?method=streaming&app_id=③&type=M3U8_AUTO_480&path=②

可能需要修改ua(比如改成0)

①：266719是es的id 

250528是百度云的id

778750是百度云tv的id

②：文件的路径

③：必须使用百度的ID

http://localhost:59777/pcs/百度ID@pcs/files/ 

在手机上使用时，可以在打开es后使用这个端口试试
自定义百度网盘分享密码 (Javascript) https://www.giuem.com/baidu-pan-customize-share-password-by-javascript/

附上自动补档黑科技
http://github.com/NijiharaTsubasa/BaiduPanAutoReshare
使用方法解释
http://www.ssgo.org/threads/%E6%88%91%E6%B5%8B%E8%AF%95%E4%BA%86%E4%B8%80%E4%B8%8B%E3%80%90%E5%BA%A6%E5%A8%98%E7%9B%98%E5%88%86%E4%BA%AB%E5%AE%88%E6%8A%A4%E7%A8%8B%E5%BA%8F%E3%80%91.1473/
