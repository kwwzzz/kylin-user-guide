# 麒麟控制面板
## 概述
控制面板提供了一个友好的图形用户界面，用于对操作系统常用配置项进行管理。

控制面板将常用配置归结为两个分类，系统配置、硬件配置。

系统配置主要包含了桌面环境以及系统层面的配置项；硬件配置主要包含了计算机硬件及其相关的配置项目。

![图 1 控制面板主界面-big](image/1.png)

## 系统配置
系统配置设置提供了显示器、默认应用、电源、开机启动四个模块。

### 显示器
显示器可以配置显示相关的设置。

![图 2 显示器设置-big](image/2.png)

#### 显示器设置
显示器设置可以对当前显示器进行选择，调节屏幕分辨率、方向、屏幕刷新率等。

上方彩色矩形代表当前屏幕，中间显示了显示器名称及接口名。

显示器右侧的下拉列表包含了当前所有的显示器，并且下拉框显示的显示器为当前活动显示器。若需要将选中的显示器设为主屏幕，需在多显示器情况下，如果当前显示器不是主屏幕，则点击“设为主屏”后当前显示器被设置为主屏幕。并且同一时间有且仅有一个主屏幕。

分辨率、刷新率等所有配置的修改都是针对当前活动显示器：

**分辨率：**右侧的下拉列表包含了系统及显示器支持的分辨率列表，可以通过下拉列表切换当前活动显示器的分辨率，选中即更改真实生效。

**方向：**右侧下拉列表包含不旋转、90°顺时针、上下颠倒、90°逆时针4个选项，选中即更改真实生效。

**刷新率：**右侧下拉列表包含当前显示器在当前分辨率下支持的刷新率列表自动以及60Hz，选中即更改真实生效。

所有显示器显示主屏幕图像：该选项需仅当存在多个显示器，打开其开关按钮即更改真实生效。

<br>

#### 夜间模式
打开夜间模式，用户可对时间进行修改，并设置显示器开启和关闭时间，对显示器的色温进行调节。

![图 3 夜间模式-big](image/3.png)

### 默认应用
默认应用提供了系统默认应用的配置项，可以修改浏览器、电子邮件、图像查看器、音频播放器、视频播放器、文本编辑器六种类型的默认打开应用。

![图 4 默认应用-big](image/4.png)

### 电源
电源可对电源管理器进行设置：提供平衡模式、节能模式、自定义模式给用户进行选择。

用户自定义为电源供给或电池供给，并可对屏幕保护进行设置：30分钟电脑进入休眠状态、30分钟后系统将显示器关闭。

![图 5 系统电源设置-big](image/5.png)

### 开机启动
开机启动提供对开机启动软件的配置管理功能。

![图 6 开机启动](image/6.png)

列表中显示了当前系统已存在的开机启动软件，列表左侧为软件名称；列表右侧为对应软件的开机启动状态。

列表右侧的开关按钮代表了左侧软件的开机启动状态，打开代表该软件随开机启动；否则代表开机不启动。可以通过点击开关按钮来切换状态。

点击“+”添加开机启动应用按钮弹出添加窗口。

![图 7 开机启动添加](image/7.png)

#### 添加
（1）填写“程序名”；

（2）填写“程序路径”，注意保证命令合法有效或者通过点击“浏览”按钮，在弹出文件选择界面，选择以desktop为后缀的文件，程序会自动解析并导出desktop文件中的命令数据；

（3）“程序描述”作为可选项，可填可不填；

（4）最后点击“确定”按钮，新的启动项即被创建并显示在列表中；

（5）新建的启动项默认为开机启动状态。

<br>

## 设备
设备设置提供了打印机、鼠标、触摸板、键盘、快捷键、声音，六个设置模块。

### 打印机
通过控制面板设备 > 打印机，用户可以添加打印机和投影仪，下方会显示可用打印机和扫描仪列表。

![图 8 打印机设备-big](image/8.png)

### 鼠标
通过控制面板设备 > 鼠标，可对鼠标键、鼠标指针以及光标进行个性化设置。

![图 9 鼠标设备-big](image/9.png)

### 触摸板
通过控制面板设备 > 触摸板，开启触摸板，并可根据用户需求对触摸板进行个性化设置：打字时禁用触摸板、启用触摸板的鼠标点击功能、支持垂直边界滚动等。

![图 10 触摸板设置-big](image/10.png)

### 键盘
通过控制面板设备中键盘模块，可对键盘进行常规通用设置，并能够根据键盘语言调整键盘布局。

![图 11 键盘设备-big](image/11.png)

#### 通用设置
通用设置主要设置键盘输入相关基础设置。

![图 12 通用设置](image/12.png)

打开启用按键重复设置后激活重复按键功能，按下某个按键不放，系统会将该行为作为重复不间断的键盘输入；关闭后，按下某个按键不放，系统会将该行为作为一次键盘输入。

启用按键重复设置后，可对延时、速度两个选项进行设置。

**延时：**右侧的滑动条用来设置按下按键后到系统开始接收键盘输入之间的间隔，靠近“慢”的方向，间隔时间越短，系统更快的开始接收键盘输入；反之亦然。

**速度：**右侧的滑动条用来设置按下按键后，重复输入之间的间隔，靠近“慢”的方向，间隔越长，同样时间内重复输入的次数也越少；反之亦然。

**输入字符来测试重复速度：**下方的文本框用来测试设置后的效果，鼠标左键点击文本框使其获取输入焦点，按下某个按键实时查看效果。

<br>

#### 键盘布局
键盘布局是设置当前系统的键盘布局。

![图 13 键盘布局设置](image/13.png)

键盘语言的下拉菜单显示已安装的键盘布局列表，最多可以添加4个键盘布局。

点击“安装其他语言”，添加其他语言。

<br>

### 快捷键
快捷键允许用户对系统快捷键进行更改，而且可以添加或删除自定义快捷键。

通过控制面板设备 > 快捷键，查看系统内全部快捷键。

![图 14 快捷键设置-big](image/14.png)

当前快捷键存在两种分类：系统快捷键和自定义快捷键。

**系统快捷键：**仅允许修改热键键值。

**自定义快捷键：**属于用户快捷键，可以添加、删除、修改。

点击“添加自定义快捷键”按钮，弹出快捷键添加界面。

![图 15 添加快捷键](image/15.png)

填写名称、快捷按键，注意为保证命令合法有效若被占用，便会在下方提示：此快捷键已被“打开终端”占用，请重新设置。

此时需重新设置，在快捷键设置合法的情况下点击“确认”后，添加快捷键成功并即刻真实生效。

<br>

### 声音
通过控制面板设备 > 声音，可对输入、输出和系统音效进行设置。

![图 16 声音设备-big](image/16.png)

#### 输出
输出提供了输出设备的相关配置。

![图 17 声音设备输出设置-big](image/17.png)

**选择输出设备：**列表显示了当前系统的所有可用声音输出设备，通过点击单选按钮来切换输出设备。

**主音量大小：**对输出设备的主音量大小进行调节。

**声道平衡：**可以对所选输出设备进行声道设置，靠近“左”方向为左声道，靠近“右”为右声道。

<br>

#### 输入
输入提供了输入设备的相关配置。

![图 18 声音设备输出设置-big](image/18.png)

**选择输入设备：**列表列出了当前的所有输入设备，通过点击单选按钮来选择输入设备。

**音量大小：**可以配置输入设置的输入音量大小。

**输入等级：**可以配置声音输入设备的高低等级，靠近“低”方向为低级，靠近“高”为高级。

<br>

#### 系统音效
系统音效提供了对系统音效主题进行设置，对开机、注销、唤醒、操作成功等提示音进行个性化设置。

![图 19 系统音效设置-big](image/19.png)

当前系统的音效主题有Defualt、UbuntuKylin两种。

初始音效提供犬吠、雨滴、玻璃、声纳四种效果，点击对应选项进行切换。

<br>

## 个性化
个性化设置提供了背景、主题、锁屏、字体、屏保、桌面设置六个模块。

<br>

### 背景
背景模块针对桌面背景，为用户提供两种背景形式的选择：图片、颜色。

<br>

#### 图片
用户通过桌面背景 > 选择背景形式下，选择：图片。

![图 20 图片背景设置-big](image/20.png)

浏览背景列表中的缩略图，遇到意向背景后直接点击该缩略图桌面背景即设置成功。

点击“浏览本地壁纸”弹出文件选择界面。

![图 21 背景添加](image/21.png)

使用鼠标左键选中期望添加的壁纸文件后，点击“打开”按钮，待添加壁纸即会被选择为当前桌面背景并添加进背景列表中。

<br>

#### 颜色
用户通过桌面背景 > 选择背景形式下，选择：颜色。

![图 22 纯色背景设置-big](image/22.png)

### 主题
主题包括主题模式、图标主题、空间主题、光标主题、效果设置五个板块。

![图 23 个性化设置-big](image/23.png)

<br>

#### 主题模式
主题模式提供给用户两种主题进行切换：系统默认、深色模式，根据用户需求，勾选对应主题模式即可。

![图 24 主题模式](image/24.png)

#### 图标主题
图标主题提供给用户三种主题进行切换：基础、经典、默认，根据用户需求，勾选对应图标主题即可。

![图 25 图标主题-big](image/25.png)

#### 光标主题
光标主题提供给用户多种主题进行切换，选中想要设置的光标主题即可。

![图 26 光标主题-big](image/26.png)

#### 效果设置
效果设置可供用户对桌面界面的透明特效进行设置，打开透明特效开关，靠近“低”方向为低透明度，靠近“高”为高透明度。

![图 27 效果设置-big](image/27.png)

### 锁屏
锁屏模块针对锁屏界面，为用户提供锁屏背景图片切换。

选择在登陆屏幕上显示锁屏背景图片即打开对应开关按钮，且可对电脑开启锁屏所需要的时长进行设置。

![图 28 锁屏设置-big](image/28.png)

### 字体
字体模块提供了系统字体及字体大小的配置项，用户可根据需求对字体及其大小、等宽进行常规设置，在高级设置里提供相应字体的设置。

点击“恢复默认设置”按钮将所有字体设置还原为系统默认状态。

![图 29 字体设置-big](image/29.png)

### 屏保
用户可通过个性化 > 屏保，对屏保进行设置，选择开启屏保，设置开启屏保的等待时间等。

![图 30 屏保设置-big](image/30.png)

### 桌面
用户可通过个性化 > 桌面，对开始菜单进行设置、设置锁定在开始菜单的的图标等。

![图 31 桌面设置-big](image/31.png)

## 网络
网络代理主要是配置网络代理相关设置，分网络连接、VPN、代理三个模块。

![图 32 网络设置-big](image/32.png)

### 网络连接
#### 网络状态
用户可以通过网络连接模块中网络状态板块查看当前的网络连接状态。

![图 33 当前网络状态-big](image/33.png)

#### 可用网络
在可用网络列表内可查看当前可用的网络。

![图 34 可用网络列表-big](image/34.png)

### VPN
在VPN模块中，可以添加VPN连接，点击下方“添加VPN连接”，编辑名称、选择类型、设置服务器地址等即可。

![图 35 VPN设置-big](image/35.png)

### 代理
代理模块通常分自动设置可连接到互联网（即无代理）和手动代理两种模式，且两种模式同时只能存在一种。

![图 36 网络代理设置-big](image/36.png)

#### 自动设置
选择自动设置即当前系统不设置代理，直接访问互联网，点击自动设置代理的开关按钮即可。

![图 37 自动设置代理-big](image/37.png)

#### 手动设置
当有明确的代理协议情况下，比如需要使用Http代理、Https代理、Ftp代理、Socks代理时，可以选择手动配置代理，将代理服务器的IP地址和端口号填入对应文本框即可。另外Http代理可以将代理认证配置在这里从而免除了访问网络时弹出的认证窗口。点击“认证”按钮，弹出认证界面。

![图 38 手动设置代理-big](image/38.png)

## 账户
账户提供了对系统用户的管理配置，允许管理员创建用户、删除用户、修改用户信息。

![图 39 账户信息设置-big](image/39.png)

### 当前账户
#### 修改用户头像
点击用户头像即可对用户头像进行修改，图片可从本机图片中选择。

![图 40 修改用户头像](image/40.png)

#### 更改密码
用户通过点击“更改密码”即可修改当前帐户的密码。

![图 41 更改密码](image/41.png)

#### 更换账户类型
系统用户类型分两种，标准用户和管理员，区别在于管理员可以通过输入自己密码临时提升root权限；标准用户无法提升自己的权限。

用户通过点击“更换类型”即可将普通用户切换为管理员：

直接单击鼠标左键选中单选按钮后，点击“确定”按钮更新当前用户的用户类型。

注意，系统至少需要存在一个管理员用户，所以最后仅存的管理员用户无法修改用户类型至标准用户。

而且标准用户切换至管理员需要知道系统任一管理员的密码才能被允许切换，且当前用户无法删除自己。

![图 42 更换用户类型](image/42.png)

### 其他用户
在其他用户板块中，用户可对其他用户的头像、账户类型进行编辑与当前账户的设置一致，对其它用户进行添加、删除等操作。

其他用户的账户头像显示系统默认头像，点击账户头像区域弹出系统头像列表，点击列表中的头像文件或者在弹出的头像列表中点击“浏览更多图片”选择自定义头像文件，头像设置区域的头像更新为最新头像。

![图 43 其他用户设置-big](image/43.png)

#### 添加新用户
点击“添加新的用户”，定义账户名称、密码、账户类型等。

分别分别输入用户名、密码类型、密码、确认密码，点击下方用户类型单选按钮确定新建用户的类型，点击“确定”按钮，新用户被创建。

![图 44 添加新用户](image/44.png)

## 时间和日期
时间和日期设置提供了两个模块。

![图 45 时间和日期设置-big](image/45.png)

### 时间和日期
时间和日期板块中，可同步系统时间、手动更改时间、更改时区，设定为24小时制或12小时制。

![图 46 时间和日期](image/46.png)

当前的时间和日期同步状态分两种，一种是与网络时间同步，也就是与互联网上的NTP服务器时间同步；另一种是与本地计算机的时钟芯片时间同步。

<br>

#### 同步系统时间
选择“同步系统时间”后，计算机的时间与网络NTP服务器时间同步，此状态下不再允许修改时间或日期；取消“同步系统时间”后，计算机的时间与本地计算机的时钟芯片同步，此状态下可以修改时间或日期。

<br>

#### 手动更改时间
点击“手动更改时间”，对时间的时、分、秒、年份、月份、日期进行设置。
![图 47 手动设置时间日期](image/47.png)

#### 更改时区
点击“更改时区”右侧的下拉列表显示所有的时区列表。

<br>

#### 时间格式
时间格式分12小时和24小时，点击右侧相应的开关按钮即可立即生效。

<br>

### 区域语言
#### 当前区域
在区域语言模块可对当前区域进行设置，默认地区为中国。

![图 48 区域语言-big](image/48.png)

#### 更改数据格式
点击“更改数据格式”，弹窗如下图所示，可对日历、一周第一天、日期、时间自定义。

![图 49 更改格式数据](image/49.png)

#### 首选语言
系统窗口、菜单及网页的显示语言，首选推荐语言为简体中文。

用户可以通过点击“添加首语言”添加其他地区语言，作为系统语言的备选项。

<br>

## 更新
更新设置提供了系统更新与备份两个模块。

![图 50 更新和备份主界面-big](image/50.png)

### 备份
备份提供备份和还原两个板块，选择“开始备份”将文件备份到其他驱动器，选择“开始还原”查看已备份列表选择系统需要恢复的还原点进行恢复。

![图 51 备份设置-big](image/51.png)

## 通知和任务
通知和任务提供了通知、关于本机操作系统两个模块。

<br>

### 通知
通知包括通知、设置通知来源两个板块。
#### 操作中心通知
设置为在操作中心显示通知消息后，会在操作中心显示系统版本更新后的新增内容、获取来自应用和其他发送者的通知，并在锁屏界面上显示通知。

![图 52 操作中心通知设置-big](image/52.png)

#### 设置通知来源
以电源管理为例，打开开关按钮设置电源统计为通知来源，设置项：允许通知、设置在通知中心看到的最大通知数量。

![图 53 设置麒麟软件商店为通知来源](image/53.png)

### 关于
在关于模块中，可详细了解到本机系统的版本、版本号、安装日期信息和设备规格详情。

![图 54 关于本机系统-big](image/54.png)

## 常见问题
### 无法启动？
点击“开始菜单”上的“控制面板”按钮无反应？

在键盘上按下Ctrl+Alt+t组合键打开命令行终端，输入ukui-control-center后按下回车。

查看错误输出
### 无法修改配置？
修改控件状态后，控件立刻还原到修改前状态？

出现上述问题的原因大概率是因为权限问题。使用如下方法修复问题。

在键盘上按下Ctrl+Alt+t组合键打开命令行终端，输入rm ~/.config/dconf/user后按下回车，即可修复问题。

重新修改配置

