piratemagnetlink.py
===================

只支持 Unix 环境。先 pip install pyquery 安装依赖。然后：

1. 打开豆瓣电影的我看列表，点列表右上角的紧凑排列图标，然后看一下总页数
2. 编辑 douban.py，修改用户名和总页数
3. 运行 douban.py，把输出放到 favo.txt 里
4. 运行 piratemagnetlink.py，生成文件名、下载地址、体积列表
5. 运行 outputmagnet.py，生成纯下载地址列表
