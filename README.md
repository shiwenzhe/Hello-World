# 问题1

手机号的属性标签合并，文件phone.txt有一亿条手机号标签记录，文件new.txt有100万条记录两个文件的手机号合并成一个phone_all.txt文件

例如:
 
phone.txt文件格式如下：  
>13800000000|卡商,诈骗  
>13800000001|诈骗  
>13800000002|卡商  
>13800000003|外卖  


new.txt文件格式：  
>13800000002|卡商,诈骗  
>13800000003|金融  
>13800000004|卡商  

合并之后phone_all.txt文件：  
>13800000000|卡商,诈骗  
>13800000001|诈骗  
>13800000002|卡商,诈骗  
>13800000003|外卖,金融  
>13800000004|卡商  
 
考虑程序性能，内存利用，算法复杂度。
