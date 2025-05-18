# Python


# Python Analysis

This is work that I did in Python (on Google Colab) during my Data Technician Skills Bootcamp.
Project 1   FizzBuzz:

Go through the integers from 1 to 100.
If a number is divisible by 3, print "fizz."
If a number is divisible by 5, print "buzz."
If a number is both divisible by 3 and by 5, print "fizzbuzz."
Otherwise, print just the number.


for num in range(1, 101):
    if num % 3 == 0 and num % 5 == 0:
        print("fizzbuzz")
    elif num % 3 == 0:
        print("fizz")
    elif num % 5 == 0:
        print("buzz")
    else:
        print(num)
![Python1](https://github.com/user-attachments/assets/8212671b-c706-44bf-96bf-5c7a92d6a22f)

Project 2 - Working with a small dataset
This piece of work uses the dataset student.csv

Loading and Exploring Data 
[student.xlsx](https://github.com/user-attachments/files/20269965/student.xlsx)

1.	Question: "Write the code to read a CSV file into a Pandas DataFrame."
2.	Question: "Write the code to display the first 5 rows of the DataFrame."
3.	Question: "Write the code to get the information about the DataFrame."
4.	Question: "Write the code to get summary statistics for the DataFrame."

   .#csv_file = "student.csv"
pupil_df = pd.read_excel("student.xlsx")
#pupil_df.head()
print(f"Successfully loaded  into a DataFrame. Now let's explore it.")
2.  pupil_df.head(5)
![Screenshot 2025-05-18 012456](https://github.com/user-attachments/assets/c3720f4f-dcf5-4b8c-8864-85c9193d05f8)

3. pupil_df.info()
Output:
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 35 entries, 0 to 34
Data columns (total 5 columns):


4.pupil_df.describe()
![Screenshot 2025-05-18 012404](https://github.com/user-attachments/assets/ca5ef2e0-1434-4f27-8b34-0b96372bd1d9)

Exercise 2: Indexing and Slicing
1.	Question: "Write the code to select the 'name' column."
2.	Question: "Write the code to select the 'name' and 'mark' columns."
3.	Question: "Write the code to select the first 3 rows."
4.	Question: "Write the code to select all rows where the 'class' is 'Four'."


![image](https://github.com/user-attachments/assets/09c6ff24-6fa9-49d2-8ed8-5450fb07a7d7)


![image](https://github.com/user-attachments/assets/72da7e85-c92c-4d65-ad0e-b6e13ecaceaf)

![image](https://github.com/user-attachments/assets/2c9a2995-aef2-419d-b8aa-192a5c35b63f)


![image](https://github.com/user-attachments/assets/ad1cc213-51a0-464b-b157-4b49b24d0715)

Exercise 3: Data Manipulation
![image](https://github.com/user-attachments/assets/1df7fc6c-7830-4bce-b4bd-1348dfda0791)

![image](https://github.com/user-attachments/assets/2d0ff9ed-9e07-4ff9-a833-5289fb23999b)

![image](https://github.com/user-attachments/assets/fb96f14f-65f5-4020-943b-3f7e1fee758a)

Exercise 4: Aggregation and Grouping
1.	Question: "Write the code to group the DataFrame by the 'class' column and calculate the mean 'mark' for each group."
2.	Question: "Write the code to count the number of students in each class."
3.	Question: "Write the code to calculate the average mark for each gender."
![image](https://github.com/user-attachments/assets/cf55689a-ac34-4e2c-aa1f-b96cea04f460)
![image](https://github.com/user-attachments/assets/7fe0506c-f485-4413-ac8e-10a983884481)

![image](https://github.com/user-attachments/assets/e0b9a1d2-4044-4386-b6d0-b0f771e886d0)

Exercise 5: Advanced Operations


![image](https://github.com/user-attachments/assets/a5a88053-634f-4393-9274-8233aa9c85f2)

![image](https://github.com/user-attachments/assets/b0065394-5401-472b-a917-27176b7bd8b2)

![image](https://github.com/user-attachments/assets/7fc85b0f-c9f1-48f9-8b18-648e63647617)

Project Visualizing

![image](https://github.com/user-attachments/assets/6f14094f-cbb6-4cee-9bd6-da4de648ebad)


Project 3 - Open ended task working with a large dataset

This project used the dataset [GDP (nominal) per Capita.csv](https://github.com/user-attachments/files/20269997/GDP.nominal.per.Capita.csv)

![image](https://github.com/user-attachments/assets/664276fa-9b39-4328-aad1-ebe057424289)

![image](https://github.com/user-attachments/assets/54cbfe7e-ad82-4c2d-8f30-036414e30d01)

![image](https://github.com/user-attachments/assets/57165264-e8bf-4f9e-84ba-b4eee8c7c851)

![image](https://github.com/user-attachments/assets/c2fb64e2-09b9-4d20-b1f7-724ab81c3941)


![image](https://github.com/user-attachments/assets/795c9d48-159a-4c1c-a902-3a5b5312f659)

![image](https://github.com/user-attachments/assets/7e9628b5-4ecf-448d-bf3a-7e2cb604b242)

![image](https://github.com/user-attachments/assets/2434a971-9fb7-426f-b39d-0787356efeb7)

![image](https://github.com/user-attachments/assets/e7e0191b-b875-44bd-b765-3636906b8721)

![image](https://github.com/user-attachments/assets/fbb07da1-1c9d-4840-8bde-56d58ec24163)

![image](https://github.com/user-attachments/assets/cf035169-526e-4f0e-b981-77157431b8f3)
