from datetime import date
def diff_date(y1,m1,d1,y2,m2,d2):
    date1=date(y1,m1,d1)
    date2=date(y2,m2,d2)
    d=date2-date1
    print(d.days)
y1,m1,d1=input("Enter a number").split("/")
y2,m2,d2=input("Enter a number").split("/")
diff_date(int(y1),int(m1),int(d1),int(y2),int(m2),int(d1))
