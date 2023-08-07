## Introduction

- **Course Name**: Design and Implementation of Human-Computer Interfaces

- **Couse Instructor:** Dr. Samit Bhattacharya, CSE, IIT Guwahati

- **Some examples:** smartphone apps, wearables, smart TV apps, etc.

- These interfaces have become very much part of our lives, due to proliferation of large number of affordable consumer electronic products.

- Challenges: to make the products **usable** to lay-persons and the main concern is to ensure usability for the products.

- **Course Objective:** development of a usable system follows a process consisting of stages, in this course we will learn the stages a system should follow to be usable.
  
- **Course Plan:**
<img width="284" alt="image" src="https://github.com/renuka-rajpuria/nptel-2023/assets/91603618/a5e4e948-734a-4191-b080-d5c309957f1b">

----

## Lec 1: Interactive Systems

### 1.1 Scope

How to "engineer an interactive software", with 2 key concepts -
- Interactive software: specifically computer software that are interactive
- "Engineering" such software - how to design, develop and implement such software systems.

### 1.2 Interactive System

- The term computer brings to mind desktops, laptops, smartphones, etc but these are not the only examples of computer. We are actually computers. Eg: a digital pedometer is it a computer?

- Computer: an electronic device which is capable of receiving information (data) in a particular form and of performing a sequence of operations in accordance with a predertermined but variable set of procedural instructions (program) to produce a result in the form of information or signals. In a nutshell, a computer takes some input and runs some program on it to give some output.

- Key function of a pedometer: differentiate between standing and walking?, keeping a count of number of steps, now we need to understand that counting of steps is not an easy task as you are likely to walk at different speeds at various instants. Then the pedometer also tries to convert the number the steps to distance covered for which it should know the formula for conversion and perform the conversion. Thus it fits the defination of a computer. (Input is here from the signals, algorithm includes a set of formula and based on it the output is produced.)

- Another example is microwave oven: the various components of it includes:
<img width="427" alt="image" src="https://github.com/renuka-rajpuria/nptel-2023/assets/91603618/c34d252b-bbcd-4413-b1fa-a73085ca38ed">

It receives some input from the front panel such as temparature, duration, etc then it produces some sound and heat output based on the stored information.

-  Another example: Smart TV, the various components are:
<img width="581" alt="image" src="https://github.com/renuka-rajpuria/nptel-2023/assets/91603618/6eca37c7-6511-41cd-8fb4-afa34ff71a01">

This is also a computer.

- These all are examples of "interactive" computer systems where the "interaction" takes place between the "computer" and the "user". **These users however are not technology experts but rather are layman users.**

- Is it necessary for the users to know about the technology behind it?
  This is an example of an error message in earlier systems where it shows a lengthy error message alongwith its hexadecimal status code. 
  
<img width="495" alt="image" src="https://github.com/renuka-rajpuria/nptel-2023/assets/91603618/e4ce7ecd-9a45-48b5-89dc-d5399b35ce9c">

  There is only one option that is the OK
  If I do not know anything about what is hexadecimal, event clock etc that is unless I am a security accounts manager I will not understand anything from this message. So the user is shown this message and is expected to have a certain level of knowledge as is evident from the given message. 

  Thus, if I do not have the knowledge and am unable to understand, it will make me anxious with thoughts such as Did I do something wrong?, How to get out of it?, Should we refrain from performing any more things? This may lead to loss of motivation for further use which defeats the overall purpose of making the system.

### 1.3 User Centric Design

- These concerns where we want to avoid the user being forced to lose motivation or have confusion because certain knowledge is not there, it brings us to this important concept of **user-centric design.**

- Guiding principle for designing any interactive system: System should not force users to learn about the underlying technology otherwise the user will not be motivated to use the system.

- The main concern here is how to design systems/products that the users find easy to use?

### 1.4 A Case Study: TV Remote Control
<img width="147" alt="image" src="https://github.com/renuka-rajpuria/nptel-2023/assets/91603618/7358d494-c4c6-4f0e-b52d-1b55c4dece73">

Some common activities done with it includes:
- control brightness, contrast, gamma-correction, etc
- input channel number (typically 3 digits) for channel selection
- control voice level
- watch movies from external devices
- watch the photos or videos from digital camera on the TV screen

<img width="457" alt="image" src="https://github.com/renuka-rajpuria/nptel-2023/assets/91603618/fdcff8e7-75d6-4825-9ea3-3733eddf748c">

<img width="341" alt="image" src="https://github.com/renuka-rajpuria/nptel-2023/assets/91603618/8fc3ea3d-2aba-409f-8683-505d810b044a">

<img width="332" alt="image" src="https://github.com/renuka-rajpuria/nptel-2023/assets/91603618/f07a011e-a126-4663-9472-cb39a701c43d">

The thing is that in the same device all these buttons are provided, the remote actually supports many more activities than the set of common activities. 

The 3rd group of buttons are very rarely and infrequently used.

By putting every control options on a single device, the remote-control actually succeeds in scaring away many potential users (at least initially)

So what could have been done? It could have been designed in a way such that the most frequently used buttons are made clearly visible and are prominent while the other buttons are not given the same prominence. That could have emphasized the relative importance of the buttons to the users.

Thus, user-centric design is extremely important where it is the process to design products, which are computers, in which the users' needs and expectations are taken care of considering their characteristics.









  


  


  



