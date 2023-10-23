# How to use PCDCT Data Tool

该教程用于帮助用户理解如何使用PCDCT Data Tool。

请点击[此处](https://carcgl.sharepoint.com/sites/PCDCTTool/Shared%20Documents/Forms/AllItems.aspx?FolderCTID=0x012000D0DD37E577FC5440B792C14CBE008619&id=%2Fsites%2FPCDCTTool%2FShared%20Documents%2FGeneral%2FDataPlot%5FV1%2Ezip&parent=%2Fsites%2FPCDCTTool%2FShared%20Documents%2FGeneral)获取PCDCT Data Tool压缩包。

## **1. Python解释器安装**

1. 在下面的链接中找到python的安装包:
   <font color="blue">\\172.24.236.30\srdc\Large_Chiller\18-MBD(ZXJ)\MBD</font><br />
  ![](../../picture/MV4MBDInstallationGuidance/1.png)


1. 下载成功后，双击安装程序，开始安装。(需与IT联系获取admin权限)


3. 注意安装到这一步的时候，一定要勾选 Add Python 3.7 to path 选项， 然后再点击 Customize installation
  ![](../../picture/PCDCTGuidance/1.png)


4. 在下图这一步时，点击 Next 即可
  ![](../../picture/PCDCTGuidance/2.png)


5. 在下图这一步时，按图示步骤操作。随后，等待安装完成。
  ![](../../picture/PCDCTGuidance/3.png)

    ![](../../picture/PCDCTGuidance/4.png)


## **2. Python交互式命令行**

运行python程序，直接在命令行中敲 python就行了，不必写上完整的Python.exe的路径。如下所示：

  ![](../../picture/PCDCTGuidance/6.png)


## **3. 命令行运行PCDCT数据处理工具**

1. 打开命令行窗口。
  ![](../../picture/PCDCTGuidance/7.png)

2. 进入代码文件所在目录。
  ![](../../picture/PCDCTGuidance/8.png)

3. 使用`pip install `安装依赖库pandas，datetime and plotly。
 
    `pip install pandas`
    ![](../../picture/PCDCTGuidance/9.png)
    `pip install datetime`
    ![](../../picture/PCDCTGuidance/10.png)
    `pip install plotly`
    ![](../../picture/PCDCTGuidance/11.png)

4. 将需要绘制的数据以.csv的格式存放在LabData文件夹里。
  ![](../../picture/PCDCTGuidance/12.png)   

5. 打开PCDCT.py文件，在第9行中，将数据文件名更改为需要绘制的文件名(不用加.csv后缀)
  ![](../../picture/PCDCTGuidance/13.png) 

6. 在命令行里面敲入命令 
  `python PCDCT.py`
  ![](../../picture/PCDCTGuidance/15.png)

## **4. 安装VScode**  

1. 在下面的链接中找到vscode的安装包:
   <font color="blue">\\172.24.236.30\srdc\Large_Chiller\18-MBD(ZXJ)\MBD</font><br />
  ![](../../picture/PCDCTGuidance/29.png)
   
2. 双击下载后的可执行文件，安装。
   ![](../../picture/PCDCTGuidance/21.png)

3. 勾选同意，点击下一步。
    ![](../../picture/PCDCTGuidance/22.png)

4. 选择安装位置。然后点击下一步。
    ![](../../picture/PCDCTGuidance/23.png)

5. 点击下一步(不创建开始菜单可以不勾选)
    ![](../../picture/PCDCTGuidance/24.png)

6.  勾选创建快捷方式，点击下一步。
    ![](../../picture/PCDCTGuidance/25.png)

7.  点击安装，开始安装。
    ![](../../picture/PCDCTGuidance/26.png)

8.  等待安装结束。
    ![](../../picture/PCDCTGuidance/27.png)

    ![](../../picture/PCDCTGuidance/28.png)






## **5. 使用VScode运行PCDCT数据处理工具**  

1.在 文件 选项下，选择将文件夹添加到工作区

![](../../picture/PCDCTGuidance/16.png) 

2.在 终端 选项下， 选择新建终端。
   
![](../../picture/PCDCTGuidance/17.png) 

3.在终端中使用`pip install `安装依赖库pandas，datetime and plotly。

`pip install pandas`
![](../../picture/PCDCTGuidance/18.png)

`pip install datetime`
![](../../picture/PCDCTGuidance/19.png)

`pip install plotly`
![](../../picture/PCDCTGuidance/20.png)

4.将需要绘制的数据以.csv的格式存放在LabData文件夹里。
   
![](../../picture/PCDCTGuidance/12.png)   

5.打开PCDCT.py文件，在第9行中，将数据文件名更改为需要绘制的文件名(不用加.csv后缀)
   
![](../../picture/PCDCTGuidance/13.png) 

6.点击运行python文件。

![](../../picture/PCDCTGuidance/14.png) 














   