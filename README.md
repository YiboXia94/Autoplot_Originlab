# Double-click the data file and automatically plot in Originlab

### This is a script that allows you to skip selecting the data column and draw simple graphics directly.
Open a text and input:

```start C:\"Program Files"\OriginLab\Origin2017\Origin94_64.exe -r {impasc %1;plotgroup iy:=(A,B) type:=line template:=LINE2}```

and save it as a `.bat` file.

Add it as a default opening method to your data file, and just double-click the file, then you can obtain the plot directly.

### Some settings:
- Set the path of Originlab: `C:\"Program Files"\OriginLab\Origin2017\Origin94_64.exe`

- Set the plot group: Column A vs Column B: `iy:=(A,B)`; Column A vs Column B&C: `iy:=(A,B:C)`

- Set plot style: `type:=scatter`

### Details can be found in the tutorials: <https://www.originlab.com/doc/X-Function/ref/plot_bygroup>

# 用bat脚本实现双击数据即可在Originlab里绘出图形

### 跳过选择数据栏步骤，双击即可得到图形。
新建记事本，并复制以下代码：

```start C:\"Program Files"\OriginLab\Origin2017\Origin94_64.exe -r {impasc %1;plotgroup iy:=(A,B) type:=line template:=LINE2}```

另存为 `.bat` 文件。
将文件的默认打开方式更改为此文件，双击数据即可自动绘图。

### 脚本设置:
Originlab路径: `C:\"Program Files"\OriginLab\Origin2017\Origin94_64.exe`

绘图选项: Column A vs Column B: `iy:=(A,B)`; Column A vs Column B&C: `iy:=(A,B:C)`

线形设置：线图：`type:=line`，散点图： `type:=scatter`。

### 详细设置参数请参考：<https://www.originlab.com/doc/X-Function/ref/plot_bygroup>
