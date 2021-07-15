## Quantumult X懒人配置

### 配置说明：

   本配置由神机规则修改而来；

   同时参考了[@Orz-3](https://github.com/Orz-3/QuantumultX)，[@少年大佬](https://github.com/Oreomeow/QuanX)，[@Tartarus2014](https://github.com/Tartarus2014/QuantumultX-Script)以及[@w37fhy](https://github.com/w37fhy/QuantumultX)（排名不分先后）的懒人配置文件再做修改。

   并且严格遵守了[@Quantumult X不完全教程](https://www.notion.so/Quantumult-X-1d32ddc6e61c4892ad2ec5ea47f00917) 的教程指引。

修改了默认策略组，增加了正则筛选策略组，并集成了Nobyda的去广告脚本和重写，添加了最新可用的淘宝与京东比价，可按需求订阅<br>

### 使用方法：

1. (移动端先点View code打开库里文件列表)点击库中的quantumult_diy.conf文件，点击raw获取真实地址，复制地址备用<br>
2. Quan X主界面，点击右下角`三棱形状`，然后弹出界面下拉至 配置文件-下载，点击下载，将上一步复制的地址粘贴到弹出窗口，然后点确定<br>
3. Quan X主界面，点击右下角风车，然后弹出界面下拉至 Mitm ，点击生成证书<br>
4. 然后回到Quan X，继续点击配置证书，根据提示安装证书<br>
5. 安装成功后启用证书，并到系统的 设置-通用-关于本机 点击信任证书<br>
6. 打开重写和Mitm<br>
7. 添加节点/订阅，并左滑添加订阅标签（重要，不添加标签是无法筛选的）<br>
8. 开始使用<br>

### 注意事项与说明：

1. 如果你购买Quantumult X还不足30天，无法一键更新，在启用Get-Cookie时，请搜索并单独缓存你需要的获取cookie脚本。
2. 默认已解锁Tiktok日区，如需改区，本地在[rewrite_local]下方添加(?<=_region=)CN(?=&) url 307 JP  
将JP更改成你想改的区域。<br>
3. Task请在Task文件夹内按需求添加订阅，使用需额外在重写中启用JS-GetCookie，并按脚本中说明获取cookie方可用。<br>
4. 只是搬运和同步更新大佬脚本。<br>
5. 不负责维护脚本。<br>
6. 只测试自用脚本，其他大部分脚本未测试可用性。<br>
7. 有添加备注版本，详见[quantumult_remark.conf](https://github.com/borisKP/quanx/blob/master/quantumult_remark.conf)（此带备注版同步更新）

### 关于：

- 比价开启后，京东可以直接显示，淘宝显示在商品目录的"保障"栏，需要点击查看。
- 任务（task）本人只使用了大佬配置的京东签到与什么值得买签到。需要其他请自行Google解决。
- 本人不使用网易云音乐，但在[quantumult_remark.conf](https://github.com/borisKP/quanx/blob/master/quantumult_remark.conf)中已经写好相关的内容，删除相应的备注即可启动。
- 测试环境基于商店版**Quantumult X v1.0.23-build572**
- 更直觉的教程建议参考[w37fhy大佬的视频教程](https://www.youtube.com/channel/UCXdlywuMV_a8jEZ4wV6669g/videos)

### 免责声明：

* BorisKP 发布的此项目中涉及的任何解锁和解密分析脚本仅用于资源共享和学习研究，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断.

* 间接使用脚本的任何用户，包括但不限于建立VPS或在某些行为违反国家/地区法律或相关法规的情况下进行传播, BorisKP 对于由此引起的任何隐私泄漏或其他后果概不负责.

* 请勿将此项目的任何内容用于商业或非法目的，否则后果自负.

* 如果任何单位或个人认为该项目的脚本可能涉嫌侵犯其权利，则应及时通知并提供身份证明，所有权证明，我们将在收到认证文件后删除相关脚本.

* BorisKP 对任何脚本问题概不负责，包括但不限于由任何脚本错误导致的任何损失或损害.

* 您必须在下载后的24小时内从计算机或手机中完全删除以上内容.

* 任何以任何方式查看此项目的人或直接或间接使用该项目的任何脚本的使用者都应仔细阅读此声明。BorisKP 保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关脚本或此项目的规则，则视为您已接受此免责声明.
