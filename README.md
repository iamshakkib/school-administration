# school-administration
grading system
marks = []
for a in range(5):
    n = int(input("enter the marks obtained in subject"+ str(a+1) + ": "))
    marks.append(n)
total=sum(marks)
avg=total/5
print("total maks obtained in 5 subjects are " ,total)
print("percentage obtained ",avg)
if avg >= 90 and avg<= 100:
        print("A")
elif avg >= 80 and avg<= 89:
    print("B")
elif avg >= 70 and avg<= 79:
    print("C")
elif avg >= 60 and avg<= 69:
    print("D")
elif avg >= 50 and avg<= 59:
    print("E")
else:
    print("F")
