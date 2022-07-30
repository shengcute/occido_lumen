from sm3 import *
s='helloworld'.encode()
s=sm3(s)
s=binascii.b2a_hex(s).decode('utf-8')
s0=s[:4]
for i in range(1,2**64):
    j=(str(i)).encode()
    j=sm3(j)
    j=binascii.b2a_hex(j).decode('utf-8')
    j0=j[:4]
    if j0==s0:
        print('helloworld ',s,'\n',i,j)
        print("一对碰撞为：helloworld,",i)
        break

