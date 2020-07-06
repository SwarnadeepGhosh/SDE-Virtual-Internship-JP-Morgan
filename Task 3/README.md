# <span style = 'color : blue'>Display data visually for traders</span>

Using Perspective to create the chart for the trader’s dashboard



### Step 2: Background Information

Being able to access and adjust data feeds is critical to any trading analysis and stock price monitoring. From the previous tasks, we now have the adjusted data set up on your systems and being piped into Perspective.

For traders to have a complete picture of all the trading strategies being monitored, several screens typically display an assortment of live and historical data at their workstation.

Given there is a lot of information and data being produced at once, visualizing data in a clear manner with UI/UX considerations accounted for is critical to providing traders with the tools to improve their performance.

------

\* Understanding the finance and trading part is not required for this task.

\* Being familiar with python scripting language, command line basics, javascript, react and typescript are not required for this task too as you will be guided in this exercise

\* (Note, you DO NOT have to install Perspective as an individual software onto your machine. All you need to complete this task is to follow the instructions in step 3)



### Step 3 : Task Flow

**For the third module of this project will need you to accomplish the following:**

1. Set up your system by downloading the necessary files, tools and dependencies. 
2. Modify the typescript files in repository to make the web application behave in the expected manner
3. Generate a patch file of the changes you made.

*We've broken down the steps for you in stages below so you can accomplish this task in an organized manner.*

**Set Up**

Before you can tackle any software or development task you need to set up your development environment. Your development environment refers to your system having all the required software installed to modify the code, as well as getting the code of the project itself onto your computer.

To do this we've created a simple PDF guide below on how to get your environment set up:

View this for environment setup -->> [setup_devenv_m3_v3.pdf](setup_devenv_m3_v3.pdf)

**To start the server :** 

```powershell
python datafeed/server3.py
```

```powershell
npm start
```

**Initial Graph**

![initial-graph](D:\COURSE Modules\My Courses\SDE JP Morgan Internship\Task 3\img\initial-graph.png)



**Making Changes**

When you’re in a work environment, you’ll usually receive tasks in the form of engineering tickets.
Here is an example of what this task looks like in the form of an engineering ticket.

Purpose
You will use perspective to generate a live graph that displays the data feed in a clear and visually appealing way for traders to monitor this trading strategy.

Recall that the purpose of this graph is to monitor and determine when a trading opportunity may arise as a result of the temporary weakening of a correlation between two stock prices. Given this graph, the trader should be able to quickly and easily notice when the ratio moves too far from the average historical correlation. In the first instance, we'll assume that threshold is +/-10% of the 12 month historical average ratio.

Acceptance Criteria

- This ticket is done when the numbers from the python script render properly in the live perspective graph. This means the ratio between the two stock prices is tracked and displayed. The upper and lower bounds must be shown on the graph too. And finally, alerts are shown whenever these bounds are crossed by the ratio (the guide below will also give more detail and visuals to help you understand these requirements better)
- This ticket is done when a patch file is uploaded along with a video or audio explanation of the final chart you have produced


To properly make the changes necessary to complete the objectives of this task, follow the guide below.

Making Changes guide -->> [making_changes_m3_v2.pdf](making_changes_m3_v2.pdf)



**Final Graph Setup**:

![final-setup](D:\COURSE Modules\My Courses\SDE JP Morgan Internship\Task 3\img\final-setup.png)



**Final Graphs :** 

![final-graph-1](D:\COURSE Modules\My Courses\SDE JP Morgan Internship\Task 3\img\final-graph-1.png)

![final-graph-2](D:\COURSE Modules\My Courses\SDE JP Morgan Internship\Task 3\img\final-graph-2.png)





