# python-AI-5-
python+AI笔记(5)
# 一阶-三章-if else组合判断语句
age=int(input("请输入你的年龄:"))
if age>=18:
    print("您已成年，需要买票10元。")
else:
    print("您未成年，可以免费游玩。")

# 一阶-三章-我要买票吗作业讲解
#定义键盘输入，获取身高数据
height=int(input("请输入您的身高(cm):"))
#通过if进行判断
if height>120:
    print("您的身高超出120cm，需要买票10元。")
else:
    print("您的身高小于120cm，可以免费游玩")
print("祝您游玩愉快")

# 一阶-三章-if_elif_else组合使用的语法
#注意，在多条件的情况之下，各个条件是互斥的，因此多个条件都满足，只会输出一行代码的结果
if int(input("bala"))<120:  #通过int转换，可以让代码清爽一些
    print("bala")
elif int(input("bsbs"))>3
    print("bsbs")
else:
    print("AAA")

# 一阶-三章-猜猜心里数字的讲解
#定义一个变量
num=5
if int(input("请猜个数字"))==num:
    print("猜对了")
elif int(input("猜错了，在猜一次"))==num:
    print("猜对了")
else:
    print("Sorry,猜错了")

# 一阶-三章-判断语句的嵌套
age=20
year=3
level=1
if age>=18:
    print("你是成年人")
    if age<30:
        print("你的年龄达标了")
        if year>2:
            print("恭喜你，年龄和入职时间都达标，可以领取礼物")
        elif level>3:
            print("恭喜你，年龄和级别达标，可以领取礼物")
        else:
            print("不好意思，尽管年龄达标，但是入职时间和级别都没有达标。")
    else:
        print("不好意思，年龄太大了")
else:
    print("不好意思，小朋友不可以领取。")

#嵌套判断语句用于多条件，多层次的逻辑判断
