# 代理池工具-杨CC

免费的代理池-完全开源,可以提意见,后续会持续更新.


# 24年12月10号(甲辰年 丙子月 戊申日) 更新0.4测试版本
## 更新内容
  
添加1个获取源：https://openproxy.space/list/
  
添加两个参数：-op 和 -O 
  
参数详情： -op 从新的源中获取代理池信息
参数详情： -O  保存信息到output目录svae.txt中
  
如果有人觉得使用工具麻烦，请你直接查看data目录下的yancy_canshu.py文件，谢谢！请不要跟智障一样去我B站评论区瞎评论！
  
![image](https://github.com/user-attachments/assets/a2cf492a-ecf2-44f3-9a41-5ef91f51ffd6)



```
usage: python run.py [-h] [-z] [-i] [-a] [-pr] [-op] [-O]

杨CC-获取代理池ip Version：0.4

options:
  -h, --help            show this help message and exit
  -z, --run-zdaye       使用 zdaye 获取代理池ip(高质量/支持全系统/容易被封ip))
  -i, --run-ihuan       使用 ihuan 获取代理池ip(高质量/仅支持Windows)
  -ip36, --run-ip3366   使用ip3366获取代理持池（中质量/支持全系统）  
  
  -pr, --run-proxylistplus
                        使用 proxylistpus 获取代理池ip（中质量/支持全系统）  
  -a, --run-all         运行所有参数（默认不使用-i参数，如果你是Widnows系统，请手动添加-i参数）
  -op, --run-openproxy  使用 openproxy 源获取socks4代理池（中质量/当前全系统可用）
  -O, --save-output     将获取到的ip池存放在output目录中的svae.txt文件中

```


# 24年12月8号（甲辰年 丙子月 丙午日）下午3：30更新 - 0.3版本发布

## 更新内容：
  
 添加-a参数 可以同时运行全部参数
  
 添加-pr参数 -使用proxylistpus源进行获取
  
 更新-ip36 参数代码逻辑，使其运行更快，信息更明确
  
 优化整体代码逻辑
  
 优化python支持，当前支持python3.12/3.11/3.10,其他python版本暂未测试，预计3.7以上版本均可使用


```
usage: python run.py [-h] [-z] [-i] [-a] [-pr]

杨CC-获取代理池ip Version：0.3

options:
  -h, --help            show this help message and exit
  -z, --run-zdaye       使用 zdaye 获取代理池ip(高质量/支持全系统)
  -i, --run-ihuan       使用 ihuan 获取代理池ip(高质量/仅支持Windows)
  -ip36, --run-ip3366   使用ip3366获取代理持池（中质量/支持全系统）
  -pr, --run-proxylistplus
                        使用 proxylistpus 获取代理池ip（中质量/支持全系统）
  -a, --run-all         运行所有参数（默认不使用-i参数，如果你是Widnows系统，请手动添加-i参数）


```


# 24年12月8号（甲辰年 丙子月 丙午日）上午 更新 - 0.2版本发布
新添加了一个源，足以获取对应代理池ip.
添加版本号。

添加参数 -ip36
```
  -h, --help           show this help message and exit
  -z, --run-zdaye      使用 zdaye 获取代理池ip(高质量/支持全系统)
  -i, --run-ihuan      使用 ihuan 获取代理池ip(高质量/仅支持Windows)
  -ip36, --run-ip3366  使用ip3366获取代理持池（中质量/支持全系统）

```

# 24年12月6号-免费代理池工具发布!
免费的代理池-完全开源,可以提意见,后续会持续更新.

python版本:3.12 其他版本请自测

# 使用教程:

```
git clone https://github.com/Sgyling/yancy-dai-li_chi.git#
cd yancy-dai-li_chi
python3 -m pip install -r requirements.txt
python3 run.py -h 
```





![image](https://github.com/user-attachments/assets/cbb8ee9e-eb96-4bfe-8ebd-0e068b45ef9a)

# QQ交流群:660264846  B站：疯狂的杨CC 

![image](https://github.com/user-attachments/assets/aa6099f8-d09d-4a93-b781-30ce705499cd)
