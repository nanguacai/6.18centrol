#注意事项

#1 安装依赖包在requiement.txt

#2 修改你的账户名和密码
username= "改为你的京东帐号"
password ="修改为你的京东帐号密码"

#3 修改你的所抢的时间段：是1点30分的，提前两秒点击时间，留两秒页面刷新（根据你的页面刷新速度设置一般在57-59秒
不能设置为带float，只能是integer）
 end_time = datetime.datetime(2018,6,8,13,29,58) # 2018/06/03/ 13:29:58

#4 注意下载的chrmoedriver的版本和你的chrome浏览器的版本要相匹配，百度就可以找到
