# uyga-vazifa05
import math
#1
# a=int(input("sonni kiriting:"))
# if a%2==1:
#     print("toq son")
# else:
#     print("murakkab son")
#2
# a=int(input("balingizni kiriting:"))
# if a>60:
#     print("o'tdingiz")
# else:
#     print("yiqildingiz")
#3
# a=int(input("harorat nechchi gradus(gradus selsiyda):"))
# if a>0:
#     print("normal")
# else:
#     print("muzlash xavfi bor")
#4
# a=int(input("bank hisobingizda qancha bor?:"))
# if a<0:
#     print("qarzdorsiz")
# else:
#     print("musbat balans")
#5
# a=int(input("doira radiusini kiriting"))
# if a>0:
#     s=math.pi*a**2
#     print("yuzasi:",s)
# else:
#     print("radius manfiy bola olmaydi")
#6
# a=int(input("yoshingizni kiriting:"))
# if a>=18:
#     print("shartnoma tuzish mumkin")
# else:
#     print("mumkin emas")
#7
# a=float(input("dioganallar orasidagi gradusni kiriting(radianda):"))
# b=8
# c=9
# if a>=360 or a==0 or a==180:
#     print("dioganallari kesishmaydi")
# else:
#     s=b*c*math.sin(math.degrees(a))
#     print("yuzasi:", s)
#8
# a=float(input("sonni kiriting: "))
# if 0<=a<=1:
#     b=a**2
#     print(b)
# else:
#     b=2*a+1
#     print(b)
#9
# a=int(input("sekundni kiriting:"))
# if a>=3600:
#     b=a//3600
#     c=(a%3600)//60
#     d=(a%3600)%60
#     print(b,"-soat",c,"-minut",d,"sekund")
# else:
#     b=a//60
#     c=a%60
#     print(b,"-minut",c,"-sekund")
#11
# a=int(input("balingizni kiriting:"))
# if a>=90:
#     print("A")
# elif 90>a>=80:
#     print("B")
# elif 80>a>=70:
#     print("C")
# elif 70>a>=60:
#     print("D")
# else:
#     print("F")
#12
# a=int(input("1-tomonni kiriting:"))
# b=int(input("2-tomonni kiriting:"))
# c=int(input("3-tomonni kiriting:"))
# if a==b==c:
#     print("teng tomonli")
# elif a==b or b==c or c==a:
#     print("teng yonli")
# else:
#     print("turli tomonli")
#13
a=float(input())
if a>0:
    print("musbat")
elif a<0:
    print("manfiy")
elif a==0:
    print("nol")
