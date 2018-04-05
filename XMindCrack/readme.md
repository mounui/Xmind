# Xmind激活

​	Xmind不激活也是可以使用的，那么，你可能会问为什么还要激活。这是因为未激活的Xmind少了很多使用的功能。好了，废话不多说了，下面将如果激活Xmind。

- 在官网购买序列号激活

  打开Xmind软件，帮助 > 序列号 （或者自行百度Xmind激活）

- 使用激活补丁 (_仅供参考，禁止用于商业用途，如有需要请通过正常途径购买激活_）

  1. 下载Xmind激活补丁 [XMindCrack.jar](https://github.com/mounui/Xmind/tree/master/XMindCrack) 
  2. 打开 Xmind 取消检查更新选项 (下面两步可以一起设置)

  > -> 编辑 -> 首选项 -> 常规 -> 启动 -> 启动时检查更新和消息：取消勾选 (最后确定)

  ​	取消发送用户数据选项

  > -> 编辑 -> 首选项 -> 常规 -> 启动 ->发送用户数据: 取消勾选 (最后确定)

  ​	最后关闭Xmind

  3. 将 XMindCrack.jar 复制到 Xmind 的安装目录下，默认安装路径为 C:\Program Files (x86)\XMind（如果你是自定义安装的请找到自己的安装目录）；
  4. 在 Xmind 的安装目录下找到 XMind.ini 这个文件（部分人隐藏后缀名了，所以显示的是xmind这个名字，只要是在xmind图标后面的那个就是的）用记事本打开这个文件并在最后添加一行：

  ```ini
  -javaagent:./XMindCrack.jar
  ; 注意此处-javaagent后面的地址应为补丁文件 XMindCrack.jar 的地址，因为我们把该文件放到了Xmind 的安装目录下，Xmind.ini 和 XMindCrack.jar 在同一目录下，因此这里我们可以使用相对路径，如果这两个文件不在同一个目录下，注意填写正确的路径
  ```

  5. 断开网络，或者使用防火墙阻止 XMind 联网，或者在 hosts 文件中添加一行 127.0.0.1`www.xmind.net`（建议采用断网或者增加hosts记录法）。其中 hosts 文件一般在：C:\Windows\System32\drivers\etc 目录下
  6. 再次启动 Xmind，进行软件激活 -> 帮助 -> 序列号 -> 输入任意邮箱地址及以下序列号：

  ```bash
  XAka34A2rVRYJ4XBIU35UZMUEEF64CMMIYZCK2FZZUQNODEKUHGJLFMSLIQMQUCUBXRENLK6NZL37JXP4PZXQFILMQ2RG5R7G4QNDO3PSOEUBOCDRYSSXZGRARV6MGA33TN2AMUBHEL4FXMWYTTJDEINJXUAV4BAYKBDCZQWVF3LWYXSDCXY546U3NBGOI3ZPAP2SO3CSQFNB7VVIY123456789012345
  ```

  7. 所有步骤完成之后，即可重新联网。