# Build-a-daily-task-scheduler-application-using-Amazon-PartyRock
![image](https://github.com/user-attachments/assets/8c9e6b10-4b73-4b9e-a1ec-c8d03ed266ff)




## Overview of Project ☁️

In this first project, we'll be using [PartyRock](https://partyrock.aws/) to develop a 'Daily Task Scheduler Application' aimed at enhancing our productivity and organization. 

For those not familiar with PartyRock, it's a platform offered by AWS designed to simplify app development through the use of **generative AI**. I've had a lot of fun playing around with PartyRock recently, so I hope you'll also enjoy building this project.

**Steps to be performed 👩‍💻**
In the next few lessons, we'll be going through the following steps.

1. Generating the daily task scheduler application
2. Changes in existing widgets
3. Adding new widgets
4. Publishing your app

**Services Used 🛠**
AWS PartyRock: A fun playground offered by AWS to build applications with generative AI. It helps you make your own apps with AI, without having any coding experience.

**Estimated Time & Cost ⚙️**
This project is estimated to take about 15-20 minutes
Cost: Free (For a limited time, AWS offers new PartyRock users a free trial)



**➡️ Diagram**
This is the homepage of [PartyRock](https://partyrock.aws/):
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/tnc4cp0h21gawfp22uh8.png)




**➡️ Final Result**
This is what your project will look like, once built:

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/zsz2onz5wyb76biu0k4m.png)








## Getting Started with PartyRock

**What is PartyRock?**
PartyRock (powered by Amazon Bedrock), is a fun and intuitive hands-on, generative AI app-building playground. In just a few steps, you can create a variety of apps to experiment with generative AI.

**It helps you make your own apps with AI, without having to code.** You don't need to be developer to be able to start creating your own applications with PartyRock.

PartyRock is built on the belief that all builders should have access to a fun and intuitive tool to get started building with generative AI and be able to share the apps they create. With just a few easy steps, you can make all sorts of applications.

Building and experimenting with PartyRock, offers a unique opportunity to understand how AI operates and how to harness its capabilities effectively. You can try out various types of AI models, and learn how to get better at asking generative AI prompts.

**Use cases**
You could create an application that tells funny dad jokes about any topic you pick. Or maybe you want an application that makes a special playlist with tailored sound tracks. You could even build one that helps you decide what to cook, based on what you have in your kitchen.



**How to Get Started**

1.Visit the website : https://partyrock.aws/

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/d2fo1v33d7zw0fxv0ud5.png)

2.Create your first application by clicking on "**Generate app**".

3.Describe what you would like the app to do. Let’s go for something fun here!

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/rt0elvxh9swnd7s8yrjh.png)




4.Click the "play" icon below or `ctrl` + `enter`, get some snacks and let PartyRock do the work for you!

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/6hzv8d9waweg4r39eldl.png)




5.By scrolling down below we can see the creative image description of our prompt and the generated AI image of our Potato, named "John" climbing Mount Everest!

_Image Description_
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/949xx8gd29olxpggk0ks.png)



_Generate Image_
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/b05e9e1hd01bqf33vrgd.png)




6.If not satisfied with the first prompt, you may recreate the current image by clicking the "replay" button below or `ctrl `+ `enter`. 

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/2zn7hdegubc02p6ahisp.png)



7.With that, we just created an application without any coding pre-requisites, using prompt engineering in less than 5 minutes!


8.We can also **remix** applications created by others to have a copy and change it according to our preference by clicking on the "_Remix_" button present on the top right of the application page.








## Generating the daily task scheduler application

1.Let’s start with building a task scheduler application. Navigate to AWS [PartyRock](https://partyrock.aws/) on you web browser or through this link `https://partyrock.aws/`


2.Click on "Generate app" and enter an appropriate prompt. For this example, let's try `Generate a daily task scheduler` then click "_Generate_" and wait for PartyRock to do the work for you!
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/bkr15a4wa2whhkd96zxs.png)





3.PartyRock generated an application which takes tasks to be done as an input, gives the schedule according to priorities, and even provides a chatbot to refine your schedule!
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/q7wchcax539cbrn06r1u.png)






## Modify existing widgets
In the this step, let’s try modifying the existing components to be more specific. Game? GAME!

1.You can organize the blocks present by clicking and dragging the bottom right corner of the block to restructure them.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ywjhqxm9w3wsrihn5vhy.png)






2.You can edit your widget by clicking on the Edit option in the top right corner. 

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/pofy48y4opbo44ykduug.png)







3.Here in the Edit section of "_Generated Schedule_" widget, you have multiple models available. You can use one of these models to generate your outputs based on how well generated you want your output. 

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/tn39qi3g8za27t2g7022.png)


Lets see a comparison:

**Claude 3.5 Sonnet**
_In this model, Claude 3.5 Sonnet gave a detailed daily schedule based on the information I provided._

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/yo3d8cyukq33pdg0f8sl.png)




**Claude 3 Haiku**
_In comparison with this model, it generated a more concise and compacted answer._
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/bynwfqeocxrdcymmfklk.png)




The "_prompt_" section from Edit Schedule tab is used to provide prompt to the model on which the output is generated. We can reference a widget using @widget_name in the prompt.







## Adding new widgets
Let's try adding some more widgets and further customize the application!

1.Let’s try to add a time widget that takes the approximate time required for each task.

2.Click on "_Add Widget_" on the top left of your screen to add a widget.
You may choose a different type of widget depending on your future needs but in this scenario, let's choose "_user input_" widget. 
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4gz6v5z8m0g2xlnyn57e.png)





3.Then, change the name and add a placeholder of your new widget.
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ryaqqbmoql26m6f03qqy.png)





4.In our "_Generated Schedule_" AI widget, let's add the input of our new widget "_Time_" to prepare an updated schedule by typing `@Time`. You can change the prompt to enter the time required for each task.
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/odciz48aanfplvpblgl0.png)





5.Click on Save and check your new schedule.
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ifmlrrefu24rjrniw4t2.png)





6.Let’s also add a motivational quote widget to generate a motivational quote and a photo generator to generate a motivational image and get you kickstarted with your day.

_Add a text generation widget and label it as Motivational Quote, you may freely choose which model you can use for your new AI widget_
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/vmxk7rtarcugoryc32qp.png)





_Add an image generation widget and label it as Motivational Image, make sure that to customize the prompt by pressing @ to reference it on our text generation Motivational Quote Widget_
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4kvvkabfcq473sr0b7as.png)
So coooool right? 





7.You can try adding or changing the widgets according to your own imagination. Once, you're done, click the "_Leave Edit_" on the top right corner. Remember to be creative and have fun doing it! 
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/h8av5s6ugs7xcqlpxofx.png)







## Publishing your application
Great work with creating your application. PartyRock doesn't stop here, you can even publish your app for others to use it!


1.Click on "_Share_" button present on the top right corner of the website. Click "_Public_" then ** Make app public**. 
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/cv396oylyxusnjxh6uaw.png)




Anyone with this link can see, use or remix your application.

Here is my Daily Task Scheduler application: https://partyrock.aws/u/papercut/dHtxEnA6y/Daily-Task-Scheduler








## Importance of a detailed prompt

**Prompt engineering** is one of the important aspects when it comes to using PartyRock. We need to keep our prompts detailed and clear to get the maximum results as per our requirement.

Let’s take an example:

In the previous steps we generated an application of a daily task scheduler using the prompt given below:
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/m2sl7j49eey7yse29bgg.png)




And we got a generated app with tasks as input, scheduler and a chatbot for optimization.
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/sx8gecox0avdarrgeto8.png)






We performed a few steps and customization to optimize the application with the final output as:
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/lqm5yue3asp6ds70xyh2.png)





However if you try making the prompt more detailed and precise:
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/cipgm79xu1jrxu4tpdaz.png)






We got the same application as our previous final output without performing any modifications! 
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/mmb6dduhecklonbda40t.png)

With all the time that was spent on the modifications instead of directly getting the final result from a proper prompt, was hopefully enough to explain the importance of prompt engineering!







## Clean-up
Delete your application by navigating to "Apps" in the left section of the page and click on the _trash icon_ confirming deletion your application.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/1ixuqunmvp4ssxcnlrvo.png)



"_is it important that I delete the app?_"
Not needed for this application! **Since PartyRock is separate from the rest of the AWS Console services, and a credit card is not needed at sign-up**. So it is really up to you whether you want to keep your application for future usage.






## Conclusion
Congratulations on completing your first project in this course. Through this project, you've gained first-hand experience in using PartyRock to create a 'Daily Task Scheduler Application'.

I'd encourage you to continue on with the other projects in this course. The difficulty of the projects will slowly ramp up, but don't worry - I've provided detailed step-by-step instructions for each one. 

You got this! 

