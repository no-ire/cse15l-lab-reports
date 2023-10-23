Name: Calvin Zhou\
Professor's Name: Joe Gibbs Politz\
Class: CSE 15l\
Date: 10-22-23

# Lab Report 1

1. ![Screenshot 2023-10-09 230515](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/21373086-3bc0-4aba-8245-47be9b9d42a3)

The working directory is /home/lecture1
After entering the code, my working directory changed (can see from the bottom screenshot) This is because no arguments were inputted (so I think it basically sets it to /home (default?)). This is not an error.

2. ![Screenshot 2023-10-09 230533](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/d800510a-8836-478a-9f53-3a06ed9c77d7)
![Screenshot 2023-10-09 230549](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/f1847289-5e82-4d0a-802b-a1848f20e657)


This time when I input lecture1 as my argument when using the cd command, my working directory became /home/lecture1 because the command changed my working directory. This is not an error either.

3. ![Screenshot 2023-10-09 230549](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/6e792b6c-c489-4ca3-a569-35152123998a)

In this screenshot, I tried to change the directory into a file. This didn’t work and produced an error. I think it’s because the text files aren’t directories and the command ‘cd’ is only meant for directories.

4. ![Screenshot 2023-10-09 231148](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/2a4ac615-a937-449d-849e-86b7452864a1)

In this screenshot, I set the working directory to /home by not including any arguments in when using cd. What ls was able to was show list the folders in the path which is lecture1. Not an error.

5. ![Screenshot 2023-10-09 231155](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/b9abafe5-9482-4843-a25f-4e286f0e5060)

In this screenshot, I decided to test things out a bit by changing the directory which resulted in the working directory to be /home/lecture1. This time when I used the ls command, it displayed 4 different results as those are the files and folders contained in this path. No error.

6. ![Screenshot 2023-10-09 231202](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/a13cc9ef-8bb6-47f5-94f5-e99ae8414a11)

In this screenshot, I used the command ls on the folder messages, and it displayed 4 different results which are the files within messages. Working directory is /home/lecture1. No error.

7. ![Screenshot 2023-10-09 231239](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/bcb59724-5c6c-4d5d-88e4-efbc61319b91)

In this bonus screenshot, I used the cd command and inputted messages which change the working directory to /home/lecture1/messages. When I used the ls command on one of the text files, it listed itself as an output. I’m unsure if this is supposed to happen.

8. ![Screenshot 2023-10-09 231358](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/d8fbe3bf-76cd-42e8-8397-b532e06b80c7)

In this screenshot, I started off by changing the working directory back to /home. When I used the cat command, nothing happened as no arguments were being passed. Additionally, I also tried using the cat command when I changed my working directory from /home to /home/lecture1. I think an error asl occurs when I use 'cat' with no arguments and I input something on the command line. After I use 'cat with no arguments and input anything on the command line, it just coppies what I printed so it creates a copy of what I put. I'm unsure it why it does that, but I think it has to do with properties of cat.

9. ![Screenshot 2023-10-09 234512](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/b82a5dd9-7c31-42e7-bdb4-613356523e31)

In this screenshot, I used the cat command on both lecture1 and messages. Currently my working directory is /home. I think before I changed my current directory, I think the reason why lecture1 is a directory is because it was on the next path after /home. And when I changed the directory to lecture1 the same applied to messages. No error.

10. ![Screenshot 2023-10-09 234731](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/9b04d25e-a5f8-46c9-b5fc-9ba96ed5d531)

In this example, I changed the current directory to messages so now my working directory is /home/lecture1/messages. This time in my arguments, it’s text files and when I used cat, it displayed what was in those text files which being Hello World in Thai and English. No error.
