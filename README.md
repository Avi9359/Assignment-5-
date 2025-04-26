# Assignment-5-
# TASK 1
students ={
    "Alice":85
}
student_name = input('enter the student name:')

if student_name in students:
    print(f"{student_name}'s marks: {students[student_name]}")
else:
    print("student not found.")
    

# TASK 2
original_list = [1,2,3,4,5,6,7,8,9,10]
extracted_list = original_list[:5]
reversed_list = extracted_list[::-1]

print("original list:", original_list )
print("Extracted first five element:", extracted_list)
print("Reversed extracted elements:", reversed_list)
