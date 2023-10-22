# PEP_textbook_download
这是一个用于人教社课本下载的项目。  
This is a program used in textbooks pep download.  
作者在GitHub仅提供源码，下载文件请点击下方的下载栏提供的网盘链接[跳转至下载栏](https://github.com/lueduodezhe/PEP_textbook_download#%E4%B8%8B%E8%BD%BD-download)  
The author has chosen to provide only the source code on GitHub. To download the files, please click on the provided cloud storage link in the download section below [or click here](https://github.com/lueduodezhe/PEP_textbook_download#%E4%B8%8B%E8%BD%BD-download)  
.  
**推荐使用2.1版  
Recommend using 2.1 version**  
**语言：简体中文   
language:Simplified Chinese**  
## How to use?如何使用？（此处以下载九下化学课本为例）
**（需要搭配浏览器自带的DEV tools完成操作 Complete the operation with the DEV tools provided with the browser）**   
1.打开以下网站 https://jc.pep.com.cn/  
Open the following website https://jc.pep.com.cn/  
<img width="960" alt="image" src="https://github.com/lueduodezhe/PEP_textbook_download/assets/141403762/4de369d0-b32c-4399-8cd6-00c138183c1a">  
2.选择教材    
Choose a textbook  
3.新建一个标签页，右键点击检查（审查元素），找到“网络（Network）”     
Create a new TAB, right click Check (censor element), and find "Network"  
4.单击任意一个JPG文件  
Click any JPG file  


https://github.com/lueduodezhe/PEP_textbook_download/assets/141403762/3d063286-cbce-4dc0-9404-f011f395fb3e


5.ID、校验码等如图所示  
The ID, check code ("校验码"), etc. are shown in the figure  
![SHMAD1GO{~DOCQ 2DWH$~ 5](https://github.com/lueduodezhe/PEP_textbook_download/assets/141403762/6528c3b5-eff4-4aaf-8cc8-9354939e0d73)

6.打开程序，输入对应信息并等待完成  
Open the program, enter the corresponding information and wait for it to finish  
![image](https://github.com/lueduodezhe/PEP_textbook_download/assets/141403762/a04f2342-5a4b-48d3-a58c-3339ce486c10)![image](https://github.com/lueduodezhe/PEP_textbook_download/assets/141403762/602a80a6-1c1b-4d6b-95b1-8addebbd63be)


**提示：文件名不能以阿拉伯数字打头   
Tip: File names cannot start with Arabic digits**
------
## 下载 Download  
123网盘：[点此以打开](https://www.123pan.com/s/ICnzVv-PYagh.html) 提取码:vfXg  
暮希云盘：[点此以打开](https://pan.xiaomuxi.cn/s/YeWhz)  
抗揍云：[点此以打开(v1.0)](https://wwzm.lanzouj.com/b04kaaqzg)] 提取码:1j53  
[点此以打开(v2.0)](https://wwzm.lanzouj.com/b04kaar2j)提取码:2fgc  
[点此以打开(v2.1)](https://wwzm.lanzouj.com/b04kaxcsd)提取码:cr91
## 更新日志 Changelog    
# version 2.2
修复了程序运行结束后会在后台静默运行的bug，需要注意的是，使用本版本的可执行文件版时，不能将其重命名。还改进了保存文件提示框的一个小细节。	
The bug that caused the program to continue running in the background after it has completed has been fixed. It is important to note that when using the executable version included in this release, renaming the file may cause issues. Additionally, a minor detail regarding the save file prompt has been improved.
# version 2.1      
优化了使用体验，调用了文件资源管理器来选择PDF文件的路径，也为后续的另一个分支做准备  
We have further improved the user experience by implementing "explorer" to select the path for the PDF file. This enhancement also sets the stage for a potential future branch of development.
# version 2.0     
优化了使用体验，用户交互界面从命令行窗口改为了基于Tkinker的对话框，省去了使用后需要手动删除“images”文件夹的步骤，PDF文件改为在与程序同一路径生成  
We have enhanced the user experience by transitioning from a command-line interface to a dialog box based on Tkinter. This eliminates the need for manually deleting the "images" folder after usage. Additionally, PDF files are now generated in the same directory as the program itself for added convenience.    
# version 1.0  
本python项目基于requests、Pillow等库，可以自动下载图片文件并生成PDF文件，使用后需删除“images”文件夹内所有的图片文件  
This Python project is built upon libraries such as requests and Pillow. It has the capability to automatically download image files and generate PDF files. However, it is important to note that after usage, all image files within the "images" folder should be deleted manually.
