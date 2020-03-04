# mkmatminer
Seele gpu miner  

(Fixed the problem of high CPU usage on some machines, which may reduce mining efficiency. Now fixed)  
    
How to use:  
1: Copy the files in this folder to the build directory of go-seele  
2: Modify ../node2t.json under runit.bat to your file name  
3: Run runit.bat and runmkmatminer.bat  
  
100 ~ 200 seele one day on gtx1080  
It is recommended to synchronize windows time to ensure mining efficiency  
You can change node2 in runit.bat to node31,  node2(1.2.6) node31(1.3.1)  
Do not change the number of cpu threads "--threads 1"  
  
  
（修复了部分机器cpu使用过高的问题，该问题可能降低挖矿效率，现已修复） 
   
如何使用：  
1： 把这个文件夹下的文件复制到go-seele的build目录下  
2： 修改runit.bat下的 ../node2t.json 为你的文件名  
3： 运行runit.bat同时运行runmkmatminer.bat  
  
100~200 seele每天在gtx1080上  
建议同步 windows时间 来保证挖矿效率  
可以把runit.bat中的node2改成node31， node2（1.2.6） node31（1.3.1）  
不要改变cpu线程数“--threads 1” 

  
  
