## vim 

### 三种模式

**同步SUDO问题，建立软链接**

ln -s /home/ayjin/.vim /home/root/.vim

ln -s /home/ayjin/.vim/vimrc /home/root/.vim/vimrc

> ***普通模式***
>
> > Ese 然后：输入指令
> > u：返回上一个操作。
> > p:粘贴
> > yy:复制一整行

> ***插入模式***
>
> > i 普通插入
> >
> > a 追加
> >
> > o 在下一行添加新行
> >
> > 0 回到开头
> >
> > G 跳入最后一行
> >
> > shift + i 行头
> >
> > shift + a 行尾添加
> >
> > shift + o
> >
> > 全选5j 下五行 
> >
> > 5l 右五格
> >
> > delect:
> >
> > > d3->右删三个
> > >
> > > dd 剪切该行
> >
> > 复制：
> >
> > > y3->复制三个
> > >
> > > yA->复制到尾
> >
> > change:
> >
> > w:跳入下一个词的开头
> >
> > b:跳入到上一个词的开头
> >
> > > c6->右删除三个并进入写入模式
> > >
> > > ciw改变光标处的词
> > >
> > > ci" 改变爽引号内的词
> >
> > find:
> >
> > > f: 找到冒号
> > >
> > > df:  删除到冒号
> > >
> > > yf:  复制到冒号
> >
> > 搜索
> >
> > > /map  搜索map
> > >
> > > n下一个
> > >
> > > N上一个

> **可视模式**
>
> > 普通模式
> >
> > v进入
> >
> > 可以用鼠标进行文本选择
> >
> > shift v 
> >
> > 选择一行一行
> >
> > 全选操作：
> >
> > shift v G
>
> > 可视块模式
> >
> > Ctrl v 
> >
> > 选定代码块
>
> ## 分屏打开代码
>
> > :vsplit打开分屏
> >
> > 切换分屏
> >
> > ctrl w + 分屏的位置hjkl
> >
> > :e ~path
> >
> > 调整分屏大小
> >
> > :vertical resize +10
> >
> > 上下
> >
> > resize +10

## chrome vimium

>  选择当前窗口元素 f + 你目标
>
> 向下 j
>
> 快速向下d
>
> 向上k
>
> 快速向上u
>
> 回到顶部gg
>
> 回到底部G
>
> 帮助 shift+/
>
> 快速搜索o
>
> 当前标签页前进H后退L
>
> 关闭页面x
>
> 回复页面X 
>
> 

