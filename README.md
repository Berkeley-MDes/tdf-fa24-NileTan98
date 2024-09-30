# TDF Weekly Report

## Week 5 Report

The first file I compiled was 01_helloworld.cpp, because Jeff went through this one in class and I had some familiarity with it.

<img width="1206" alt="Screenshot 2024-09-29 at 10 15 54 PM" src="https://github.com/user-attachments/assets/c76d2fdb-64ff-4c42-a180-7a8aa81162e9">

The second file I compiled was 02_helloworld_spell.cpp because it builts on the first file, and also because I failed to compile this one in class.

<img width="1505" alt="Screenshot 2024-09-29 at 11 21 57 PM" src="https://github.com/user-attachments/assets/2bd6c8f7-7606-48ff-b8f0-9bcbdf1b93c5">

After examining this file and the one I hastily tried to type down, I realized where my error was:

<img width="791" alt="Screenshot 2024-09-29 at 11 25 52 PM" src="https://github.com/user-attachments/assets/5de4b81c-712e-40ea-976c-772daa52ee69">

For line 39, I wrote "Log.info("current character: %c", hello(count))" instead of "hello [count]", which led to an error message.

However, even now I've realized where my mistake lies, due to my lack of coding knowledge, I still don't know the difference between hello(count) and hello[count]. I wish the future classes would delve more into the coding aspect of things.

The last file I tried was 04_make_it_blink.cpp, I was really happy that I got my photon to flash:

https://github.com/user-attachments/assets/c2826acc-8541-4877-9477-167c0cf18be9

I was even happier that after I adjusted the delay speed from delay(100) to delay(1000), I saw the blink speed significantly slowed down:

https://github.com/user-attachments/assets/3abce062-e404-49a0-991d-1c341b09d588

Even though it's a pretty basic adjustment and I didn't get to the physical connection aspect of thing. I'm happy that I'm following and understanding the script.

## Week 4 Report
In this week's class we delved into Photon, which is yet again somethig I'm completely unfamiliar with.

I've used Arduino before but this seems more complex and requires much more hardcore coding.

I tried to follow the lecture, but was completely lost during the coding section.

I decided to analyze the workflow of an ATM machine and how we interact with it, because (**speculation** here) I feel like as cashless payment and digital transcation becomes more and more prevelant, physical ATM machines will gradually become obsolete, or they will be in dire need of update and evolution.

A Google search proves my instinct to be correct: https://www.paymentsdive.com/news/atms-dwindle-for-third-straight-year/653645/

<img width="862" alt="Screenshot 2024-09-26 at 2 45 11 PM" src="https://github.com/user-attachments/assets/3a2a9944-8336-4b8f-b9db-01bbaa640c16">

Anyhow, here's the workflow diagram of a user interacting with an ATM machines as of today:

![output (1)](https://github.com/user-attachments/assets/499434d3-31cf-4dfc-b90b-705b33391b3a)


## Week 3 Report

This week, I've finished my cellphone stand!!

<img width="613" alt="Screenshot 2024-09-19 at 1 59 16 PM" src="https://github.com/user-attachments/assets/344927be-1991-4c9b-8347-0c437b5a4cec">

Considering I've never done any 3D modeling and printing in my life. I'm very proud of the end result.

This was the second attempt for me. At first, I printed a rectangular stand:

<img width="1051" alt="Screenshot 2024-09-19 at 1 59 25 PM" src="https://github.com/user-attachments/assets/8b51695b-f339-4c10-b67a-873ef8b3c7e6">

However, the ditch to place the cellphone in was too wide, because I forgot to adjust the parameters to my own cellphone.

Also, I didn't like how bulky the stand was. I wanted to make something smaller, lighter and economical, so I reshaped the stand to be triangular.

Here is the comparison between the two stands:

<img width="979" alt="Screenshot 2024-09-19 at 1 59 35 PM" src="https://github.com/user-attachments/assets/19a7f6eb-45da-455b-9cd2-39cc86d905ad">

You can see how I got there via Grasshopper:

<img width="1185" alt="Screenshot 2024-09-19 at 1 48 41 PM" src="https://github.com/user-attachments/assets/fb4f7513-3a46-49f7-8f33-a89777affea8">

You can also learn more about my process through this Youtube video:

[![Everything Is AWESOME](https://img.youtube.com/vi/3iBHLhVDQ1U/0.jpg)](https://youtu.be/3iBHLhVDQ1U "Everything Is AWESOME")

Speculation: I really like how automated and parametric Grasshopper is. I feel like it lays groundwork for people who aren't from a visual background or know how to draw to build a 3D model in a convenient and effective manner.

## Week 2 Report
Here's my understanding of how to use Grasshopper to create a cellphone stand. It starts with setting up the parameters, then we go on to make two separate things:
1. a cellphone
2. a stand

The cellphone is basically a cylinder and the stand is created through creating a sphere, and then subtracting a smaller sphere to create walls, then subtract a cylinder to make space for the cellphone.

<img width="994" alt="Screenshot 2024-09-09 at 2 39 44 PM" src="https://github.com/user-attachments/assets/ba30447b-8b66-4b1a-830d-f960605051a4">

To mess with the parameters and dimensions of the stand, I first adjusted the radius of the two spheres:

<img width="646" alt="Screenshot 2024-09-09 at 2 46 22 PM" src="https://github.com/user-attachments/assets/403caa48-a957-4476-b549-73021a13f92e">

Then, I tried to replace the cylinder with a cone:

<img width="931" alt="Screenshot 2024-09-09 at 2 48 09 PM" src="https://github.com/user-attachments/assets/0b453e75-95a5-4bc6-95de-f3a2f8558035">

It was very cool to see how easily I can reshape the design with very simple instructions. However, I can't manage to make the end result stay "green." Some errors always occured when I tried to play with the parameters.

Lastly, I tried to replicate TJ's demo during Monday's class and create a box with a hallowed cylinder inside:

<img width="1136" alt="Screenshot 2024-09-11 at 5 37 53 PM" src="https://github.com/user-attachments/assets/0d95cd25-8098-4445-aa77-9071d65ced4f">

Here is the Grasshooper commands I used to achieve the modeling above:

<img width="1025" alt="Screenshot 2024-09-11 at 5 34 28 PM" src="https://github.com/user-attachments/assets/b226be69-85af-4c96-9339-86311cafb6d9">

I'm somewhat happy with the end result as it was the first thing I ever created via Grasshopper. I feel like I'm starting to get a hang of it thought process behind how Grasshopper works.

Speculation: I was introduced to Adam, an AI text-to-3D tool. I feel like as tools similiar to Adam invovle, 3D modeling will become more accessible to public.

## Week 1 Report
For this past week, I've started using Github for the first time. I've also started learning Rhino from beginning.

It's daunting to learn Rhino and can't say I fully understand how it works, but I'm also excited :)

<img width="1428" alt="Screenshot 2024-09-05 at 4 49 09 PM" src="https://github.com/user-attachments/assets/fbea8258-23ba-4cc6-81ee-3506904275b4">

I was able to make something simple in GH by the end of the week, so I consider it a major achievement:

<img width="1250" alt="Screenshot 2024-09-18 at 5 32 14 PM" src="https://github.com/user-attachments/assets/e2bbc038-2833-4e4a-8b1b-483ac51108c5">

Speculation: I wonder after Grasshopper, how will Rhino invovle. What's the future for CAD tools?

--- 
PPS: 
## Quick Links, compiled here for your convenience: ##

- [TDF Wiki](https://github.com/Berkeley-MDes/desinv-202/wiki) - the ultimate source for truth and information about the course and assignments
- [Google Drive Folder](https://drive.google.com/drive/folders/1OjFgu4llHn-2WayQFVWRKFyOkQ_WaQRx?usp=drive_link) - slides and other resources
- [bCourses](https://bcourses.berkeley.edu/courses/1528355) - where the grading happens
