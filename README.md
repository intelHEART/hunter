# hunter
python-pygame实现的2d框架GameFrame+游戏原型《追猎者》

##RUN drawmapanimation.py 

游戏基础设计过程：

    游戏愿景：

            作品志在还原一种追杀以及被追杀，且同时包含局势变化的行为状态，本作的愿景非常简单：“不是在追杀，就是在追杀的路上“

    游戏设计演绎树：


        追杀----》实力悬殊---》秒杀------》HP超过一定差值，优势方可以一击近战攻击秒杀

        局势变化---》双方HP在对抗中变化----》双方在具有陷阱的跑酷环境中追逐，双方通过其他道具与技能进行对抗

    游戏目标设计：

        对游戏进行玩法分析：

        追猎方可以因为操作失误而立刻转换成逃离者，这个转化的过程反复的频率可以过高，因此沉浸感不足

        改进：

        游戏中的追杀能力来自于一把具有时间限制的宝剑，当这把宝剑时间限制过后，它便会消失，然后在另一个地方出现，获得宝剑的玩家获得秒杀能力，即上位为追猎者。

 ![image](https://github.com/intelHEART/hunter/blob/master/hunter_start.png)
 ![image](https://github.com/intelHEART/hunter/blob/master/hunter_processing.png)
