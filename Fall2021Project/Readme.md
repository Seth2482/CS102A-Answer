# CS102A/CS107 Project: Reversi

这次project的主题是黑白棋，总体来说比较简单。       
这个仓库维护了一个已经可以运行且拿到80分基本分的demo，仅供参考，禁止抄袭！     
如果您觉得这个写得不错，不妨给CS102A-Answer来个star！

## Project需求
- Task 1: 初始化游戏(20分)**（已实现）**
    - 应用程序要求能够初始化一个具有4个棋子的棋盘 **（也就是说，棋盘要能够初始化！）**
    - 应用程序要求能够展现游戏状态（当前行棋方，黑白棋子数量等等） **（也就是说，当前棋局的状态要能展现出来）**
    - 应用程序要求能够在不通过关闭游戏重启的方法，重新开始新的一局游戏 **（也就是说，玩家能随时重新开始新的一把游戏）**

- Task 2: 保存/读取游戏(20分)**（已实现）**
    - 应用程序一个能够通过一个按钮，来从文本文件中读取一个游戏。保存的文本文件要包括当前棋盘，先前的移动步骤，以及当前行棋方。**（也就是说，要能从文本文件中读取一个棋局）**
    - 应用程序应当能对错误的文本文件进行检查（如无胜利方，非法走子等等）**（也就是说，有可能有错误的棋谱文件，要能够做相应的检查，A3Q5）**
    - 应用程序应当能把当前棋局保存到一个文本文件中 **（也就是说，要能本地化保存棋盘游戏到一个文件中）

- Task 3: 运行游戏(20分)**（已实现）**
    - 应用程序要能够判定当前局面是否游戏结束，以及用户的赢输状态
    - 应用程序要能够根据Reversi的规则做棋子翻转 **（A3Q5）**
    - 应用程序要能够在作弊模式和正常模式中任意切换，作弊模式允许在任何空的位置下棋子

- Task 4: 图形界面(20分)**（已实现）**
    - 应用程序要使用图形化界面（JavaSwing或者JavaFX）**这其实是说，你的程序不能与命令行做任何的交互！**

- Bonus(15周答辩上限30，16周答辩上限20)**（未实现）**
    - 人机对战 **（随机？贪心？Alpha-Beta剪枝搜索？多种评估策略？）**
    - 用户排行榜 **（用户管理系统？文本文件保存用户排名机制？）**
    - 主题皮肤切换，完善的用户界面 **（多写几个页面然后做切换？主题皮肤可以考虑图片读取？）**
    - 增加背景音乐和棋子音效 **（多线程运行音乐避免卡死？）**
    - 可行移动位置提示 **（A3Q4？）**
    - 加载棋局时步骤显示 **（重绘并线程休眠？）**
    - 悔棋 **（记录先前移动步骤，然后做相应修改？）**
    - 局域网联网对战 **（socket编程？）**
    - 可执行文件压缩打包 **（exe4j？）**       
    - 黑白棋/反转黑白棋规则切换 **（加个按钮的事情？）**
    - 用户机制中皮肤抽奖和充钱 **（文本文件读取+图片绘制？）**

## 答辩分数计算规则
- CS102A班（JavaA普通班）：      
15, 16两周任选一周答辩，其中基本分80分，bonus分数上限是15周为30分，16周为20分        
15周答辩基本分×1.05         
选取1/20-1/15的15周答辩优秀小组进入16周的理论课答辩         

- CS107班（JavaA图灵班）：
只能15周答辩，bonus上限为30分，无基本分的比例系数加成，且bonus部分加分幅度小于普通班         
只要做得优秀，都有去16周理论课答辩的机会！

## 给学弟学妹们的话
这次project难度较低，很容易就能拿到很高的分数，推荐各位同学们尽快开始，争取15周答辩好并去理论课答辩！