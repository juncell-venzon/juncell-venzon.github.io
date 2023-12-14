---
layout: essay
type: essay
title: "Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2023-11-29
published: true
labels:
  - Software Engineer
  - Design Pattern
---



<div class="text-center py-2">
  <img width="500px" src="../img/design-pattern.png" class="img-thumbnail" >
</div>



## I. Introduction
---
Understanding design patterns in software engineering is like musicians mastering the notes and chords in music. These patterns, however, are much more than mere theoretical concepts; they are practical steps in shaping and finalizing a software product. Design patterns are established solutions to common problems in software design. They act as templates that can be applied to real programming scenarios, making code more efficient, scalable, and maintainable. These patterns help developers avoid reinventing the wheel, providing a tested, proven pathway to solving design challenges. In our ongoing team final project, "UHnify," a website that allows users to create accounts and join clubs to discover events. This project is a great example of how design patterns serve as important building blocks in the making of complex software systems. Each pattern employed in "UHnify" has contributed significantly to the project's development process, aligning with our milestone goals and enhancing the overall functionality and user experience of the platform.

## II. The Orchestra of Design Patterns
***
Try to picture an orchestra, Each instrument always has its specific role to play, contributing its unique sound to create a unified piece of sound. This ties in really well with the project since we used many design patterns which all play their part in the development process (milestone goals)

- <b>Data Fetching and Publication Pattern:</b>  This is analogous to the conductor, who sets the tempo and ensures that everything is in tune. Our Configuration Pattern in files such as Accounts.js guaranteed that the site operated properly right away.
- 
* <b>Configuration Pattern:</b> AI played a crucial role in helping with my practice sessions and providing quick and effective solutions.

- <b>Utility Functions Pattern:</b> This is the orchestra's tuning fork, which ensures that every instrument is in tune. Our utility functions in Accounts.js served as critical tools for ensuring uniformity throughout the program.

* <b>Module Pattern</b> Acts as the backbone in providing rhythm and structure to musical compositions. In our project, we utilized modules like Methods.js and Mongo.js to encapsulate functionalities, ensuring consistency and division of responsibilities - much like a skilled drummer maintaining the beat.

- <b>State Management:</b> Can be likened to an ensemble of woodwind instruments where each instrument plays its melody while harmonizing with others. Within components such as SignIn.jsx, we employed useState and useEffect hooks proficiently to manage local state and handle lifecycle events concurrently.

* <b>List Rendering Pattern:</b> Picture the repetitive yet essential rhythm of a tambourine. Components like ListClubs.jsx followed this pattern, iterating over data to render lists, similar to a consistent beat in music.

- <b>The Component Pattern:</b> mirrors the cohesive nature of an orchestra's violin section working together in harmony. In constructing our user interface for "UHnify," React's component pattern served as our guiding principle. Through functional components such as Club.jsx and Profile.jsx , we were able to create numerous UI elements that performed designated tasks effortlessly.

* <b>API Methods (Meteor Methods)</b> Comparable to the brass section, known for its powerful and resonant sound, this pattern in Methods.js played a key role in defining server-side operations, underpinning the application’s functionality.

- <b>Form Handling Pattern:</b> Similar to the harp, this pattern adds finesse and elegance. Our use of uniforms-bootstrap5 in components such as AddClub.jsx simplified and elegantly handled forms.

* <b>Container and Presentational Components:</b> This arrangement is analogous to having soloists and choir members. As seen in AddClub.jsx and ClubFinder.jsx, soloists (Container components) focus on the performance (how things operate), but the chorus (Presentational components) adds to the visual appeal (how things look).


## III. Conclusion 
---
Finally, just as an orchestra blends different instruments to make a beautiful piece of music, we blend different architectural patterns in software development to build efficient, scalable, and maintainable systems. Through "UHnify," my study and use of these patterns has not only equipped me to answer interview questions but also to construct more such symphonies in the world of code.
