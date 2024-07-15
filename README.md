## Overview
We present chromotherapy  in VR based on your level of brain's enjoyment matched to color. BCI + Chromotherapy

## Inspiration

*"It is impossible to study society—social life, public life, religious life—without taking into consideration emotional backgrounds, how emotions are provoked, how emotions are expressed, how emotions are displayed"*

Currently, it is difficult to find a platform that provides an environment for users to track their emotions, manage and express them. Typically platforms only allow users to do one or the other. We wanted to provide users with an opportunity to not only detect what emotions they are experiencing, but also a tool to relieve stress. We opted to use a tool that has long been used by humanity as a way of expressing emotions: art.

*“Colors have certain biological and psychological effects on people, and I think it’s about time we start taking advantage of it” - Mohab Ibrahim, PhD, MD, associate professor of anesthesiology at the University of Arizona College of Medicine, Tucson*

We also discovered that when it comes to chromotherapy (color therapy), it's difficult to know what colors better suit who considering the various different factors that affect that. We figured there was a way to manage  and to fix this problem by using brain signals. 

## What it does

We paired Arctop’s latest technology, Neuos and Oculus Quest 2 using the so they can work simultaneously to provide users with this immersive experience. Neous will read brain signals to personalize the experience for each user and Oculus Quest 2 will provide users with a means to express themselves through color and movement.

## How we built it
We built it by integrating Arctop's SDK, which fetches brain signals using Neous. It provides three kinds of data with 5 calls per second. The three kinds of data are: Enjoyment, Focus and the Zone. We then send the data to the cloud through the app and listen to changes in this data with unity. We leverage the zone data and match this data to particular colors, which we calibrate at the beginning of the session. These colors are matched on a level of enjoyment from minimum enjoyment to maximum enjoyment. 
While the user is in session we match their emotion to color as they are drawing in real time. They draw in Virtual Reality in a room with certain 3D objects that provide creativity.

## Challenges we ran into
The major problem we experienced was integrating Arctop's SDK, considering it's a relatively new startup and the device uses an old bluetooth technology. However, we worked with the mentors and other developers working on the same obstacle to fix most of the issues. We later made this code available as Open Source code for anyone who might run into the same issues later.

## Accomplishments that we're proud of
We are proud that we were able to execute this idea and create a mostly working prototype in the limited time. Most of us are also new to hackathons and the experienced hackers did a great job at guiding the new members through the process.

## What we learned
We  learned to work with strangers to form a new product and regardless of having our own team, we worked with other teams to make open source code to make life easier for others in the future.

We learned that it was important to communicate thoroughly initially to set the foundation for the project. We then split up the project and used each person's skills to use our time efficiently.

We also learned about the challenges we can overcome when we come together. Bouncing ideas off everyone around the table was really eye opening for not only us, but everyone we interacted with.

## What's next for Expressive Emotion VR
If we had more time and resources we would have loved to create an app to accompany the experience. This app would allow users to save their art and track their emotions over time.


