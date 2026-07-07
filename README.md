# OrangeFox Action Builder

**这是一个基于 GitHub Actions 的自动化编译脚本，专门用于编译 OrangeFox Recovery。该版本已加入对16.0的全新支持，并针对.patch补丁进行了适配。**

### ​如何使用
**​Fork 本仓库到你的个人 GitHub 账号下。**

**​在你 Fork 的仓库中，前往 Actions 标签页。**
(如果提示 Actions 未启用，请点击绿色按钮允许其运行)。

**​在左侧菜单中选择 OrangeFox - Build 流程，然后点击右侧的 Run workflow 下拉菜单，填写你的设备参数**：

# 参数名称填写
 -**OrangeFox 源码分支**：可选 16.0 、12.1 或 11.0。
 
 -**设备树仓库地址**：设备树仓库链接，你的 Recovery 设备树 Git 地址。
 
 -**设备树分支**：你设备树分支名。

 -**设备树路径**：设备树存放路径，在源码树中的绝对路径。
 
 -**设备代号**：你的设备代号。
 
 -**编译目标**：编译目标，执行 lunch 命令时的完整目标名称。
 
 -**编译镜像**：编译生成物，可选 recovery、boot 或 vendorboot。

 -**需应用的补丁**：留空则不应用；填 all 应用全部；逗号分隔多选，列如 0000-Add-haptics.patch,0001-Change-screenshot_path.patch。
