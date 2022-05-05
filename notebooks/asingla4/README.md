# Aditya's Lab Notebook

## 2/1/2022 Meeting with Machine Shop
We met with Greg Benett from the machine shop today. We got an initial idea on what kind of box we might need for our project. We were also given some suggestions on what servo-motor to use, and what laser to use.

## 2/8/2022 - First TA Meeting 
We talked roughly about how this project will shape up. Daniel mentioned the following things:
- How to design the PCB: We will mostly follow the steps outlined in the CAD assignment, but instead import the components required for our particular project.
- The initial PCB order will be somewhere in March, and we must have a keycad file ready for review before then.
- The demo will be graded based on the RV tables for each subsytem, along with our high level requirements. 
- The high level requirements must be YES/NO items which can be tested. 
- RV tables outline the requirement, and how it would be tested, for example stepping down voltage to 3.3 V
- We should look at our components first (such as the laser, motor, gps), and then find a suitable microncontroller which is compatible with them.

Our action items for the next meeting are:
- Complete the proposal
- Do more research on what specific components to order
- Flesh out the project, and exactly what each subsystem should look like.

## 2/18/2022 - Soldering Assignment
We met in the senior design lab to work on the soldering assignment. Today we were able to get the soldering part of the assignment done, leaving the software component for next week.

## 2/19/2022 - Team Meeting 1
We met to work on fixing our proposal based on the feedback given to us regarding formatting. We fixed most issues and resubmitted the proposal.

## 2/20/2022 - Team Meeting 2
We met and worked on the design document for the DDC presentation tomorrow. We were able to get all our content ready for the check presentation.

## 2/21/2022 - DDC
We had our DDC check meeting today. Some of the feedback given to us was:
- We need to fix our 3rd high level requirement, more specifically giving more details about the increment in target pace through the buttons.
- We need to add data protocols into our block diagram, as well as mentioning the exact voltage going to each component. He also mentioned that we should remove the exact component names from our document to give us some more flexibility on that front.
- In the RV tables we must add some tolerance for the resistor as well. We should also fix formatting (move to 1A, 1B, from just 1)
- In the tolerance analysis we need to be more specific, especially add the angles that the servo motor will work on.
- For safety and ethics, we should pad this section a bit more and really stress on the important ethical issue of privacy, etc.

## 2/23/2022 - Meeting with TA about Design Review
Since the Design Document is due tomorrow, we set up a meeting with our TA to go over our document and ask for feedback and suggestions on where to improve. Some of the feedback given to us was:
- We needed to fix some formatting issues throguhout the document.
- We have to make the verification steps in our RV table very explicit. Rather than just saying do A, we should also give a step by step guide on how to do A.
- We should mention more tangible requirements in our high level requirements. Just saying it should be accurate is not sufficient, we should mention more numbers.

## 2/24/2022 -  Complete Soldering Assignment
We all came into the lab today and completed the soldering assignment. Since we had already soldered the parts last week, working on the software component was relatively quick and easy.

## 2/28/2022 - Preparation for Design Review
Today we had our weekly meeting with our TA. We discussed the following things:
- what parts we should order for our needs
- we wanted to check if our PCB design looked okay
- how to prepare for the design review: Daniel told us how to divide the presentation and how much time we should spend on the different parts of our paper

We also worked as a team after the meeting to work on PCB designs as well as getting prepared for the design review.

I also had a peer design review today, so I attended another team's design review.

## 3/1/2022 - Design Review and PCB Board Review
We had our design review presentation today. It went pretty well, but we got some valuable feedback:
- Battery: worries that it may be too heavy. Perhaps prove that it isn't too heavy?
- Laser: 3s update seems ok but don't want the laser to move too quickly.
- Reference the angle on your physical design page so everyone understands what the angle is measured with respect to.
- Table titles need to be above the table, figure titles need to be below the figure.
- Update tolerance analysis for the MCU voltage

Later in the day we also attended the PCB board review and got an okay on our current design.

## 3/5/2022 - Team Meeting to complete PCB Design and Design Document
We meet today virtually to work on completing the PCB design since round 1 orders are due next week. We also worked on the corrections in our design document based on the feedback we received from our design review. Since second chance submissions for the design document are due tonight, this was our highest priority.

## 3/7/2022 - General Meeting with TA
Today we met our TA for our wweekly meeting. Important points from this meeting were:
- finalizing what parts to order
- since the microcontroller we wanted to order was no longer available, we discussed what alternatives we could explore
- questions regarding our PCB design 
- general discussion about feedback from the design review.

Since we were able to shortlist the parts we needed last week while working on the design document, we also decided to finish ordering all the parts we needed. We were able to submit our orders.

## 3/8/2022 - PCB Order Round 1 
Today the PCB round 1 orders were due. Our teammate Carlos worked on the PCB design and finished the ordering process.

## 3/9/2022 - Teamwork Evaluation
We each separately completed the teamwork evaluation I form today.

## 3/11/2022 - 3/20/2022 - Spring Break
Due to this being the week of spring break, we did not meet. 
During this perioud we also received a notification that there were some complications with our orders, and thus we will need to resubmit the order soon.

## 3/23/2022 - Ordered Parts
Today we met to figure out what went wrong with our previous order. We also researched alternate lasers to use since the one we ordered earlier was not bright enough for our needs. We were able to put in our order for all the parts we needed.

## 3/25/2022 - TA Meeting
We met our TA today and discussed more about what to do while we waited on our parts to arrive. We decided to concentrate on writing the code required to use the GPS as well as what our timeline for the next few weeks should look like. We also secured the capacitors and resistors we will need from the free part section in the lab.

## 3/28/2022 - Parts again 
Today we got an email from facilities saying that there was another issue while ordering parts. This time due to some issue on the facilities side, our order cart was lost. Thus, we all met today again to work on ordering the parts. We also had a quick zoom call with our TA to ask him how to order the parts without any issues arising.

## 3/30/2022 - GPS Code
Today we all met and discussed how to go about writing the code necessary for the GPS. We were able to find a resource which will be extremely helpful once our parts arrive. https://circuitdigest.com/microcontroller-projects/gps-interfacing-with-pic16f877a#

## 3/31/2022 - Laser Testing and Lab Notebook
Today we met to update our lab notebooks for the last few weeks. We also tested the new laser that just arrived today.
- Our new laser seems to be perfect for our application.

## 4/01/2022 - Meeting with TA
We met our TA today to discuss the progress of our project. We talked about PCB design and the best way to get started on the code part.

## 04/05/2022 - Parts Pickup
We came into the lab today to pick up our parts. We tested initially on the breadboard. The parts look good for now.

## 04/07/2022 - Soldering of parts
We soldered the microcontroller and the other components to our PCB. After this we checked the connections through a multimeter.

## 04/09/2022 - Remaining parts come in
All the parts were delivered today. We completed the soldering. However, we noticed that some of the parts were incorrect, so we had to order a new batch of parts, specifically the 32 mHz crystal required for our microcontroller.

## 04/11/2022 - Testing Subsystems
Today we built the LCD circuit using an arduino on the breadboard. We were able to complete our R&V for this subsystem today.

## 04/12/2022 - Disaster with Microcontroller
We tried programming our microcontroller today but we got no response from the PCB. We realized that this microcontroller ATMEGA809 is not compatible with Usbasp. We spent most of today looking for alternatives and found one: which is to use the UPDI pin to program the microcontroller.

## 04/13/2022 - Change of Plan
Unfortunately we were not able to program our MCU using the UPDI pin. This is because it is impossible to solder a wire to access it and since our original design did not use it, we did not have an external pin for this. Today we decided to move completely to an ATMEGA328P. We ordered an arduino nano which we plan on removing the atmega from. We also began a new PCB design

## 04/14/2022 - PCB Design
We spent the entire day designing the new PCB today. We almost have the new design ready.

## 04/15/2022 - PCB Order
We ordered the new PCB from PCBWay. We also tested the buttons and servomotor on the LCD breadboard circuit from before. 

## 04/17/2022 - Built Breadboard Circuit
Today we spent the entire day building the breadboard equivalent circuit for our design. We used a breadboard ATMEGA328. We were unable to get it to work the whole day.

## 04/18/2022 - Fixed Circuit
Today we were able to get our circuit to work. We switched to an external clock and this resulted in us being able to program the microcontroller. We uploaded the same code as we did in the arduino and verified that the LCD worked. 

## 04/19/2022 - Continued testing subsystems
We continued testing the LCD, buttons, servo-motor and regulators on the breadboard today. We were able to verify that our design was good.

## 04/20/2022 - Mock Demo
We had our mock demo today. So we discussed with our TA regarding our current situation as well demoing the breadboard circuit. 

## 04/21/2022 - PCB Arrives
Today we spent the whole day soldering the parts onto our PCB. We then worked on programming our microcontroller. We were able to program it.

## 04/22/2022 - Testing LCD on PCB
Today we tested our LCD on our PCB. We ran into some issues, but we were able to resolve them. We plan on working on the buttons and servomotor tomorrow.

## 04/23/2022 -> 04/24/2022: Locker stuck
Our locker got stuck due to something pressing on the lock from inside. We could not make any progress.

## 04/25/2022 - Complete all subsystems
Today we spent all day working on making all the subsytems work with the PCB. We also spent a lot of time working on the GPS functionality. We were able to get it all work. The only thing we could not figure out was the servomotor.

## 04/26/2022 - Work on Servo
We spent all day troubleshooting our servo-motor. However, we could not figure out what the issue was. Thus, we decided to do our demo tomorrow without the servo-motor.

## 04/27/2022 - Demo
Today we demo-ed our project. This marks the end of our project.

