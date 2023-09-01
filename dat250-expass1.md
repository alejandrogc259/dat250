# Report of the first assignment
## Technical problems
1. I have not understand how tags work in Docker. I have been 2 hours trying to push the image and finally I did it but I did not see how it really works.
2. To check if it was working fine I had to do like a port tunneling or something like that. I don't really get it but this command worked for me (docker run -p 127.0.0.1:9000:9000 unitconverter).
Using it I can access via localhost:9000 when running the App.
3. I had to change ' for " in the Dockerfile file to make it work.
4. The command "push" is a bit different than the one in the guide.
5. To disable the message "Javalin: It looks like you don't have a logger in your project." I searched on the internet and I found that it could be solved by adding a dependency called slf4j-simple.
This is the code I paste into build.gradle.kts: "implementation("org.slf4j:slf4j-simple:2.0.7")".

## How to validate everything is working
I ran the project in IntelliJ Idea and it worked fine, also with gradlew. The "docker run" command works too, as I said before. I also checked if the tests were working and they worked fine. When 
a test failed (on purpose) gradlew did not let me build the project.

## Pending issues
I think there are no pending issues.


URL of DockerHub: https://hub.docker.com/r/alejandrogc259/dat250
