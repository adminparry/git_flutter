一个material的文本字段

允许用户在外接键盘或者屏幕的虚拟键盘进行输入
每当用户更改文本中的字段的时候 都会调用onChanged的回调方法
当用户输入完的内容要进行提交时 都会调用onSubmitted回调方法 例如在虚拟键盘上的确认

控制文本显示的内容可以通过controller进行

例如设置个初始值 控制已经包含的某些文字 也可以控制文本的选中的区域

继承关系
Object > Diagnosticable > DiangosticableTree > Widget > StatefulWidget > TextField

