# hello-world
2018/9/27-18:52
#输出整个网段

#join() 方法实现
print "\n".join([ "192.168.10." + str(x) for x in range(1,11) ])  #for python27
#for python35
a = "\n"
print (a.join(["192.168.10." + str(x) for x in range(1,11) ]))
