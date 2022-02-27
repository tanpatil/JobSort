# JobSort

This tool was built by Tanay, Gaurab and Abijit for NYU Hacks 2022

For more info, check out [our devpost](https://devpost.com/software/jobsort)

[Instructions](/frontend)

## Inspiration
In the fast-paced and quickly-growing energy field, efficiency and accuracy mean everything. But when essential equipment break down, large-scale operations can fall apart. Provided with JobSort's task assignment system, we sought to optimize delegating tasks to anything from homework in the classroom to working on a hackathon project, all while making the detailed process appear simple and elegant. We've been meaning to build this for a while and realized that the melatonin deficient and fast-paced environment of a hackathon would be the best place to sesh it out.

## What it does
JobSort provides an easy-to-understand platform to delegate tasks that prioritizes time efficiency in matching qualifications to task assignments. With our focus on user experience and attention to detail on the front end, we hope to help JobSort users to avoid facing the difficulties of the intricate tracking and scheduling process.

## How we built it
We built the full-stack web application around our task delegating system that supports dynamically adding new tasks. The web application's front-end was built with Vue.js, a Javascript framework designed for easy UI development. The back-end of the web application had two services, a NodeJS server that handled most of the authentication and data manipulation and a Flask server that called the algorithm that we wrote in Python. The NodeJS server also supports sending SMS notifications to technicians, implemented using Twilio's NodeJS library.

## Challenges we ran into
One of the biggest design challenges we faced while building JobSort was constructing the algorithm to delegate tasks. We had to carefully consider what was necessary for the admins and how we delegated them to the operatives. We also wanted to maintain multiple MongoDB servers as the databases but couldn't because of time constraints. In the algorithm design, we ended up selecting urgency over speed. We weighed the pros and cons with each algorithmic choice we made, which fueled our discussions throughout the development.

## Accomplishments that we're proud of
One thing that we were definitely proud of was working together as a team. We were amazed to see the progress that we were able to make, especially in such a short period. We all definitely enjoyed this multi-faceted problem, especially going through the design process and watching things grow as we came together with a solution.

## What we learned
We learned a lot while working on JobSort, but some of the most important things we learned ironically were how to work effectively as a team and how to delegate tasks. We also learned about different web development frameworks and how to use them to create a user-friendly interface. We also learned how to use Twilio's API to send SMS notifications.

## What's next for JobSort
Creating more interactive features and avenues for communication.
We also want to create a more engaging experience for users so that JobSort can become a hub for technicians and employees to communicate.
Afterward, we want to improve our algorithm further, expanding it cross with several more constraints and tailoring the experience to the user, the operative.
We also want to maintain three databases: one for admins, one for tasks, and one for operatives. One idea that we came by has multiple people tag in to speed up the process. This decreases the idle time of the operatives and fosters a collaborative environment; something JobSort thrives on.
