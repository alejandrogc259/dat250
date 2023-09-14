# Report of the second assignment
## Technical problems
1. I was getting an error trying to visualize the database in IntelliJ and other programs, but then I realised that the version of h2 Driver was causing the error, so I looked in pom.xml and I downloaded the driver to make it work.
2. The test failed because I was using lists instead of sets. I changed it and it worked. Now it pass the test.

## Link to my code
https://github.com/alejandrogc259/dat250-jpa-tutorial

## How I inspected the database
I used IntelliJ Databases Tools and DBeaver. 

![image](https://github.com/alejandrogc259/dat250/assets/76476629/d8694953-2ca7-4235-814a-9863d4702aaa)
![image](https://github.com/alejandrogc259/dat250/assets/76476629/e38361e5-a2ef-4a35-9f3e-df8d6ae5d461)


The tables created are:
- One for each class (5)
- One for each many-to-many relations (2)

## Pending issues
I think there are no pending issues.

