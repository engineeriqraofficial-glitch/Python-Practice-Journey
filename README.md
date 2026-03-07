# Python-Practice-Journey#Ek "Admission Eligibility" checker banaiye.
#Neeche di gayi conditions check karein:

#Student ke marks 60 se zyada hone chahiye AND uski attendance 75% se zyada honi chahiye.

#Ya phir, agar student ke paas "Sports Certificate" hai, toh attendance ki zaroorat nahi (Sirf marks 60+ kafi hain).
print ("Admission eligibility criteria :")
student_marks = int(input ("marks of the student : "))
attendance = int (input("student attendance : "))
sport_certificate=input("sort certificate answwer in yes or no : ")
if (student_marks <60 and attendance < 75) or sport_certificate=="yes":
   print("the student in pass in good marks congratulation")
else: 
   print("sorry best for next time ")
