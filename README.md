try:
    num=int(input("enter number:"))
    print(num*4)
except KeyboardInterrupt:
    print("number to entered")
except ValueError:
    print("please check before u enter datatype")
print('bye')
