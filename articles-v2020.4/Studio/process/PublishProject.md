# 发布自动化项目
**发布自动化项目**允许你将编辑成功的自动化项目进行发布及存储，以便后续机器人执行或共享流程。

自动化项目发布到控制台后，将存储在流程包管理页面，以便分配给指定机器人执行。而发布到流程市场后，将存储在指定的流程市场中，以便实现共享。

如果想要将自动化项目直接交付给机器人进行执行，可以通过发布到机器人，将自动化项目发送到对应机器人。


要实现发布流程，从工具栏->发布中选择你想要发布的位置，然后点击它。

<!-- ![发布项目](https://docimages.blob.core.chinacloudapi.cn/images/Studio/automationProject/publishProject/choosePosition.PNG) -->

## 发布流程
1. 创建一个自动化项目。项目示例参看[创建自动化项目](./CreateProject.md?_v=v2020.4)
2. 在工具栏->发布选择发布的位置：
    * 发布到控制台
    
        ![发布到控制台](https://docimages.blob.core.chinacloudapi.cn/images/Studio/automationProject/publishProject/publishToConsole.PNG)

        a. 在**资源组**部分，可以选择需要将项目发布到哪个资源组中。

        b. **流程包名称**默认情况下为项目名称，可进行更改。

        c. 在**版本号**部分，可以查看项目的**当前版本号**，然后根据需要添加**最新版本号**。若更改版本号信息，需注意的是最新版本号要大于当前版本号。

        d. (可选)**备注**部分主要输入与当前自动化项目有关的版本及其他信息的相关介绍。请注意，备注的内容不可超过220个字符。

    * 发布到机器人
    
        ![发布到机器人](https://docimages.blob.core.chinacloudapi.cn/images/Studio/automationProject/publishProject/publishToRobot.png)

        a. 在**机器人**部分，显示的是当前系统中已激活的机器人名称。

        b. **流程包名称**默认情况下为项目名称，可进行更改。

        c. 在**版本号**部分，可以查看项目的**当前版本号**，然后根据需要添加**最新版本号**。若更改版本号信息，需注意的是最新版本号要大于当前版本号。

        d. (可选)**备注**部分主要输入与当前自动化项目有关的版本及其他信息的相关介绍。请注意，备注的内容不可超过200个字符。

    * 发布到流程市场
    
        ![发布到流程市场](https://docimages.blob.core.chinacloudapi.cn/images/Studio/automationProject/publishProject/publishToFlowmarket.PNG)

        a. 在**流程市场**部分，可以选择需要将项目发布到哪个流程市场中。请注意，首次发布需通过**管理市场**配置你的市场，具体步骤请参考[管理市场](../Market.md?_v=v2020.4)。

        b. **流程包名称**默认情况下为项目名称，可进行更改。
        
        c.  在**版本号**部分，可以查看项目的**当前版本号**，然后根据需要添加**最新版本号**。若更改版本号信息，需注意的是最新版本号要大于当前版本号。
        
        d. (可选)**图标**主要用于对当前发布的流程进行标识。
        
        e. **描述**部分主要输入对当前自动化项目的功能等相关介绍。请注意，描述的内容不可超过200个字符。
        
        f. (可选)**标签**用于定义当前流程。

3. 点击“发布”，该项目将会发布到指定位置。
4. 发布成功后，将弹出一个信息提示框，显示：
    * 发布成功的项目名称
    * 该项目的版本号

        ![发布成功](https://docimages.blob.core.chinacloudapi.cn/images/Studio/automationProject/publishProject/publishSuccess.PNG)