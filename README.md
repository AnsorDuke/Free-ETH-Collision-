# Free-ETH-Collision
*(Updated at 2024.08.27)*
*Telegram @QAQRichMan*
*Telegram group: t.me/free_eth_collision*

## Announcement
*This program is for testing & learning only.*
*Take yourself's risk when running it*

## Fundamental Principles
This project programed with Python *Web3* and *multiprocessing* packages.
As known that Etherum private keys are secure big numbers, means very high randomness, very strong security, and very strong collision resistance.
This project generate massive Secure Big Numbers as private keys real quickly.
All keys will be calculated into Public Addresses, then matching the target addresses file.

## User Guide
1. Running the .exe program with a target file *target.txt* in the same folder.
2. Setting
    - Step 1: Weather print worker detail logs including key and address: (y/n).  
        Press Enter to skip and accept default No, so that can improve the performance. Enter y, to print Keys & Addresses when worker threads updating logs.
    - Step 2: Setting Log number for each worker. 
        Setting the worker's log counts printing on console. For example, set as 100, the generator in each thread will update a key to monitor after 100 times. The console monitor will print and count the total number of all workers. 
    - Step 3: Setting number of multi threads. 
        The program will show your CPUs and Threads. It's better using less than 80% of Total Threads, so your computer can maintain the running process and have normal interaction. You cannot feel any sluggish basically.
3. Outfile will be added as *success.txt* in the same folder, when successfully macthing any address in the target file. Good Luck you guys!

## Key Features
1. High performance
    - Using a special algorithm with high efficient, so can generating massive Keys & Addresses quickly. See Running Sample, showing the cases about detail numbers and spending time.
2. Ultra-minimalist 
    - The design of this program is ultra-minimalist, with clean lines and few frills. Using console interface can adapt little resource.
3. Running indepent
    - The program can running alone, just put a *target.txt* in the same folder, do not need any other dependence.
4. Free for use
    - Join in the telegram group and download the program totally in free.


## Running Sample
*All sample running on the platform with a CPU in totol 6 Cores 12 Threads.*
*All tests are only present this platform's perfamance.*

1. Testing Case 1: 
    Setting:
    - Print worker detail ? :-> **No**
    - Worker Log Count :-> **10000**
    - Multi Thread :-> **1**
    Running Time: :-> **10 minutes**
    Result:
    - CPU usage: **8.1%**
    - Collison addresses in **1 thread** & **10 minutes**: **3.89 million**
    - Expected efficiency with **1 thread** & **1 day**: **560 million** (560,000,000)

2. Testing Case 2: 
    Setting:
    - Print worker detail ? -> **Yes**
    - Worker Log Count -> **100000**
    - Multi Thread -> **4**
    Running Time: -> **10 minutes**
    Result:
    - CPU usage: **38.9%**
    - Collison addresses in **4 thread** & **10 minutes**: **14.4 million**
    - Expected efficiency with **4 threads** & **1 day** -> **2.07 billion** (2,073,600,000)


---
*(Translate with Google)*

## 公告
*此程序仅供测试和学习使用。*
*运行时请自行承担风险*

## 基本原则
本项目使用Python的*Web3*和*multiprocessing*包进行编程。
众所周知，以太坊私钥是安全的大数，意味着非常高的随机性，非常强的安全性，以及非常强的抗碰撞性。
本项目能够快速生成大量安全的大数作为私钥。
所有密钥将被计算成公钥地址，然后与目标地址文件进行匹配。

## 用户指南
1. 在同一文件夹中运行.exe程序，并放置目标文件*target.txt*。
2. 设置
    - 第1步：是否打印工作详细信息日志，包括密钥和地址：(y/n)。
        按Enter键跳过并接受默认值No，这样可以提高性能。输入y，当工作线程更新日志时打印密钥和地址。
    - 第2步：为每个工作线程设置日志数量。
        设置工作线程在控制台打印日志的计数。例如，设置为100，每个线程中的生成器将在100次后更新一个密钥以进行监控。控制台监控将打印并计数所有工作线程的总数。
    - 第3步：设置多线程数量。
        程序将显示您的CPU和线程数量。最好使用少于总线程的80%，这样您的计算机可以维持运行过程并进行正常交互。基本上您不会感到任何迟钝。
3. 当成功匹配目标文件中的任何地址时，输出文件将添加为同一文件夹中的*success.txt*。祝你们好运！

## 关键特性
1. 高性能
    - 使用高效的特殊算法，能够快速生成大量密钥和地址。查看运行样本，显示有关详细信息和花费时间的案例。
2. 超极简主义
    - 程序设计超极简，线条清晰，几乎没有装饰。使用控制台界面可以适应很少的资源。
3. 独立运行
    - 程序可以独立运行，只需在同一个文件夹中放置*target.txt*，不需要任何其他依赖。
4. 免费使用
    - 加入电报群组，可以完全免费下载程序。

## 运行样本
*所有样本都在总共有6个核心12个线程的平台上运行。*
*所有测试仅展示此平台的性能。*

1. 测试案例1：
    设置：
    - 是否打印工作详细信息？：**否**
    - 工作日志计数：**10000**
    - 多线程：**1**
    运行时间：**10分钟**
    结果：
    - CPU使用率：**8.1%**
    - 在**1线程**和**10分钟**内碰撞地址：**389万**
    - 预计效率，使用**1线程**和**1天**：**5.6亿**（560,000,000）

2. 测试案例2：
    设置：
    - 是否打印工作详细信息？-> **是**
    - 工作日志计数 -> **100000**
    - 多线程 -> **4**
    运行时间：-> **10分钟**
    结果：
    - CPU使用率：**38.9%**
    - 在**4线程**和**10分钟**内碰撞地址：**1440万**
    - 预计效率，使用**4线程**和**1天**：**20.7亿**（2,073,600,000）



