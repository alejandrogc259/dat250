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





## Pending issues
I think there are no pending issues.
