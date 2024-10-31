# TDF Weekly Report

## Week 9 Report
This week, we've started learning LLM, which is very new & exciting and feels very topical.

TJ's tutorial is very detailed and helpful. Here's my attempt at **Experiment 1**:

<img width="1396" alt="Screenshot 2024-10-31 at 12 42 40 PM" src="https://github.com/user-attachments/assets/3b0b16f7-c20f-423a-83d8-2c59df766ad9">

Here's my **experiment 2**. For fun, I asked ChatGPT to answer questions from the perspective of George Washington:

<img width="1452" alt="Screenshot 2024-10-31 at 1 09 08 PM" src="https://github.com/user-attachments/assets/d719cb4d-a87b-4ba7-8880-474c2e3893e7">

**Reflection**: Reflecting on the progress of this week, I gained significant confidence in navigating prompt engineering, further refining my understanding of how LLMs interpret context. This initial success fosters curiosity for future projects, particularly in exploring the breadth of personalized AI responses for interaction design.

**Speculation**: The future of design will likely be profoundly influenced by the evolution of designing for LLM platforms, where traditional interface design will shift towards crafting adaptive conversational flows, dynamic content generation, and personalized user interactions. Designing LLM platforms will require thinking beyond static layouts and usability principles, focusing instead on developing intuitive user experiences that leverage real-time learning, context-awareness, and multimodal inputs.

Case in point: OpenAI is considering voice interaction to ChatGPT. The future of design will be on making design platforms like ChatGPT easiler to use. Users will design and generate their own contents on these platforms.
https://www.91mobiles.com/hub/open-ai-chatgpt-voice-feature-launched/




## Week 8 Report

The biggest achievement of the week was definitely finishing Project 2, which you can watch the video here:

https://youtu.be/SZh687QCjRw

![IMG_5835](https://github.com/user-attachments/assets/01136b14-09b2-4713-baf4-b480cebb76c0)

We are very happy with the way the project has turned down. It definitely achieved our originial conception, as presented in the diagram here:

![WechatIMG444](https://github.com/user-attachments/assets/0463f6a4-76ca-44e8-b2b2-ae3c0cc3753f)

For **speculation**, I believe there's a wider scope of application of how the Lumia project can be used. This is what we wrote in our report video:

"Imagine Lumia not just as a museum installation, but as a transformative technology that can reshape how we experience spaces. Picture public spaces where architecture comes alive with the flow of people, retail environments that create personalized shopping experiences, or therapy rooms where light and sound work together to aid rehabilitation.

The possibilities extend from corporate lobbies to theme park queues, from meditation spaces to interactive stage designs – anywhere human interaction can be enhanced through responsive environments. In conclusion, Lumia isn't just an art installation; it's a platform for reimagining how we interact with our surroundings."

I hope this project can be something we continually work towards in my journey at MDes.


## Week 7 Report

This week, my teammate Xiao & I delved into our project. 

It's very cool being able to employ what we learned in the previous weeks into practice. We used the **gyro accelerometer** as well as the **potentiometer** in our kit as two of the inputs. 

We have also established cloud connections between two Photon Particles for the first time:

![WechatIMG400](https://github.com/user-attachments/assets/5a4ae9db-bfc3-4592-9fcb-87757de8fded)

https://github.com/user-attachments/assets/a81ce496-364f-4f19-ac63-743a7ce7ae46

The cloud connection was very cool, remotely controlling another Photon feels like magic to me. However, we also quickly discovered the downside of cloud as well: the wifi can be unstable and the Photons would randomly go offline. There's not much we can do in this situation other than waiting for the Photons to go back online.

We also tried out Neopixel for the first time. Neopixel looks so much cooler than a regular LED lightbulb but also more complicated to use.

The neopixel library in VS Code turned out to be very problematic. The code always fails to run despite the library being added and the neopixel colors wouldn't change, or even light up on command.

![4031729210514_ pic](https://github.com/user-attachments/assets/2a458299-fd49-43f0-a7b6-2ddbce2b5159)

![4011729210512_ pic_hd](https://github.com/user-attachments/assets/9148c101-05c9-407c-9a2d-fb3e93511333)

Still, I feel like our team is making major progresses and learning so much new things in the process.

**Speculation:** I feel like the cloud function is highly useful in that it can remotely share data and therefore control other Photons. This way, we can truly build an ecosystem, instead of a singular device that's constrained by the physical space. However, I feel the current cloud storage limits its potential usage. If we have large enough cloud storage space, Photons can become a truly powerful tool for interactive design. 

![output (2)](https://github.com/user-attachments/assets/85cb6292-90cc-450f-8ba0-2b975f1afaa1)


## Week 6 Report

I just did soldering for the first time in my life!!

![IMG_5525](https://github.com/user-attachments/assets/b9c37924-9ddd-42b3-a3b1-df532d0514c5)

And I was able to successfully connect APDS9960 & compile. It's interesting to see how the mointor change values as I play around with the sensor.

https://github.com/user-attachments/assets/20d93fdb-892c-47c6-885f-08a79e78505d

I was also able to successfully connect MPU6050 & compile. However, this time I'm not entirely sure what the data means:

<img width="649" alt="Screenshot 2024-10-07 at 1 19 22 PM" src="https://github.com/user-attachments/assets/608cd25d-bcb0-4a03-9f11-7c08ff54b770">

This week, I've also paired with Peng Xiao to do our Project 2.

Here are the diagrams explaining our proposed project, **Lumia**:

![A4 - 1](https://github.com/user-attachments/assets/12fc9bfd-9e53-425e-a247-3507828314d6)

![Frame 3](https://github.com/user-attachments/assets/8374fc5b-2405-4240-98f2-5c9f2fa8efac)

**Speculation**:

I feel like Photon is very useful for dynamic interactions in a project like Lumia. I could use the Photon to collect sensor data, such as proximity, temperature, or motion, and trigger a wide range of outputs like sound, light, or even digital displays. This could create fully immersive and reactive environments where the audience becomes an integral part of the artwork. For example, n our project, as people move, the Photon could adjust lighting intensity and colors or play different sound compositions based on sensor inputs. I want to explore what more Photon can do to make art come alive.

## Week 5 Report - Part 2

1. The first tutorial I did was **Button -> LED pulse rate**, and it worked on the 1st try

https://github.com/user-attachments/assets/4d6a2d58-968a-42be-8f0a-2dd44ba5431e

At first, I didn't put in the resistor and the light was too bright. Now I know the importance of resistor.

2. The second tutorial I did was **basic button send-on-change example**

![IMG_5403](https://github.com/user-attachments/assets/7657cace-9489-453d-bc9f-a4bb318fac2a)

At first I was worried because there's no visible action happening to Photon after I connected the pieces, but I was relieved when I saw that the Particle Console recorded my button actions:

<img width="682" alt="Screenshot 2024-10-03 at 1 00 33 PM" src="https://github.com/user-attachments/assets/2340c81a-15c6-4fb3-a94d-0c084ba9dc7c">

3. The third tutorial **fsr (force sensitive resistor) -> RGB-led color fader** is by far my favorite, because it feels highly interactive and I can change the LED colors with my fingers.

https://github.com/user-attachments/assets/bd651c06-291f-4be5-9ff4-98d5418528a3

At first, I ran into an issue: no matter how hard I pressed, there's only one color.

With the help of Chris at Makerspace, we were able to find the problem after countless tries of troubleshoots: I didn't use the right resistor. The resistor was blocking too much voltage. After switching resistors, I was able to change colors basing on pressure levels.

https://github.com/user-attachments/assets/641b6e3b-fb0a-43e7-975e-3a0bb3b96d6a

**Reflection** 

I think these projects are more dynamic than earlier projects because it uses analog inputs buttons and sensors, which make the output more interactive. It still has that "input to output" structure, but with added complexity.

A cool expansion could be adding notifications—like getting an alert if the FSR senses too much pressure for too long, which could help me adjust my posture. Adding Machine Learning could let the system recognize different pressure patterns, making it even smarter.

**Speculation**

Combining this with other projects, I imagine Machining Learn can be used to adapt a smart workspace that adapts to my habits—sensors tracking my activity, adjusting lighting, and sending helpful reminders—all working together to boost comfort and productivity.


## Week 5 Report - Part 1

1. The first file I compiled was 01_helloworld.cpp, because Jeff went through this one in class and I had some familiarity with it.

<img width="1206" alt="Screenshot 2024-09-29 at 10 15 54 PM" src="https://github.com/user-attachments/assets/c76d2fdb-64ff-4c42-a180-7a8aa81162e9">

2. The second file I compiled was 02_helloworld_spell.cpp because it builts on the first file, and also because I failed to compile this one in class.

<img width="1505" alt="Screenshot 2024-09-29 at 11 21 57 PM" src="https://github.com/user-attachments/assets/2bd6c8f7-7606-48ff-b8f0-9bcbdf1b93c5">

After examining this file and the one I hastily tried to type down, I realized where my error was:

<img width="791" alt="Screenshot 2024-09-29 at 11 25 52 PM" src="https://github.com/user-attachments/assets/5de4b81c-712e-40ea-976c-772daa52ee69">

For line 39, I wrote "Log.info("current character: %c", hello(count))" instead of "hello [count]", which led to an error message.

However, even now I've realized where my mistake lies, due to my lack of coding knowledge, I still don't know the difference between hello(count) and hello[count]. I wish the future classes would delve more into the coding aspect of things.

3. The last file I tried was 04_make_it_blink.cpp, I was really happy that I got my photon to flash:

https://github.com/user-attachments/assets/c2826acc-8541-4877-9477-167c0cf18be9

I was even happier that after I adjusted the delay speed from delay(100) to delay(1000), I saw the blink speed significantly slowed down:

https://github.com/user-attachments/assets/3abce062-e404-49a0-991d-1c341b09d588

Even though it's a pretty basic adjustment and I didn't get to the physical connection aspect of thing. I'm happy that I'm following and understanding the script.

**Thoughts:**

I've found Photon really useful for building connected projects. It combines timing control, variables, outputs, and cloud integration, making it a pretty cohesive system for prototyping IoT ideas.

The Particle Cloud is a game-changer because I can send that data to the Particle Cloud to monitor everything remotely. Compared to something like an Arduino, it’s awesome that the Wi-Fi and cloud features are built-in, which makes developing and scaling connected projects much easier.

Overall, it’s been a great tool for prototyping, learning about IoT, and seeing my ideas come to life without too much hassle.

Thinking about the kinds of ecosystems that are missing in my daily life, I realize there are a few areas where things could be more connected and intuitive. For instance, I'd love to have a more cohesive home automation system. Right now, my lights, thermostat, and other smart devices work independently, but having a centralized system that learns my habits and automatically adjusts everything for comfort would be amazing.

Going back to the ATM system I mentioned last week, I can see how some of the pieces of the Photon ecosystem could relate to an ATM system.

In an ATM system, timing is critical—things need to happen in a certain order for the experience to be seamless and secure. Just like I use timers to control when sensors activate or when data is pushed to the cloud, an ATM must time its interactions precisely, such as waiting for a PIN entry before allowing a withdrawal.

The concept of variables is also relevant. In my Photon projects, I store sensor values and states as variables. Similarly, an ATM system relies on variables for tracking user information, account balances, and session data. These variables have to be monitored and updated dynamically as users interact with the system.

Outputs, such as LEDs or notifications, are another connection. On the Photon, I use LEDs to signal status, like indicating when a process is complete. In an ATM, status indicators are used to guide users, like showing when a card is being read, if there’s an error, or when cash is ready to be dispensed.

Finally, remote integration via the Particle Cloud is a lot like the way ATMs connect to banking networks. The Photon uses the cloud to communicate with external devices or log data, while an ATM connects to a bank’s servers to verify account details, log transactions, and provide real-time updates. This remote communication ensures everything is synced and functioning as expected, just like in an IoT project.

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
