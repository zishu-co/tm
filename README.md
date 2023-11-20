# 自塾时间管理用户手册
简介：自塾时间管理是一款简单易用，超轻量级的时间管理软件。程序本身只是一个html文件，下载到电脑后，双击即可用浏览器运行。数据是被储存在浏览器中的，因此请使用同一个电脑的同一个浏览器打开使用。

## 认识界面
自塾时间管理的界面包括三部分。
1、最上边的按钮区，包括五个按钮，分别是 开始、结束、新增、删除和归档。
2、中间的当前记录区，包括一个表格，用于记录当前处理的事项。
3、下部的历史记录区，包括一个表格，用于展示历史完成的事项。

## 控件用法

#### 表头：
当前记录和历史记录的表格均有表头和表身，用鼠标点击表身的其中一条就是选中一条记录，该条记录选中后会出现底色高亮。用鼠标点击表头是取消选中，取消选中后，表身的底色高亮被去除。
#### 开始按钮：
在选中某一条当前记录的情况下，开始按钮变为深色，意思为可用。点击开始按钮，就会在选中的那条当前记录的开始时间填入当前的时间，格式为hh:mm:ss。同时在日期中填入当天的日期，格式为yyyy/mm/dd。
#### 结束按钮：
在选中某一条当前记录的情况下，结束按钮变为深色，意思为可用。点击结束按钮，就会在选中的那条当前记录的结束时间填入当前的时间，格式为hh:mm:ss。同时计算开始时间和结束时间的时间差，转换为小时，保留小数点后两位，填入实际用时中。
#### 新增按钮：
当天记录和历史记录对应的选中状态分为四种，“新增”这个按钮的作用也不同。
第一种：点击当天记录和历史记录的表头，取消所有选中，那么点击“新增”按钮，就会在当天记录的最下方新增一行完全空白的记录，我们可以自己去填写内容。
第二种：点击当天记录中的某条记录，历史记录不要选中任何记录，那么点击“新增”按钮，就会在当天记录的选中的那条记录下方新增一条记录，同时复制了选中的那条记录的编号、主题和统筹配时。
第三种：点击历史记录中的某条记录，当天记录不要选中任何记录，那么点击“新增”按钮，就会在当天记录的选中的那条记录下方新增一条记录，同时复制了选中的那条记录的编号、主题和统筹配时。
第四种：既点击选中了当天记录中的某条记录，也点击选中了历史记录中的某条记录，这种情况以选中的当天记录为准，同第二种情况。

#### 删除按钮
在选中某一条当前记录的情况下，删除按钮变为深色，意思为可用。点击删除按钮，就会删除选中的那条当前记录。

#### 归档按钮
凡是已经有实际用时的记录，均可以进行归档。如果选中了某条记录，点击归档就是归档这一条当前记录。如果取消选中，点击归档就是归档所有的有实际用时的当前记录。归档后，该条记录从当前记录移到历史记录中。

## 表格字段用法

#### 序号
把当前列表的记录从1开始编号，顺序递增。

#### 编号
给当前的任务进行编号，能够区分不同的任务的任何识别号都可以。如果暂时想不起来，可以用当天的日期当作编号，比如1120、1121、1122等。

#### 主题
当前任务的关键词，只要能简明地表达当前任务的内容即可，一看到这个主题就能知道这个任务是哪个任务。主题和编号要一一对应。主题的开头可以用ABC来表示这个任务的轻重缓急。A代表重要紧急。B代表重要不紧急。C代表紧急不重要。

#### 统筹配时
当前任务的总计划用时。这个统筹配时一般是由外部来决定的，比如客户希望在多长时间内完成？领导希望在多长时间内完成？

#### 分拆事项
一个任务如果能一口气做完，一般在1小时以内的话，基本用不着拆分，拆分事项可以空着。如果一个任务需要用好多个小时，无法一次性做完，那就需要拆分成多个小任务，每个小任务都赋予一个分拆事项。分拆事项的开头可以用ABC来表示这个任务的轻重缓急。

#### 分拆配时
一个分拆事项计划用多长时间来做完，可以把计划时间写在分拆配时。一般分拆配时不要超过两个小时，因为一般人很难连续集中精力工作两个小时。最好分拆成半个小时一段，每段之间安排休息。

#### 开始时间
点击开始按钮，系统会自动填入这项工作的开始时间和当天的日期。接下来集中精力处理工作，直到一股作气完成了这个事项。开始时间填入后可以手动编辑。

#### 结束时间
点击结束按钮，系统会自动填入这项分拆事项的结束时间，并计算开始时间和结束时间的时间差，换算成小时，并四舍五入保留小数点后两位，填入实际用时。结束时间填入后可以手动编辑。

#### 实际用时
系统会始终计算开始时间和结束时间的时间差，换算成小时，并四舍五入保留小数点后两位，填入实际用时。

#### 日期
点击开始按钮，系统会自动填入这项工作的开始时间和当天的日期。日期填入后可以手动编辑。

## 数据统计

#### 当天有效工作时间
只要当前记录中有实际时间，当前记录的表格下方就会显示当天有效工作时间。一般来说，当天有效工作时间大于6小时比较理想。

#### 某一任务的总用时
归档后的记录也可以选中，在表格上方会显示那一天的有效工作时间以及那个编号的工作的统筹配时、分拆配时和实际用时的总和。如果实际用时总和小于统筹配时，那么这个任务的效率系数大于1，是比较理想的，继续加油。如果效率系数小于1，就需要分析一下在哪个分拆事项上耽误了时间。

#### 筛选
编号、主题和日期均可以根据关键字进行筛选。筛选后的数据即时显示在下方的历史记录的表格中。

#### 历史列表总用时
历史记录的表格的下方会始终显示当前历史列表的总用时。
