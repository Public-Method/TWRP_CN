
**基于TWRP2.3汉化并兼容官方英文字库及主题，支持中文字符,支持扩展字库，并兼容恢复cwm的备份包[此功能代码由suky提供]**

内置和外置字库由zimo3软件生成，或可用suky编写的python代码twrp_font.py生成。

[suky修改部分]已汉化所有分辨率的主题,并添加了清除电量统计的选项(注意:该选项位置放在了条件显示的清除SD-EXT上,若需要清除SD-EXT(非外置SD)的,请自行修改对应分辨率的ui.xml)

-------------------------------------
**Team Win Recovery Project (TWRP)**

The goal of this branch is to rebase TWRP onto AOSP while maintaining as much of the original AOSP code as possible. This goal should allow us to apply updates to the AOSP code going forward with little to no extra work.  With this goal in mind, we will carefully consider any changes needed to the AOSP code before allowing them.  In most cases, instead of changing the AOSP code, we'll create our own functions instead.  The only changes that should be made to AOSP code should be those affecting startup of the recovery and some of the make files.

This branch is currently a work in progress, however, most features have been implemented and it is now ready for testing.

You can find a compiling guide [here](http://rootzwiki.com/topic/23903-how-to-compile-twrp-from-source/ "Guide").

[More information about the project.](http://www.teamw.in/project/twrp2 "More Information")

If you have code changes to submit those should be pushed to our gerrit instance.  A guide can be found [here](http://teamw.in/twrp2-gerrit "Gerrit Guide").
