记忆闪卡：Bucket /ˈbʌkɪt/
 
【正面（背诵遮挡面）】
 
单词：Bucket
词性：n.
场景：日常｜对象存储S3/MinIO/OSS
 
【背面（释义+象形记忆+IT释义，复习用）】
 
1、象形拆分记忆（你的原创记法）
 
B：大肚子孕妇（身形鼓鼓）
U：圆筒桶身（外形就是水桶）
cket 辅助收尾拼写
联想：B+U拼出水桶轮廓 → bucket=水桶
 
2、单词本义
 
n. 水桶、提桶
 
3、计算机·对象存储专业释义（核心考点）
 
Bucket = 存储桶
 
1. 对象存储顶层唯一容器，类比电脑C盘/D盘；
2. 桶内只存Object（文件对象），桶下不能新建桶；
3. 桶名全网全局唯一，S3、阿里云OSS、MinIO必备概念。
 
短句速记
 
A bucket holds water.（桶装水）
Storage bucket holds files.（存储桶装文件）
 
需要我做成纯卡片精简版，方便直接复制到Obsidian卡片吗？                    await app.fileManager.renameFile(file, timestampPath);
                }
            }
        }
    };
    
    // 告诉 Obsidian：只要这个文件被写入内容了，立刻叫醒上面的 onModify 函数
    app.vault.on('modify', onModify);
    
    // 防呆机制：如果5秒内啥也没发生（比如剪贴板是空的），自动注销监听，省得占内存
    setTimeout(() => app.vault.off('modify', onModify), 5000);
}
%>
