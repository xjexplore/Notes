@font-face CSS at-rule 指定一个用于显示文本的自定义字体；体能从远程服务器或者用户本地安装的字体加载. 如果提供了local()函数，从用户本地查找指定的字体名称，并且找到了一个匹配项, 本地字体就会被使用. 否则, 字体就会使用url()函数下载的资源。(https://developer.mozilla.org/zh-CN/docs/Web/CSS/@font-face)

文本属性：

1. text-align(水平对齐)：
属性值left,right,center,justify(应用于块级元素，有继承性)

2. line-height(垂直对齐)：
指文本行基线之间的距离，line-height值和字体大小之差就是行间距。(应用于所有元素，有继承性)

3. vertical-align(直对齐文本)：
值：baseline,sub,super,top,bottom,middle,inherit
初始值：baseline
应用于：行内元素和表单元格
继承性：无

4. word-spacing(字间间隔)：
应用于所有元素，有继承性，初始值为normal

5. letter-spacing(字母间隔):
应用于所有元素，有继承性，初始值为normal

6. text-transform(文本转换)：
值：uppercase,lowercase,capitalize,none,inherit
初始值：none
应用于：所有元素
继承性：有

7. text-decoration(文本装饰)：
值：none,underline,overline,line-through,blink,inherit
初始值：none
应用于：所有元素
继承性：无

8. text-shadow(文本阴影)：
值：none,[<color> || <length> <length> <length>?,]*<color> || <length> <length> <length>?,],inherit
初始值：none
应用于：所有元素
继承性：无
前两个长度值确定了阴影与文本的偏移距离，第三个长度值可选，定义了阴影的”模糊半径“

9. white-space(处理空白符)：
值：normal,nowrap,pre,pre-wrap,pre-line,inherit
初始值：normal
应用于：所有元素
继承性：无
值          空白符          换行符          自动换行
pre-line    合并            保留            允许
normal      合并            忽略            允许
nowrap      合并            忽略            不允许
pre         保留            保留            不允许
pre-wrap    保留            保留            允许