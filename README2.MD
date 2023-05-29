#update:

Sorry, I really am new to this Github thing. I tried uploading my Vuforia data into Github, but then it turned all messy, and there were too many files to upload that I didn't think it was worth cramping up this
whole space.

So instead, I'll summarize what I have done to make the app work. I know this isn't really the way it's supposed to be, but what can i do :/

First, I made use of a 3D CAD model of the engine itself to train the Vuforia Tracking System to "recognise" the smaller Engine Model. Once I trained it, I did a test to make sure that "something happens" once the
system could recognise and detect the real-life model engine. This proved to have worked, as well as for the full-scaled engine.

Once I could get the system to detect the engine, I worked on the "what happens after the engine gets detected?" part. At this time, I was relatively new to C#, but I used my intuition and Python knowledge to engineer
my way to code what I needed the app to do. The main function that I needed was to create an outline of the engine that surrounds the engine. Sort of like a "hologram". This allows the user to "see" what is around the
engine without having to walk around. Then, I programmed touch-screen buttons for the user to click on to progress through the inspection process. Each button is labeled "ONE" through whatever number marks the end, with
each numbered button appearing one after another. With each click, it brought up a menu where the user has to key in the relevant details they need.

After that, I made the user interface a little "nicer". Since it was just a prototype app for the internship company, I decided to have a little fun with it XD Anyways I didn't have much time to play around after that so..

All in all, it was a really fun experience using Unity to develop apps using Vuforia (Augmented Reality). It really has good potential to do many fun and creative ideas, but technology always has its' limits. For example, 
using the Microsoft Surface Go 2 was quite a bad experience as it tends to overheat when I used the app, probably because the camera was working overtime :") But oh wells, you can't have everything i guess...

