# python2
2nd project showing a python code for file handling

f=open('first1.txt',"r")
print(f.read())
f.close()
f=open('first1.txt',"r")
print(f.readline())
print(f.readline())
print(f.readline())
F=open('first1.txt',"w")
F.write("overwritten")
F.close()
F=open('first1.txt',"r")
print(F.read())
F.close()


f=open("star.txt","r")
print(f.read())
f.close()


try:
    f=open("star.txt","r")

except IOError:
    print("file does not exist")
else:
    print(f.read())
f.close()


try:
    f=open("steps.txt","r")

except IOError:
    print("file does not exist")
else:
    print(f.read())
f.close()
