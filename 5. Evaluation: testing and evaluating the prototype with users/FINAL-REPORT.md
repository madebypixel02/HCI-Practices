<!-- *********************************************************************** -->
<!--                                                                         -->
<!--                                         =@@*   +@@+                     -->
<!--                                         =@@*   +@@+ :*%@@@%*:           -->
<!--                                         =@@*   =@@+.@@@=--%@@-          -->
<!--                                         :@@%. .#@@--@@*   +@@* .+%@@@   -->
<!-- FINAL-REPORT.md                          =%@@@@@@+ =@@*   =@@+.@@@+-=   -->
<!--                                            .---:   -@@#.  *@@--@@*      -->
<!-- By: aperez-b <aperez-b@uoc.edu>                     +@@@@@@@* +@@+      -->
<!--                                                       :-==:.  -@@#      -->
<!-- Created: 2023/01/07 23:35:27 by aperez-b                       +@@@%@   -->
<!-- Updated: 2023/01/07 23:37:58 by aperez-b                                -->
<!--                                                                         -->
<!-- *********************************************************************** -->

# Final Report

## Table of Contents

- [1. Summary](#1-summary)

  Write the general description and outcome of the solutions of the case study

- [2. Introduction](#2-introduction)

  Description of the project, solution proposals and short conclusion

- [3. Structure](#3-structure)
  - [3.1. Context](#31-context)

    Description of user profiles and analysis of HCI principles

  - [3.2. Improvement Proposals](#32-improvement-proposals)

    Analysis of the accessibility of the first hand-drawn prototype and development
    of the digital low-fidelity prototype

  - [3.2. Analysis and Results](#33-analysis-and-results)

    User test of the prototype, analysis of the accessibility of the digital
    prototype and analysis of HCI in it

- [4. Conclusions](#4-conclusions)

  Final remaks and improvements for future prototype iterations

- [5. References](#5-references)

  Links to resources used in the development of this project

## 1. Summary

ENGLISH

This project is based on a homeseeker case study. Our goal was to design and
prototype some features that would make our hypothetical website appealing
over other similar sites. To do so, we looked at what other services do good
and their flaws, and designed a prototype with a set of user profiles in mind.

It was not easy to design something simple and powerful at the same time. One
will eventually sacrifice bloating the user interface for some extra convenience.
One of the major roadblocks in the project was proposing an interface that
was intuitive and accessible for everyone, and still offer similar features
to what common homeseekers offer. Though it was not perfect, the resulting
prototype of this practice has managed to reach a certain level of usability
while maintaining the core principles of minimalism by which it stands.

SPANISH

Este proyecto se basa en un caso de estudio de una página de alquiler y compra
de domicilos. El objetivo fue diseñar y prototipar algunas funciones que
formarían parte de nuestra hipotética página web. Para ello, observamos lo que la
competencia estaba haciendo, fijándose en sus puntos fuertes y aprendiendo de sus
errores, y con ello diseñamos un prototipo teniendo en cuenta nuestros perfiles
de usuarios tipo.

No fue fácil diseñar algo simple y a la vez potente. Tarde o temprano se
complica la web mucho a cambio de una pequeña funcionalidad conveniente. Uno
de los obstáculos más grandes a superar fue el de proponer una interfaz que
fuera intuitiva y usable por cualquiera a la vez que tuviera la capacidad
de realizar acciones complejas como hace la competencia. Aunque no es ni
de lejos perfecto, el prototipo resultante de esta práctica ha conseguido
hasta cierto punto alcanzar un nivel decente de usabilidad, y ha mantenido
los principios fundamentales de minimalismo por los que se rige.

## 2. Introduction

The goal of this subject was to develop a prototype of an interface corresponding
to a homeseekers site. In order to design something appealing and fresh to potential
customers, we had to add certain improvements that similar services lacked.

To do this, we first started by looking at the competition, i.e. other commonly
known homeseeker sites ([Fotocasa](https://fotocasa.es),
[Idealista](https://idealista.es), etc), and did some benchmarking of each of
them (see their pros and cons) to understand the kind of things to implement
as well as the things to avoid. We chose features `2`, `3` and `5` out of the
following **5 requirements**:

1. You can search for rental or purchase housing.
2. Search for homes by location (maps, neighbourhoods, municipalities, counties,
draw the search area on a map, etc.
3. Check out homes based on their characteristics (number of rooms, bathrooms,
equipment, area, price, recently built construction, pool, parking, etc).
4. Check out the full details and description.
5. Three actions should be related to homes, like saving as a favourite,
consulting opportunities, sharing an ad, or setting price drop alerts.

We then analyzed the type of user profiles that would use our app, because
designing for everyone is designing for no one. This helped us understand what
every user profile might need, and better implement the features accordingly.

After that, we started developing our prototype, first by visualizing them
inside flowcharts, to better understand possible conflicts (user not signed in,
incorrect search parameters, etc). We contacted two test users and interviewed
them to better understand how they expected the features we were going to implement,
and also designed our first hand-drawn sketches of how these improvements
would look in the future.

Next, we re-built the prototypes digitally using prototyping tools such
as *JustInMind* or *Jiira*.

Lastly, we analyzed the accessibility and basic aspects of
Human-Computer Interaction (*HCI*) of our barebone sketches and proposed
some improvements to them to reach level *A* accessibility, and reached out
to the peers we had formerly interviewed to test our
prototype to find improvements for future iterations of our prototype.

## 3. Structure

### 3.1. Context

To follow this case study I decided to improve the site with the following
features:

1. Search for homes by location (maps, neighborhoods, municipalities, counties,
draw the search area on a map, etc.).
2. Check out homes based on their characteristics (number of rooms, bathrooms,
equipment, area, price, recently built construction, pool, parking, etc.).
3. Three actions should be related to homes, like saving as a favorite,
consulting opportunities, sharing an ad, or setting price drop alerts.

To design these features, I set up the following user profiles:

![Kathy Anderson \*](https://user-images.githubusercontent.com/40824677/197558776-62e3db52-d259-4b29-87b1-5a5d5b8a1c72.jpeg)

**Demographics**

- 15 to 24 years old (23)
- Single
- College Student
- Lives with her parents in New York
- Very low budget (typical university student)
- Wants to rent apartment near the University

**Interests**

- Usually studies at Starbucks on her laptop
- Has many friends and likes to hang out with them
- Loves to keep her space tidy
- Takes piano classes twice a week

**Needs & Objectives**

- Find a roommate to share an apartment with
- Become a professional artist

![Bill Jackson \*](https://user-images.githubusercontent.com/40824677/197558790-a4c032d3-320d-41ee-b921-bb4f61199d55.jpeg)

**Demographics**

- 60+ years old (67)
- Married to Emily Jackson (has two adult children)
- Retired (worked at a bank)
- Lives alone after her wife died
- Medium budget, can afford some extras in the new house
- Wants to sell her old house and buy a smaller flat near his loved ones

**Interests**

- Likes to take care of his grandchildren
- Plays pool with his all-time friends
- Likes to chop wood on his second home in the forest
- Sings at the local church

**Needs & Objectives**

- Find a cheap flat near his kids' house to help care for his grandchildren
- Figure out how to use technology and social media to stay in touch with friends and family

![Riley Wheeler \*](https://user-images.githubusercontent.com/40824677/197558784-3ae8bd81-293f-4276-bf51-9d60da0832db.jpeg)

**Demographics**

- 30 to 40 years old (32)
- Married to John (has three young kids)
- Mechanic engineer (works in car maintenance)
- Lives in a very small apartment with his husband and family
- High Budget, wants to give every extra she can to her loved ones
- Wants to buy a large house with John and her kids

**Interests**

- Loves to care for her three rascals
- Works out at local gym with old college friends
- Has a passion for cooking desserts for a local charity
- Uses social media to advertise her mechanics business

**Needs & Objectives**

- Find some spare to relax from her busy schedule
- Get a large house with a garden and pool in the countryside

![Jack Nelson \*](https://user-images.githubusercontent.com/40824677/197558792-642a565a-3a53-4877-8ad0-c88c25320a06.jpeg)

**Demographics**

- 15 to 24 years old (20)
- In a relationship with Mary, not married
- College Student, entrepreneur (has a business in cryptocurrency)
- Lives with his parents in Ontario, Canada
- High budget, wants a smaller modern house with very good cell service
- Wants to buy his first small house for himself and his girlfriend

**Interests**

- Works from home and studies completely online at the UOC (Techniques for Software Application Development)
- Has few but valuable friends
- Follows many crypto-related accounts on Instagram to check how the currency changes
- Plays Football in a semi-professional level three times a week

**Needs & Objectives**

- Buy a small house in the city
- Balance his busy life and handle being a student, entrepreneur and good boyfriend all at once

\* Images generated by thispersondoesnotexist.com

Knowing these user profiles and the insights extracted from the interview
made to Pablo and Patricia in Challenge 2, I focused on applying the following
aspects of *HCI*:

- The *save as favorite* button should have a heart icon, and possibly be filled
upon saving.
- Price-drop alerts should be enabled or disabled by pressing *bell* icon.
- Arrows pointing back must refer to going back (go back on the site, previous image, etc)
- User should not be able to save as favorite without an account (or not logged in),
but can set price-drop alerts or contact seller on-demand with an email address.
- The map feature should be visible on the screen, close to the search bar.
- The site should respect accessibility rules (design principles for all), avoiding,
color contrast issues, implementing skip links and/or context information for images and
buttons (used by screen readers to better explain the user what is being displayed). Some
examples implemented in the first designs are short periods for undoing certain actions,
and ability to show captions in videos.

Understandably, it was not possible to implement these points perfectly, so the low-fidelity
prototype designed during this time may not implement the above aspects of *HCI* faithfully.

### 3.2. Improvement Proposals

These improvements were finally visible in a simple hand-drawn prototype:

![Main Screen - Search box and map](https://user-images.githubusercontent.com/40824677/201931275-7581e162-4b8a-4ef9-9510-3e003a411563.png)

![Search Results - Filtering options](https://user-images.githubusercontent.com/40824677/201931265-080f23cf-19de-4e02-8d64-07183904c2d5.png)

![Search Result - Tooltip options (save, share, notify, contact)](https://user-images.githubusercontent.com/40824677/201931254-1ed1c8e7-4b8a-4660-929c-99c4de5a416a.png)

![Video Captions and Read Aloud mode](https://user-images.githubusercontent.com/40824677/204353865-3251dd1a-4143-40bd-8518-1eb0e6ca77d3.png)

![Undo Remove from favorites](https://user-images.githubusercontent.com/40824677/204356132-188694f8-67f6-4e2d-ace1-f7a075ae57c7.png)

As we can see, the interface is quite simple, and that is no coincidence.
Users potentially trying out my homeseeker tool will want something that
is not underwhelming, and yet is still powerful enough to show as much
info as possible at a glance. The photos above show clearly how the page
is supposed to work:

```txt
Homescreen > Search Results > Product Page

Homescreen: hosts a large centered search bar with quick options to
change between buying or renting a house, as well as a map
(possibly powered by Google Maps) to draw an area directly on
rather than typing an address.

Search Results: shows the same search bar from the homescreen at the top,
a left sidebar with granular filtering options, and the actual result disabled
in cards in the remaining space. Each result includes a sample photo,
an address or house name, and a short description of the house.

Product Page: clicking on any result from the results page will "expand"
the result card into a bigger card which takes up all of the width of
the page (as there is no sidebar here). The image is now a gallery of
pictures, allowing the user to press arrow buttons to see more pictures
(or even videos) of the house they are looking at. There is also a
set of buttons that appear on top of the picture, which are for
saving the house as favorite, sharing the house on social media,
set price-drop alerts, or contact the seller.
```

Once we analyzed the accessibility of these hand-drawn sketches, we
designed [this low-fidelity prototype](https://www.justinmind.com/usernote/tests/72708202/74128913/74128917/index.html).
Here are a few images showing some of the most remarkable features:

![Home Screen Search Bar - Hover](https://user-images.githubusercontent.com/40824677/211170910-19ec8c9e-0615-43a5-965e-88f436d2f5cb.png)

![Home Screen Search Bar - Menu](https://user-images.githubusercontent.com/40824677/211170914-45438cc6-2022-48f2-952e-77fac3d1d22f.png)

![Search Results - Menu Filter](https://user-images.githubusercontent.com/40824677/211170909-11b66d9e-3ebc-4697-8f0a-6656c4b180ab.png)

![Search Results - Hover Image](https://user-images.githubusercontent.com/40824677/211170905-5077f378-809e-425c-8445-3a72f478a298.png)

![Product - Hover Favorite](https://user-images.githubusercontent.com/40824677/211170901-6aaeb97b-406b-4a39-846b-c3c65c627fad.png)

![Product - Fill Favorite - Hover Yes](https://user-images.githubusercontent.com/40824677/211170895-2a933e75-3fc0-4d71-8804-803a307e37e5.png)

![Product - Hover Next](https://user-images.githubusercontent.com/40824677/211170886-a8cce326-1d07-4887-86ae-3eefe5ff6408.png)

### 3.3. Analysis and Results

Overall, the outcome of the low-fidelity prototype has been decent.
There is lots of room for improvement though. Here are some of the
most remarkable positive and negative aspects following the user
test of the prototype and follow-up interview:

- Both users seem to find their way around the UI without trouble
- The map feature is not so useful if it only accessible from the
homescreen. It should be accessible (in full size, or a button)
on every page just like the search bar.
- It is not ideal to keep buttons inside the images as their background
color may not contrast well with the button's outline color.
- The icons for buttons are universally easy to understand: a heart
means you like something and save it for later, an envelope represents
sending an email, and so on.
- The entire result card should be clickable to open a house result,
rather than only the image opening it.
- The little animations that enlarges an image when hovering over
it lets the user know that the house from the image can be clicked to open.
- The buttons and images have good screen reader compatibility
with informative descriptions of what they represent.
- The layout of elements is not great, there is much wasted space where
useful information may be added.

Moreover, it is essential to review which of the following **fundamental
aspects of HCI** are present on our prototype:

- **Metaphor**
  - Heart icon represents *saving as favorite*.
  - Envelop icon represents *sending an email*.
  - Saving an element as favorite fills it up in red to indicate the
  action was performed successfully.
- **Affordance**
  - There is a prompt to enable price-drop alerts which is quite self-explanatory.
  - There are other self-explanatory buttons in the UI: *Apply*, *GO*, etc.
  - Hovering on an image in the search results page will enlarge it a bit to show
  that it is focused and that it can be clicked.
  - Many filters and the search bar filter have a drop-down menu represented by
  a downwards-pointing arrow.
- **Visibility**
  - Search results are split into two panels, one displaying lists of houses matching
  the search criteria and another on the left showing available filterin options.
- **Feedback**
  - Links will change the cursor to indicate they can be clicked (standard behavior for
  links).
  - Hovering on an image in the search results page will enlarge it a bit to show
  that it is focused and that it can be clicked.

## 4. Conclusions

In conclusion, this entire practice has been aimed at developing our first-ever
prototype using a real world example case study. We attempted to achieve level *A*
of accessibility, though I don't think my prototype is quite there yet. This has been
my first contact with a prototyping tool such as *JustInMind*, and it has certainly
been useful in order to better appreciate the huge amounts of work put behind every
interface, not only in the layout and style of the *UI* and *UX* themselves, but also
in carefully ensuring accessibility for all and keeping every user in mind while doing
so. Prototyping sure appears to be hard, especially when it comes to balancing out all of
these roadblocks, but it definitely pays off in the end.

## 5. References

1. Beaudouin-Lafon, M., Prototyping Tools and Techniques, https://www.kth.se/social/upload/52ef5ee4f2765445a466a28a/mackay-lafon-prototypes-52-HCI.pdf, 02/11/2022 
1. Prototyping Tools, https://designcode.io/ui-design-handbook-prototyping-tools, 08/11/2022
1. Shepherd, A., 12/10/2020:12:58, What Is Justinmind and How to Use Justinmind (Mockitt), https://mockitt.wondershare.com/software-design/justinmind.html, 15/12/2022
1. McElroy, K., 08/01/2017, Prototyping for Designers: Developing the Best Digital and Physical Products, O'Reilly Media 2017

January 7th, 2023
