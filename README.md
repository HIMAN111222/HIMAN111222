- 👋 Hi, I’m @HIMANSHU25d
- 👀 I’m interested in DSA, coding and web development
- 🌱 I’m currently learning DSA in C++
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
HIMAN111222/HIMAN111222 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
The provided code stub will read in a dictionary containing key/value pairs of name:[marks] for a list of students. Print the average of the marks array for the student name provided, showing 2 places after the decimal.

    if __name__ == '__main__':
        n = int(input())
        student_marks = {}
        for _ in range(n):
             name, *line = input().split()
             scores = list(map(float, line))
             student_marks[name] = scores
    query_name = input()
    if query_name in student_marks:
        sum = 0
        for i in student_marks[query_name]:
            sum = sum + i
            
    a=sum/len(student_marks[query_name])
    print("%.2f" % round(a, 2))
   
