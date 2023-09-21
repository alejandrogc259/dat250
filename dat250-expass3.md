# Report of the third assignment
## Technical problems
1. I have an error trying to install MongoDB because I have Ubuntu 22.04 and the tutorial last version is 20.04. I searched on the Internet and found that I had to install a dependency called libssl1.1. I ran these commands and it worked:
   - echo "deb http://security.ubuntu.com/ubuntu focal-security main" | sudo tee /etc/apt/sources.list.d/focal-security.list
   - sudo apt-get update
   - sudo apt-get install libssl1.1

## Screenshots
Validation:

![imagen](https://github.com/alejandrogc259/dat250/assets/76476629/8254306f-73c3-4869-9f81-a94b7fb330ea)

Experiment 1:
  
  Insert one
  
   ![imagen](https://github.com/alejandrogc259/dat250/assets/76476629/eddf59e5-8a1f-4896-a927-302ec62f7154)

  Query
  
   ![imagen](https://github.com/alejandrogc259/dat250/assets/76476629/46e432f4-aa61-4dc0-961d-fa0a07a89849)

  Update
  
   ![imagen](https://github.com/alejandrogc259/dat250/assets/76476629/baaa551b-2717-4322-8f89-90ace969a516)

  Delete
  
   ![imagen](https://github.com/alejandrogc259/dat250/assets/76476629/2e172e49-fa11-4319-b5b7-17cfbaadb59a)

  BulkWrite Operations
  
   ![imagen](https://github.com/alejandrogc259/dat250/assets/76476629/bff65c00-b443-4539-bf8e-9b2ef175c8f2)

Experiment 2:

![imagen](https://github.com/alejandrogc259/dat250/assets/76476629/c6ce2b8c-dfb8-441a-9d25-3ed8db763bc9)

My functions:

![imagen](https://github.com/alejandrogc259/dat250/assets/76476629/07463e43-6e92-47a4-b850-0c618883dfef)
![imagen](https://github.com/alejandrogc259/dat250/assets/76476629/ddbbe563-d1a8-45e1-b7e8-38c3931ef14a)
![imagen](https://github.com/alejandrogc259/dat250/assets/76476629/55cc5a31-df65-4841-bddc-c6efe0ad5432)
![imagen](https://github.com/alejandrogc259/dat250/assets/76476629/eb65dc04-83cb-41f4-99e1-74ea727d628f)

I think my operation is useful because it returns the average number of days it takes for a customer to buy again and that could be helpful for the shop analysis.
We can see that Cam Elot is the most frequent buyer, but we would need more data to analyze this properly.

## Pending issues
I think there are no pending issues.
