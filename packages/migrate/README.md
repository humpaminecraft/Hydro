# migrate


这个模块用于从其他系统批量导入数据。
迁移过程中请保持网络畅通。

## migrate-vijos

从Vijos4.0的数据库导入数据。  
迁移前，您需要指定数据来源。  
**请不要**将 Hydro 正在使用的数据库设置为数据来源的数据库。  
迁移过程中，Hydro 的以下内容会被**清空**：  
题目列表，提交记录，用户列表，比赛列表，比赛成绩表，训练列表，训练进度，站内消息，题解，讨论  
以下内容将被迁移：  
题目与测试数据、题解，讨论与回复，比赛、训练、作业相关数据，提交记录，用户列表，站内消息。

## migrate-hustoj

从HustOJ的数据库导入数据。  
迁移过程中，Hydro 的内容会被**清空**，以下内容将被迁移：  
题目与测试数据，用户列表。