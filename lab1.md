Name: Calvin Zhou\
Professor's Name: Joe Gibbs Politz\
Class: CSE 15l\
Date: 10-22-23

# Lab Report 1

1. ![Screenshot 2023-10-09 230515](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/85f62549-0e07-455b-a4a7-adbd78323a13)

The working directory is /home/lecture1
After entering the code, my working directory changed (can see from the bottom screenshot) This is because no arguments were inputted (so I think it basically sets it to /home (default?)). This is not an error.

2. ![Screenshot 2023-10-09 230533](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/079e5633-f618-4b4a-ac65-962c6e0e53c1)

![Screenshot 2023-10-09 230549](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/d68d412e-776c-4c11-abbf-0c3c65bdb6eb)

This time when I input lecture1 as my argument when using the cd command, my working directory became /home/lecture1 because the command changed my working directory. This is not an error either.

3. ![Screenshot 2023-10-09 230549](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/b6a2ea21-c657-4c12-a33f-577675ecd19f)


In this screenshot, I tried to change the directory into a file. This didn’t work and produced an error. I think it’s because the text files aren’t directories and the command ‘cd’ is only meant for directories.

4. ![Screenshot 2023-10-09 231148](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/38a3f95f-00fe-42af-a2e8-90cfc335bc23)

In this screenshot, I set the working directory to /home by not including any arguments in when using cd. What ls was able to was show list the folders in the path which is lecture1. Not an error.

5. ![Screenshot 2023-10-09 231155](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/4d5cac2f-7a01-4e74-a1ae-eaccd1f4df0f)

In this screenshot, I decided to test things out a bit by changing the directory which resulted in the working directory to be /home/lecture1. This time when I used the ls command, it displayed 4 different results as those are the files and folders contained in this path. No error.

6. ![Screenshot 2023-10-09 231202](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/594a608b-7816-486c-bd91-d6f1b9a9d762)

In this screenshot, I used the command ls on the folder messages, and it displayed 4 different results which are the files within messages. Working directory is /home/lecture1. No error.

7. ![Screenshot 2023-10-09 231239](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/863d07cb-705c-4778-872e-1047c3d0dcb8)

In this bonus screenshot, I used the cd command and inputted messages which change the working directory to /home/lecture1/messages. When I used the ls command on one of the text files, it listed itself as an output. I’m unsure if this is supposed to happen.

8. ![Screenshot 2023-10-09 231358](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/fdea3977-0052-412a-9d75-1ce090445844)

In this screenshot, I started off by changing the working directory back to /home. When I used the cat command, nothing happened as no arguments were being passed. Additionally, I also tried using the cat command when I changed my working directory from /home to /home/lecture1. I think an error asl occurs when I use 'cat' with no arguments and I input something on the command line. After I use 'cat with no arguments and input anything on the command line, it just coppies what I printed so it creates a copy of what I put. I'm unsure it why it does that, but I think it has to do with properties of cat.

9. ![Screenshot 2023-10-09 234512](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/e16934cd-aa55-4ed9-a89b-8299d464ba14)

In this screenshot, I used the cat command on both lecture1 and messages. Currently my working directory is /home. I think before I changed my current directory, I think the reason why lecture1 is a directory is because it was on the next path after /home. And when I changed the directory to lecture1 the same applied to messages. No error.

10. ![Screenshot 2023-10-09 234731](https://github.com/no-ire/cse15l-lab-reports/assets/146776005/3ece6234-d01d-4fcb-b930-af8223e61876)

In this example, I changed the current directory to messages so now my working directory is /home/lecture1/messages. This time in my arguments, it’s text files and when I used cat, it displayed what was in those text files which being Hello World in Thai and English. No error.
