
  sudo -i 
 
全称：login（登录式shell）
 
1.  sudo -i  = 以root身份完整登录root环境
 
- 加载root的环境变量、PATH、家目录 /root 
- 提示符从  $  →  # ，变成root终端
 
2. 对比：
 
-  sudo 命令 ：只单条临时权限，用户环境不变、提示符还是 $ 
-  sudo -i ：整段切换root，用完敲  exit  退回去
 
简写记忆：i = login登录。