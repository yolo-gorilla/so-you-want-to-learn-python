## 03 The Basics 
## Learn the basic building blocks of the python programing language

### Hello world

The hello world program is a simple program that only does one thing, It prints out "Hello world". It is great for beginers to learn how to run a program when learning a new language. 

create a new file called hello.py in yyour code editor. Then insert the following into the file:

```
print("Hello, World!")
```
Make sure to save the file. In a terminal inside the same directory as your file run the following command to run your program:

```
python hello.py
```

You should see the following output:
![image](https://user-images.githubusercontent.com/69941161/175075934-8891aa3a-9abd-47e5-add4-e754aac17bf2.png)

*Please note the author's setup required the running of python as "python3". Your setup might differ depending on how python was installed.*


Congratulations you just ran your first python program. That was easy right? 

Let's walk through what is happening under the hood. This is often skipped over by most courses and tutorials. 
### The extra stuff you don't need to know

Your terminal (The black screen with white text) is a very direct way of working on your computer. 
In the hello world example, you ran "python" as the program that was executing with "hello.py" as the parameter. 

This is because python is an interpreted language. This means that it requires a program to convert your program into actual machine code (think 1s and 0s) on the fly.
The python binary is passed the name of the file to run "hello.py". This is then converted to machine code and executed in your computers memory. 

When running scripts directly from the terminal as such, you need to make sure you are in the same directory as the scripts you are trying to run.
We will get more in depth on the filesystem on later parts of this course. 



