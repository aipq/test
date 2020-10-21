# test
def tu(n):
    if n==1:
        return n
    else:
        return n*tu(n-1)

n=int (input('请输入一个整数：'))
su=tu(n)
print("%d 的阶乘是：%d" % (n,su))
