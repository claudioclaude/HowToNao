# HowTo - Nao
![Nao](https://badgen.net/badge/Robot/Nao/blue)

---

## Content

- [Installing Choreographe](#installing-choreographe)
- [Connecting Choreographe to the virtual robot](#connecting-choreographe-to-the-virtual-robot)
- [Connecting Choreographe to physical robot](#connecting-choreographe-to-physical-robot)
- [Creating a project](#creating-a-project)
- [Running a project](#running-a-project)

---

### Installing Choreographe

- ***Step 1 - Download the setup file***\
  You can download the setup file [here](https://www.softbankrobotics.com/emea/en/support/nao-6/downloads-softwares)
 
 - ***Step 2 - Run the installer***\
   Run the file you just downloaded
   
   *For a more detailed guide to the installation check the [official documentation](http://doc.aldebaran.com/1-14/software/installing.html)*

---

### Connecting Choreographe to the virtual robot

In Choregraphe, choose <kbd>Connection</kbd> and then <kbd>Connect to a local NAOqi</kbd> menu.

<add img>

---

### Connecting Choreographe to physical robot

1. ***Cable connection***\
  Connect NAO to the router with an Ethernet cable. Attach it from the back of its head to a spare port of the router or to a switch connected to the router.

2. ***NAO's IP address***\
  When you turn on NAO, he will start saying his IP address. Note it down and type it in a browser. You will access a webpage, from there you'll be able to configure his WIFI connection.

3. ***Authentication***\
  Once you loaded the webpage, you will be asked for authentication.
    - Username: nao
    - Default password: nao
    
    If login fails or if you have lost your password, visit this [link](http://doc.aldebaran.com/2-1/nao/webpage_access.html#opennao-password-lost-nao).

4. ***Network Settings***\
  When you reached NAO's webpage, select the network settings option and connect it to the WIFI.

- **Why choosing a WIFI connection instead of a cable connection?**\
  Connecting NAO to a WIFI network is highly recommended because he'll be able to move more freely, whithout having to pay attention to cables attached to him.

---

### Choreoghrape's UI

![UI](img/UI.png)

- ***Commands***\
  Here you can find all the commands that your NAO robot can execute. These are blocks that can be attached together to form a script, kind of like Scratch.

- ***Robot view***\
  Here you can see the state of your NAO robot.\
  If you don't have a physical robot connected to your computer, this window will be your virtual robot and with it you'll be able to see how your script is behaving.

- ***Connection***\
  Here you can connect Choreographe to your phisical robot or to a virtual robot.

- ***Run/Stop***\
  These buttons allow you to run or stop your script.

---

### Setup virtual robot

- Click on <kbd>Edit > Preferences</kbd>\
  ![Edit](img/virtual1.png)

- Choose the correct NAO model and click <kbd>Ok</kbd> to confirm\
  ![Nao version](img/virtual2.png)

---

### Running a project

https://user-images.githubusercontent.com/42480082/163725934-db118552-6b19-4fc0-bb5b-30d7e319fb8b.mp4

---

### Resources
 - [Choreographe's official documentation](http://doc.aldebaran.com/1-14/software/choregraphe)
 - [Connecting NAO to the Internet](http://doc.aldebaran.com/2-1/nao/nao-connecting.html#connect-to-ethernet)
 - [Projects you can try on Nao](https://funlab.nd.edu/the-nao-base/special-movements/)
