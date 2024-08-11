# python-for-loop
#1
rows = 6
for i in range (1 , rows):
    num = 1
    for j in range (rows,0,-1):
        if j>i:
            print("",end='')
            num+=1
print("")

#2
a = 1
while a <= 10 :
    b = 1
    while b <= a:
        print('*',end = '')
        b+=1
    print()
    a+=1
rows = 6
for i in range (1 , rows):
    num = 1
    for j in range (rows,0,-1):
        if j>i:
            print("",end='')
            num+=1
print("")

#3
for item in range(5):
    print(item+1)

#4
students=['ram','sham','krishan','radha','radhika']
for student in students:
    if student=='krishan':
        continue;
    print(student)

#5
marks={95,98,97,97,97}
print(marks)
for score in marks:
    print(score)

    #6
    user_string = input("Enter a string: ")

max_count = 0
most_frequent_char = None

for char in user_string:
    count = 0
    for ch in user_string:
        
        if char == ch:
            count += 1
    if count > max_count:
        max_count = count
        most_frequent_char = char

if most_frequent_char:
    print(f"The most frequent character is '{most_frequent_char}'")
else:
    print("No characters in the string")
