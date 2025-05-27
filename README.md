
转自 https://github.com/youngyangyang04/PowerVim
安装
```bash
git clone https://github.com/youngyangyang04/PowerVim.git
cd PowerVim
bash install.sh
```
# 卸载 
sh uninstall.sh
```

```
正常模式下的快捷键（非插入模式）
;n              // 打开文件目录树显示在屏幕左侧
;m              // 打开当前函数和变量目录树显示在屏幕右侧
;h              // 光标移动到左窗口 
;l              // 光标移动到右窗口
;k              // 光标移动到上窗口
;j              // 光标移动到下窗口 以上四个快捷键特别是打开多个窗口情况下。使用这个快捷键组合非常实用
;w              // 保存文件
;u              // 向上翻半屏
;d              // 向下翻半屏
;1              // 光标快速移动到行首
;2              // 光标快速移动到行末
;a              // 快速切换.h和cpp文件，写C++的时候很方便
;e              // 打开一个新文件
;z              // 切回shell交互命令，输入fg在切回vim，非常实用
;s              // 水平分屏，并打开文件目录选取想打开的文件，如果想新建文件，;e 就好 
;v              // 竖直分屏，并打开文件目录选取想打开的文件，如果想新建文件，;e 就好 
;fw             // 查找项目内关键字，前提是你的系统已经按照了ACK 
;ff             // 查找项目内文件名 
;gt             // 跳转到变量或者函数定义的地方，前提是安装ctags，并且在在PowerVim输入 ;tg命令 Jump to the definition of the keyword where the cursor is located, but make sure you have make ctags
;gr             // 跳回，对应着;gt
;tg             // 对当前目录打ctag 
;y              // 保存当前选中的目录到系统剪切板，前提是vim支持系统剪切板的寄存器
;gg             // 按顺序光标跳转各个窗口
;t              // 在输入一个字符，则按照这个字符整体对齐

// 一下快捷键是不用;的，直接在 非插入模式 下输入
tb              // 插入表格
e               // 快速删除光标所在的词 
tabc            // 关闭当前tab，可以用:tabnew来打开一个新的tab Close tab, of course you should :tabnew a file first. 
F1              // 编译并运行C++文件，自己写的C++例子的时候一键编译。前提手动在当前目录建一个bin文件夹，这是用来存放编译产生的执行文件 
F1              // 编译Java文件
F2              // 运行Java编译的class文件，一般如果要编译并运行Java文件 按F1编译，在按F2运行
gc              // 快速注释选中的块（是visual模式下选中的块） 
gcc             // 快速当前行
{               // 光标向上移动一个代码块
}               // 光标向下移动一个代码块
di(             // 删除括号里的内容
di{             // 删除花括号里的内容
```
