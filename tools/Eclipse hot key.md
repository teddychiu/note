# Eclipse常用快捷键

> 代码助手:Ctrl+Space（简体中文操作系统是Alt+/）  
> 快速修正：Ctrl+1  
> 单词补全：Alt+/  
> 打开外部Java文档：Shift+F2  
> 显示搜索对话框：Ctrl+H  
> 快速Outline：Ctrl+O  
> 打开资源：Ctrl+Shift+R  
> 打开类型：Ctrl+Shift+T  
> 显示重构菜单：Alt+Shift+T     
> 选中闭合元素：Alt+Shift+Up/Down/Left/Right  
> 删除行：Ctrl+D  
> 在当前行上插入一行：Ctrl+Shift+Enter  
> 在当前行下插入一行： Shift+Enter  
> 上下移动选中的行：Alt+Up/Down  
> 组织导入：Ctrl+Shift+O  
> 跳到某行：Ctrl+L  
> 上下滚屏：Ctrl+Up/Down  
> 上一个/下一个成员（成员对象或成员函数）：Ctrl+Shift+Up/Down  
> 快速Outline：Ctrl+O   
> 在workspace中搜索选中元素的声明：Ctrl+G  
> 在workspace中搜索选中的文本：Ctrl+Alt+G  
> 在workspace中搜索选中元素的引用：Ctrl+Shift+G  
> 打开调用层次结构：Ctrl+Alt+H  
> 快速层次结构：Ctrl+T  
> 上一个编辑的位置：Ctrl+Q   
> 上下移动选中的行：Alt+Up/Down
> 拷贝选中的行：Ctrl+Alt+Up/Down 
> 添加导入：Ctrl+Shift+M
> 显示快捷键帮助：Ctrl+Shift+L
> 变为大/小写：Ctrl+Shift+X/Y

## 重构
> 显示重构菜单：Alt+Shift+T  
> 重构-改变方法签名：Alt+Shift+C  
> 重构-移动：Alt+Shift+V  
> 重构-重命名：Alt+Shift+R   

## 编辑器、视图、透视图切换
> 下一个编辑器：Ctrl+F6  
> 下一个视图：Ctrl+F7  
> 下一个透视图：Ctrl+F8  
> 最大化当前视图或编辑器：Ctrl+M  
> 激活编辑器：F12   

## Debug 
> F5：Step Into（debug）  
> F6：Step over（debug）  
> F7：Step return（debug）  
> F8：Resume（debug）  
> F11：debug上一个应用（debug）   

## F类快捷键 
> F2：显示提示/重命名  
> F3：打开选中元素的声明  
> F4：打开选中元素的类型继承结构  
> F5：刷新  
> F5：Step Into（debug）  
> F6：Step over（debug）  
> F7：Step return（debug）  
> F8：Resume（debug）  
> F11：debug上一个应用（debug）  
> F12：激活编辑器  

================================================================================
    
    Ctrl+1 快速修复(最经典的快捷键,就不用多说了)
    Ctrl+D: 删除当前行 
    Ctrl+Alt+↓ 复制当前行到下一行(复制增加)
    Ctrl+Alt+↑ 复制当前行到上一行(复制增加)
    Alt+↓ 当前行和下面一行交互位置(特别实用,可以省去先剪切,再粘贴了)
    Alt+↑ 当前行和上面一行交互位置(同上)
    Alt+← 前一个编辑的页面
    Alt+→ 下一个编辑的页面(当然是针对上面那条来说了)
    Alt+Enter 显示当前选择资源(工程,or 文件 or文件)的属性
    Shift+Enter 在当前行的下一行插入空行(这时鼠标可以在当前行的任一位置,不一定是最后)
    Shift+Ctrl+Enter 在当前行插入空行(原理同上条)
    Ctrl+Q 定位到最后编辑的地方
    Ctrl+L 定位在某行 (对于程序超过100的人就有福音了)
    Ctrl+M 最大化当前的Edit或View (再按则反之)
    Ctrl+/ 注释当前行,再按则取消注释
    Ctrl+O 快速显示 OutLine
    Ctrl+T 快速显示当前类的继承结构
    Ctrl+W 关闭当前Editer
    Ctrl+K 参照选中的Word快速定位到下一个
    Ctrl+E 快速显示当前Editer的下拉列表(如果当前页面没有显示的用黑体表示)
    Ctrl+/(小键盘) 折叠当前类中的所有代码
    Ctrl+×(小键盘) 展开当前类中的所有代码
    Ctrl+Space 代码助手完成一些代码的插入(但一般和输入法有冲突,可以修改输入法的热键,也可以暂用Alt+/来代替)
    Ctrl+Shift+E 显示管理当前打开的所有的View的管理器(可以选择关闭,激活等操作)
    Ctrl+J 正向增量查找(按下Ctrl+J后,你所输入的每个字母编辑器都提供快速匹配定位到某个单词,如果没有,则在stutes line中显示没有找到了,查一个单词时,特别实用,这个功能Idea两年前就有了)
    Ctrl+Shift+J 反向增量查找(和上条相同,只不过是从后往前查)
    Ctrl+Shift+F4 关闭所有打开的Editer
    Ctrl+Shift+X 把当前选中的文本全部变味小写
    Ctrl+Shift+Y 把当前选中的文本全部变为小写
    Ctrl+Shift+F 格式化当前代码
    Ctrl+Shift+P 定位到对于的匹配符(譬如{}) (从前面定位后面时,光标要在匹配符里面,后面到前面,则反之)

    下面的快捷键是重构里面常用的,本人就自己喜欢且常用的整理一下(注:一般重构的快捷键都是Alt+Shift开头的了)
    Alt+Shift+R 重命名 (是我自己最爱用的一个了,尤其是变量和类的Rename,比手工方法能节省很多劳动力)
    Alt+Shift+M 抽取方法 (这是重构里面最常用的方法之一了,尤其是对一大堆泥团代码有用)
    Alt+Shift+C 修改函数结构(比较实用,有N个函数调用了这个方法,修改一次搞定)
    Alt+Shift+L 抽取本地变量( 可以直接把一些魔法数字和字符串抽取成一个变量,尤其是多处调用的时候)
    Alt+Shift+F 把Class中的local变量变为field变量 (比较实用的功能)
    Alt+Shift+I 合并变量(可能这样说有点不妥Inline)
    Alt+Shift+V 移动函数和变量(不怎么常用)
    Alt+Shift+Z 重构的后悔药(Undo)

    编辑
    作用域 功能 快捷键 
    全局 查找并替换 Ctrl+F 
    文本编辑器 查找上一个 Ctrl+Shift+K 
    文本编辑器 查找下一个 Ctrl+K 
    全局 撤销 Ctrl+Z 
    全局 复制 Ctrl+C 
    全局 恢复上一个选择 Alt+Shift+↓ 
    全局 剪切 Ctrl+X 
    全局 快速修正 Ctrl1+1 
    全局 内容辅助 Alt+/ 
    全局 全部选中 Ctrl+A 
    全局 删除 Delete 
    全局 上下文信息 Alt+？
    Alt+Shift+?
    Ctrl+Shift+Space 
    Java编辑器 显示工具提示描述 F2 
    Java编辑器 选择封装元素 Alt+Shift+↑ 
    Java编辑器 选择上一个元素 Alt+Shift+← 
    Java编辑器 选择下一个元素 Alt+Shift+→ 
    文本编辑器 增量查找 Ctrl+J 
    文本编辑器 增量逆向查找 Ctrl+Shift+J 
    全局 粘贴 Ctrl+V 
    全局 重做 Ctrl+Y 

     
    查看
    作用域 功能 快捷键 
    全局 放大 Ctrl+= 
    全局 缩小 Ctrl+- 

     
    窗口
    作用域 功能 快捷键 
    全局 激活编辑器 F12 
    全局 切换编辑器 Ctrl+Shift+W 
    全局 上一个编辑器 Ctrl+Shift+F6 
    全局 上一个视图 Ctrl+Shift+F7 
    全局 上一个透视图 Ctrl+Shift+F8 
    全局 下一个编辑器 Ctrl+F6 
    全局 下一个视图 Ctrl+F7 
    全局 下一个透视图 Ctrl+F8 
    文本编辑器 显示标尺上下文菜单 Ctrl+W 
    全局 显示视图菜单 Ctrl+F10 
    全局 显示系统菜单 Alt+- 

     
    导航
    作用域 功能 快捷键 
    Java编辑器 打开结构 Ctrl+F3 
    全局 打开类型 Ctrl+Shift+T 
    全局 打开类型层次结构 F4 
    全局 打开声明 F3 
    全局 打开外部javadoc Shift+F2 
    全局 打开资源 Ctrl+Shift+R 
    全局 后退历史记录 Alt+← 
    全局 前进历史记录 Alt+→ 
    全局 上一个 Ctrl+, 
    全局 下一个 Ctrl+. 
    Java编辑器 显示大纲 Ctrl+O 
    全局 在层次结构中打开类型 Ctrl+Shift+H 
    全局 转至匹配的括号 Ctrl+Shift+P 
    全局 转至上一个编辑位置 Ctrl+Q 
    Java编辑器 转至上一个成员 Ctrl+Shift+↑ 
    Java编辑器 转至下一个成员 Ctrl+Shift+↓ 
    文本编辑器 转至行 Ctrl+L 

     
    搜索
    作用域 功能 快捷键 
    全局 出现在文件中 Ctrl+Shift+U 
    全局 打开搜索对话框 Ctrl+H 
    全局 工作区中的声明 Ctrl+G 
    全局 工作区中的引用 Ctrl+Shift+G 

     
    文本编辑
    作用域 功能 快捷键 
    文本编辑器 改写切换 Insert 
    文本编辑器 上滚行 Ctrl+↑ 
    文本编辑器 下滚行 Ctrl+↓ 

     
    文件
    作用域 功能 快捷键 
    全局 保存 Ctrl+X 
    Ctrl+S 
    全局 打印 Ctrl+P 
    全局 关闭 Ctrl+F4 
    全局 全部保存 Ctrl+Shift+S 
    全局 全部关闭 Ctrl+Shift+F4 
    全局 属性 Alt+Enter 
    全局 新建 Ctrl+N 

     
    项目
    作用域 功能 快捷键 
    全局 全部构建 Ctrl+B 

     
    源代码
    作用域 功能 快捷键 
    Java编辑器 格式化 Ctrl+Shift+F 
    Java编辑器 取消注释 Ctrl+\ 
    Java编辑器 注释 Ctrl+/ 
    Java编辑器 添加导入 Ctrl+Shift+M 
    Java编辑器 组织导入 Ctrl+Shift+O 
    Java编辑器 使用try/catch块来包围 未设置，太常用了，所以在这里列出,建议自己设置。
    也可以使用Ctrl+1自动修正。 

     
    运行
    作用域 功能 快捷键 
    全局 单步返回 F7 
    全局 单步跳过 F6 
    全局 单步跳入 F5 
    全局 单步跳入选择 Ctrl+F5 
    全局 调试上次启动 F11 
    全局 继续 F8 
    全局 使用过滤器单步执行 Shift+F5 
    全局 添加/去除断点 Ctrl+Shift+B 
    全局 显示 Ctrl+D 
    全局 运行上次启动 Ctrl+F11 
    全局 运行至行 Ctrl+R 
    全局 执行 Ctrl+U 

     
    重构
    作用域 功能 快捷键 
    全局 撤销重构 Alt+Shift+Z 
    全局 抽取方法 Alt+Shift+M 
    全局 抽取局部变量 Alt+Shift+L 
    全局 内联 Alt+Shift+I 
    全局 移动 Alt+Shift+V 
    全局 重命名 Alt+Shift+R 
    全局 重做 Alt+Shift+Y

     

    出处：http://www.blogjava.net/action/articles/17339.html

    ================================================================================

    eclipse快捷键以及使用技巧大全
    1. 打开MyEclipse 6.0.1,然后“window”→“Preferences”
    2. 选择“java”,展开,“Editor”,选择“Content Assist”。
    3. 选择“Content Assist”,然后看到右边,右边的“Auto-Activation”下面的“AutoActivation triggers for java”这个选项。其实就是指触发代码提示的就是“.”这个符号。
    4.“Auto Activation triggers for java”这个选项,在“.”后加abc字母,方便后面的查找修改。然后“apply”,点击“OK”。
    5. 然后,“File”→“Export”,在弹出的窗口中选择“Perferences”,点击“下一步”。
    6. 选择导出文件路径,本人导出到桌面,输入“test”作为文件名,点击“保存”。
    7. 在桌面找到刚在保存的文件“test.epf”,右键选择“用记事本打开”。
    8. 可以看到很多配置MyEclipse 6.0.1的信息
    9. 按“ctrl + F”快捷键,输入“.abc”,点击“查找下一个”。
    10. 查找到“.abc”的配置信息如下:
    11. 把“.abc”改成“.abcdefghijklmnopqrstuvwxyz(,”,保存,关闭“test.epf”。
    12. 回到MyEclipse 6.0.1界面,“File”→“Import”,在弹出的窗口中选择“Perferences”,点击“下一步”,选择刚在已经修改的“test.epf”文件,点击“打 开”,点击“Finish”。该步骤和上面的导出步骤类似。
    13. 最后当然是进行代码测试了。随便新建一个工程,新建一个类。在代码输入switch,foreach等进行测试。你立即会发现,果然出了提示,而且无论是敲哪个字母都会有很多相关的提示了,很流畅,很方便。
    总结:
    “Auto Activation triggers for java”这个选项就是指触发代码提示的的选项,把“.”改成
    “.abcdefghijklmnopqrstuvwxyz(,”的意思,就是指遇到26个字母和.,(这些符号就触发代码提示功能了。
    顺便说一下,修改类名,接口名等以不同颜色高亮的,可以这样配置在“java”→“enditor”→“syntac”,右边展开“java”→“classes”,勾上“Enable”这个选项,选择自己喜欢的颜色即可。
    当然还有其他相关的颜色配置。具体就不说啦。其实,在“Preferences”这个东西,有很多可以配置的东西,使得MyEclipse 优化的,具体的就要各个人根据自己个人喜好去配置了。

     

    Eclipse 常用快捷键
    Eclipse的编辑功能非常强大，掌握了Eclipse快捷键功能，能够大大提高开发效率。Eclipse中有如下一些和编辑相关的快捷键。
    1. 【ALT+/】
    此快捷键为用户编辑的好帮手，能为用户提供内容的辅助，不要为记不全方法和属性名称犯愁，当记不全类、方法和属性的名字时，多体验一下【ALT+/】快捷键带来的好处吧。
    2. 【Ctrl+O】
    显示类中方法和属性的大纲，能快速定位类的方法和属性，在查找Bug时非常有用。
    3. 【Ctrl+/】
    快速添加注释，能为光标所在行或所选定行快速添加注释或取消注释，在调试的时候可能总会需要注释一些东西或取消注释，现在好了，不需要每行进行重复的注释。
    4. 【Ctrl+D】
    删除当前行，这也是笔者的最爱之一，不用为删除一行而按那么多次的删除键。
    5. 【Ctrl+M】
    窗口最大化和还原，用户在窗口中进行操作时，总会觉得当前窗口小（尤其在编写代码时），现在好了，试试【Ctrl+M】快捷键。
    查看和定位快捷键
    在程序中，迅速定位代码的位置，快速找到Bug的所在，是非常不容易的事，Eclipse提供了强大的查找功能，可以利用如下的快捷键帮助完成查找定位的工作。
    1. 【Ctrl+K】、【Ctrl++Shift+K】
    快速向下和向上查找选定的内容，从此不再需要用鼠标单击查找对话框了。
    2. 【Ctrl+Shift+T】
    查找工作空间（Workspace）构建路径中的可找到Java类文件，不要为找不到类而痛苦，而且可以使用“*”、“？”等通配符。
    3. 【Ctrl+Shift+R】
    和【Ctrl+Shift+T】对应，查找工作空间（Workspace）中的所有文件（包括Java文件），也可以使用通配符。
    4. 【Ctrl+Shift+G】
    查找类、方法和属性的引用。这是一个非常实用的快捷键，例如要修改引用某个方法的代码，可以通过【Ctrl+Shift+G】快捷键迅速定位所有引用此方法的位置。
    5. 【Ctrl+Shift+O】
    快速生成import，当从网上拷贝一段程序后，不知道如何import进所调用的类，试试【Ctrl+Shift+O】快捷键，一定会有惊喜。
    6. 【Ctrl+Shift+F】
    格式化代码，书写格式规范的代码是每一个程序员的必修之课，当看见某段代码极不顺眼时，选定后按【Ctrl+Shift+F】快捷键可以格式化这段代码，如果不选定代码则默认格式化当前文件（Java文件）。
    7. 【ALT+Shift+W】
    查找当前文件所在项目中的路径，可以快速定位浏览器视图的位置，如果想查找某个文件所在的包时，此快捷键非常有用（特别在比较大的项目中）。
    8. 【Ctrl+L】
    定位到当前编辑器的某一行，对非Java文件也有效。
    9. 【Alt+←】、【Alt+→】
    后退历史记录和前进历史记录，在跟踪代码时非常有用，用户可能查找了几个有关联的地方，但可能记不清楚了，可以通过这两个快捷键定位查找的顺序。
    10. 【F3】
    快速定位光标位置的某个类、方法和属性。
    11. 【F4】
    显示类的继承关系，并打开类继承视图。

    调试快捷键
    Eclipse中有如下一些和运行调试相关的快捷键。
    1. 【Ctrl+Shift+B】：在当前行设置断点或取消设置的断点。
    2. 【F11】：调试最后一次执行的程序。
    3. 【Ctrl+F11】：运行最后一次执行的程序。
    4. 【F5】：跟踪到方法中，当程序执行到某方法时，可以按【F5】键跟踪到方法中。
    5. 【F6】：单步执行程序。
    6. 【F7】：执行完方法，返回到调用此方法的后一条语句。
    7. 【F8】：继续执行，到下一个断点或程序结束。

    常用编辑器快捷键
    通常文本编辑器都提供了一些和编辑相关的快捷键，在Eclipse中也可以通过这些快捷键进行文本编辑。
    1. 【Ctrl+C】：复制。
    2. 【Ctrl+X】：剪切。
    3. 【Ctrl+V】：粘贴。
    4. 【Ctrl+S】：保存文件。
    5. 【Ctrl+Z】：撤销。
    6. 【Ctrl+Y】：重复。
    7. 【Ctrl+F】：查找。

    其他快捷键
    Eclipse中还有很多快捷键，无法一一列举，用户可以通过帮助文档找到它们的使用方式，另外还有几个常用的快捷键如下。
    1. 【Ctrl+F6】：切换到下一个编辑器。
    2. 【Ctrl+Shift+F6】：切换到上一个编辑器。
    3. 【Ctrl+F7】：切换到下一个视图。
    4. 【Ctrl+Shift+F7】：切换到上一个视图。
    5. 【Ctrl+F8】：切换到下一个透视图。
    6. 【Ctrl+Shift+F8】：切换到上一个透视图。


    Eclipse中快捷键比较多，可以通过帮助文档找到所有快捷键的使用，但要掌握所有快捷键的使用是不可能的，也没有必要，如果花点时间熟悉本节列举的快捷键，必将会事半功倍
    1. edit->content Assist - > add Alt+/ 代码关联
    2. Window -> Next Editor -> add Ctrl+Tab 切换窗口
    3. Run/Debug Toggle Line Breakpoint -> add Ctrl+` 在调试的时候 增删断点
    4. Source-> Surround with try/catch Block -> Ctrl+Shift+v 增加try catch 框框
    5. Source -> Generate Getters and Setters -> Ctrl+Shift+. 增加get set 方法
    -----------有用的快捷键-----------
    Alt+/ 代码助手完成一些代码的插入(但一般和输入法有冲突,可以修改输入法的热键,也可以暂用Alt+/来代替)
    Ctrl+1:光标停在某变量上，按Ctrl+1键，可以提供快速重构方案。选中若干行，按Ctrl+1键可将此段代码放入for、while、if、do或try等代码块中。
    双击左括号（小括号、中括号、大括号），将选择括号内的所有内容。
    Alt+Enter 显示当前选择资源(工程,or 文件 or文件)的属性
    -----------Ctrl系列-----------
    Ctrl+K:将光标停留在变量上，按Ctrl+K键可以查找到下一个同样的变量
    Ctrl+Shift+K:和Ctrl+K查找的方向相反
    Ctrl+E 快速显示当前Editer的下拉列表(如果当前页面没有显示的用黑体表示)
    Ctrl+Shift+E 显示管理当前打开的所有的View的管理器(可以选择关闭,激活等操作)
    Ctrl+Q 定位到最后编辑的地方
    Ctrl+L 定位在某行 (对于程序超过100的人就有福音了)
    Ctrl+M 最大化当前的Edit或View (再按则反之)
    Ctrl+/ 注释当前行,再按则取消注释
    Ctrl+T 快速显示当前类的继承结构
    Ctrl+Shift-T: 打开类型（Open type）。如果你不是有意磨洋工，还是忘记通过源码树（source tree）打开的方式吧。
    Ctrl+O:在代码中打开类似大纲视图的小窗口
    Ctrl+鼠标停留:可以显示类和方法的源码
    Ctrl+H:打开搜索窗口
    Ctrl+/(小键盘) 折叠当前类中的所有代码
    Ctrl+×(小键盘) 展开当前类中的所有代码
    -----------Ctrl+Shift 系列-----------
    Ctrl+Shift+F 格式化当前代码
    Ctrl+Shift+X 把当前选中的文本全部变味小写
    Ctrl+Shift+Y 把当前选中的文本全部变为小写
    Ctrl+Shift+O:快速地导入import
    Ctrl+Shift+R:打开资源 open Resource
    -----------F快捷键 系列-----------
    F3:打开声明该引用的文件
    F4:打开类型层次结构
    F5:单步跳入
    F6:单步跳过
    F7:单步跳出
    F8:继续，如果后面没有断点，程序将运行完
    -----------行编辑用-----------
    Ctrl+D: 删除当前行
    Ctrl+Alt+↓ 复制当前行到下一行(复制增加)
    Ctrl+Alt+↑ 复制当前行到上一行(复制增加)
    Alt+↓ 当前行和下面一行交互位置(特别实用,可以省去先剪切,再粘贴了)
    Alt+↑ 当前行和上面一行交互位置(同上)
    Shift+Enter 在当前行的下一行插入空行(这时鼠标可以在当前行的任一位置,不一定是最后)
    Ctrl+Shift+Enter 在当前行插入空行(原理同上条)
    -----------不常用的-----------
    Alt+← 前一个编辑的页面
    Alt+→ 下一个编辑的页面(当然是针对上面那条来说了)
    Ctrl+Shift+S:保存全部
    Ctrl+W 关闭当前Editer
    Ctrl+Shift+F4 关闭所有打开的Editer
    Ctrl+Shift+G: 在workspace中搜索引用
    Ctrl+Shift+P 定位到对于的匹配符(譬如{}) (从前面定位后面时,光标要在匹配符里面,后面到前面,则反之)
    -----------不明白-----------
    Ctrl+J 正向增量查找(按下Ctrl+J后,你所输入的每个字母编辑器都提供快速匹配定位到某个单词,如果没有,则在stutes line中显示没有找到了,查一个单词时,特别实用,这个功能Idea两年前就有了)
    Ctrl+Shift+J 反向增量查找(和上条相同,只不过是从后往前查)