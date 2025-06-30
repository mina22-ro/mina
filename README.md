# mina
Python
def mina():
	import datetime
	from time import time
	import pyfiglet

	z = pyfiglet.figlet_format("mina khalaf")
	p = pyfiglet.figlet_format("    rogina    ")
	
	print("\033[95m", z, p)
	print("\033[00m")
	
	start = time()
	
	w = "                 welcome to python          "
	print(w)
	print("©" * 60)
	print("&" * 60)

	today = datetime.datetime.now().date()

	y = int(input("year: "))
	m = int(input("month: "))
	d = int(input("day: "))
	
	dob = datetime.date(y, m, d)

	print("تاريخ اليوم: ", today)
	print("تاريخ ميلادك: ", dob)

	age = (today - dob).days / 365.25
	print("age: ", age)

	end = time()

	runtime = end - start
	print("⏱️ وقت تشغيل البرنامج:", runtime, "ثانية")

mina
