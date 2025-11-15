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
# if a>0:
#     print("musbat")
# elif a<0:
#     print("manfiy")
# elif a==0:
#     print("nol")
#14
# a=int(input("haftaning qaysi kuni?:"))
# if a<=7:
#     if a==1:
#         print("1-dushanba")
#     elif a==2:
#         print("2-seshanba")
#     elif a==3:
#         print("3-chorshanba")
#     elif a==4:
#         print("4-payshanba")
#     elif a==5:
#         print("5-juma")
#     elif a==6:
#         print("6-shanba")
#     elif a==7:
#         print("7-yakshanba")
# else:
#     print("haftada 7 kun bor")
#15
# a=int(input("fasllarni kiriting:"))
# if a<=12:
#     if a==1 or a==2 or a==12:
#         print("qish")
#     elif a==3 or a==4 or a==5:
#         print("bahor")
#     elif a==6 or a==7 or a==8:
#         print("yoz")
#     elif a==9 or a==10 or a==11:
#         print("kuz")
# else:
#     print("1 yilda 12 oy bor")
#16
import math

# x=float(input("x ni kiriting"))
# if x<0:
#     a=abs(x)
#     print(a)
# elif 0<=x<=5:
#     a=x**2
#     print(a)
# elif x>5:
#     a=2*x+3
#     print(a)
#17
# a=int(input("tezlikni kiriting:"))
# if 60<a<80:
#     print("ogohlantirish")
# elif 80<a<100:
#     print("kichik jarima")
# elif a>100:
#     print("katta jarima")
#18
# a=int(input("maoshingizni kiriting:"))
# if a<3000000:
#     print("past daromad")
# elif 3000000<=a<=10000000:
#     print("o'rtacha daromad")
# elif a>10000000:
#     print("yuqori daromad")
#19
# a=input("hosila olinadigan funksiyani kiriting:")
# if a=="x**2":
#     print("2*x")
# elif a=="sinx":
#     print("cosx")
# elif a=="e**x":
#     print("e**x")
#20
# a=int(input("kompyuter zaryadini kiriting:"))
# if a>80:
#     print("to'liq")
# elif 30<a<80:
#     print("normal")
# elif a<30:
#     print("kam")
#21
# a=['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','x','y','z']
# b=[]
# c=[]
# for i in a:
#     if i=='a' or i=='e' or i=='i' or i=='o' or i=='u':
#         b.append(i)
#     else:
#         c.append(i)
# print("unli:",b)
# print("undosh:",c)
#22
# users = ["qhumoyun007","humoyun3234", "humoyun1907", "humoyun007"]
# login = input("Yangi login tanlang: ")
# if login in users:
#     print("Login band, yangi login tanalng!")
# else:
#     print("Xush kelibsiz!")
#23
# a=["A","B","C"]
# b=input("diplom bahosini kiriting:")
# if b.title() in a:
#     print("ustama olishingiz mumkin")
# else:
#     print("marhamat ish xaqqingiz")
#25
# kun=input("Bugun nima kun?:")
# if kun.lower()=="shanba" or kun.lower()=="yakshanba":
#     print("Bugun dam olish kuni")
# else:
#     print("Bugun ish kuni")
#26
# a=["promo","kod"]
# b=input("promokodni kiriting:")
# if b.title() in a:
#     print("chegirma")
# else:
#     print("noto'g'ri promokod")
#27
# a=["yolg'on","sen"]
# b=input()
# if b.title() in a:
#     print("ogohlantirish")
# else:
#     print()
#28
# a=int(input())
# if a==0:
#     print("noto'g'ri ma'lumot")
# else:
#     print("olg'a")
