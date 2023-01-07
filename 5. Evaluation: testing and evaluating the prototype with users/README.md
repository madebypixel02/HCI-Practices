<!-- *********************************************************************** -->
<!--                                                                         -->
<!--                                         =@@*   +@@+                     -->
<!--                                         =@@*   +@@+ :*%@@@%*:           -->
<!--                                         =@@*   =@@+.@@@=--%@@-          -->
<!--                                         :@@%. .#@@--@@*   +@@* .+%@@@   -->
<!-- README.md                                =%@@@@@@+ =@@*   =@@+.@@@+-=   -->
<!--                                            .---:   -@@#.  *@@--@@*      -->
<!-- By: aperez-b <aperez-b@uoc.edu>                     +@@@@@@@* +@@+      -->
<!--                                                       :-==:.  -@@#      -->
<!-- Created: 2023/01/07 23:38:01 by aperez-b                       +@@@%@   -->
<!-- Updated: 2023/01/07 23:38:57 by aperez-b                                -->
<!--                                                                         -->
<!-- *********************************************************************** -->

# 5. Evaluation: Testing the Prototype with Users

## Table of Contents

- [Introduction](#introduction)
- [User Testing](#user-testing)
- [Usability of a Colleague's Proposal](#usability-of-a-colleagues-proposal)
- [Accessibility Evaluation](#accessibility-evaluation)
- [Final Report](#final-report)
- [Summmary](#summary)

## Introduction

In the first challenge, we defined user profiles, analyzed the competitors and
explored the fundamental principles of human-computer interaction.

In the second challenge, we used two methods to analyze an interface. In
the flowchart we defined the step-by-step process necessary to complete some
tasks. In the second, we used real users to view live usage and detect possible
errors or things to improve.

In the third challenge, we worked on universal design, accessibility, and re-
fined the improvement proposal to meet the *WCAG* level *A*.

In the fourth challenge, we implemented a prototype to complete a given task.
Finally, in this fifth and final challenge, the objectives are:

1. Evaluating our prototype with users.
1. Evaluating the accessibility of our prototype.
1. Preparing a report on the work done.

Again, we will do a user test to evaluate our prototype and see if they perceive
improvements. We will apply the *WCAG* guidelines to see if we achieve level
*A* of accessibility. And finally, we will prepare a report on the work done and
the results of the evaluations, to see if we have achieved an improvement in
functionality. We will detail the aspects improved and how we have improved
them. And in the event of not having achieved a noticeable improvement,
we will detail what aspects we would have to modify for a theoretical second
iteration.

## User Testing

In this section, we will be contacting the same two people we interviewed in
challenge 2: synthesis of the proposal. This time, the two users Pablo and
Patricia will test our low-fidelity prototype live and will then answer a
couple of questions. We will then analyze the results of the two users
and draw some conclusions as to what needs to be changed or improved in
future iterations of the prototyping process.

Disclaimers:

- For privacy reasons, I will use fake names instead of their real names.
- I didn't record the interviews; I only took some notes on the answers,
so the conversations don't show *exactly* the answers in the interview.
- For reference, the script from the previous interview is also added, and
new content appears below the text **NEW**.

### User 1

- Description

```txt
Name: Pablo
Age: 23
Marital Status: not married, not in a relationship
Location: Lives with his parents in Madrid
Interests: all things technology, cryptocurrencies, animals
Budget: High Budget
Needs: Apartment (shared or not) closer to where he is doing his studies
Personal Goals: work out more
```

- Interview script

```txt
Alex: Hello, thank you for agreeing to make this short interview.
Pablo: Pleasure, hope it helps!

Alex: Hope so. Okay, first question: How would you search for a house
based on the area where you want to buy it?
Pablo: I maybe would look for an area that interests me, but I personally like to
find houses straight from the map. It helps me to see other places nearby such as
shops, libraries or restaurants.

Alex: Thank you. Would you use filtering options for your house, like price ranges,
how old the house is, how many floors it has, wether or not it has parking,
accessibility entrances, and so forth?
Pablo: I would set a maximum price I am willing to pay. I want a flat, preferably
without roommates, so I would set the number of floors to 1 and number of
roommates to 0. I do want more than one bedroom in case I bring friends over to sleep.

Alex: Okay, last question. Describe how you would go about sharing a house as favorite.
Pablo: Assuming I have an account, I would expect to see a "Favorite" button, possibly
with a "heart" on it. I would also expect it to be a personal list I could add
it to. Say I want to buy a house but I am still deciding between two places. I would
save many places as favorite, but it would be awesome to save them in different
categories or under different tags I would create.

---
NEW
---

Alex: Was it easy for you to perform the task of saving a house as favorite? Was there
anything in the process that was unexpected or could be improved?
Pablo: Saving a house as favorite was not a hard thing to do. I found that heart icon
I expected next to the house I wanted to save, and it filled up red once I saved
the house. Something which could be improved in this regard is that the buttons to
save as favorite, contact seller and share on social media are all inside the image,
which makes the buttons contrast poorly depending on the image behind them. One solution
would be to dynamically adjust the border of the buttons so that they always contrast
well with the background colors behind, but the easiest solution would probably be
to just place those buttons outside the image, where managing that color contrast
is much easier.

Alex: Name something else that could be improved for a future iteration of a prototype.
Pablo: Regarding those same buttons, I missed them on the search results. I usually
expect to bulk select many results (houses), and save all of them, or turn price-drop
alerts for all of them at once, instead of going inside each result one by one and
saving them as favorite or enabling price-drop alerts.

Alex: That's a wrap! Thank you so much for this interview. I will let you know
how it goes once I finish it.
Pablo: Perfect, see ya!
```

### User 2

- Description

```txt
Name: Patricia
Age: 42
Marital Status: married to Juan, has 2 small kids
Location: Lives with his husband and kids in a small house
Interests: minimalism, keeping things organized, fashion design
Budget: Medium Budget
Needs: Larger house in the outer part of Madrid, where their kids attend school
Personal Goals: swim with dolphins
```

- Interview script

```txt
Alex: Hello, thank you for agreeing to make this short interview.
Patricia: Oh, absolutely.

Alex: Okay, first question: How would you search for a house
based on the area where you want to buy it?
Patricia: I would simply enter the name of the town I'm looking for on the site
and press enter. Then I would look at the pictures to see which ones I like the
most, and make a decision based on their price and services.

Alex: Thank you. Would you use filtering options for your house, like price ranges,
how old the house is, how many floors it has, wether or not it has parking,
accessibility entrances, and so forth?
Patricia: Oh for sure. My house must have a garden for our dog and so my kids can
play. It should also have good connectivity since I work from home most of the time.
Maybe also I would prefer that the house had a parking spot, but it is not a
priority.

Alex: Okay, last question. Describe how you would set price-drop alerts 
for houses you are interested in.
Patricia: I'm not very techie as you know, but maybe I would press a button
somewhere that would send me those notifications when their prices drop.
Oh, I think I've seen a bell icon on other sites, so that's probably what
I'd look for.
Alex: Great, but what if the site says you need an account?
Patricia: Right! In that case I would create an account with an email and a
very secure
password and then try again.

---
NEW
---

Alex: How was your experience enabling price-drop alerts? Was it stupid-simple,
or was it overcomplicated.
Patricia: I have mixed feelings about it. It is quite intuitive and quick to toggle
on/off. There was a sort of persistent banner at the bottom of the page asking
whether or not I wanted to be notified. That worked great, but it is not the way
I expected. I didn't see that small bell we talked about last time, and it seems
out of place. Like it is separate from other useful buttons like sharing on Facebook,
sending an email, and so on.

Alex: I see, thank you for that feedback. Was there anything else you did not like
about the prototype or you think could otherwise be improved?
Patricia: Another thing I found odd was how the map feature just disappeared on
every page other than the homescreen. I mean, suppose I really needed that feature?
If that were the case I would certainly expect quick access to the feature from
every page, just like the search bar can be accessed from every page.

Alex: That's all folks! Thank you so much for this interview. I will let you
know how it goes once I finish it.
Patricia: You're welcome.
```

### Reflections

Following the user tests and the interview, here are some thoughts on
the good, the bad and the ugly aspects of the prototype:

- [GOOD] Both users seem to find their way around the UI without trouble
- [BAD] The map feature is not so useful if it only accessible from the
homescreen. It should be accessible (in full size, or a button)
on every page just like the search bar.
- [BAD] It is not ideal to keep buttons inside the images as their background
color may not contrast well with the button's outline color.
- [GOOD] The icons for buttons are universally easy to understand: a heart
means you like something and save it for later, an envelope represents
sending an email, and so on.
- [BAD] The entire result card should be clickable to open a house result,
rather than only the image opening it.
- [GOOD] The little animations that enlarges an image when hovering over
it lets the user know that the house from the image can be clicked to open.
- [GOOD] The buttons and images have good screen reader compatibility
with informative descriptions of what they represent.
- [BAD] The layout of elements is not great, there is much wasted space where
useful information may be added.

## Usability of a Colleague's Proposal

After testing [Àlex's prototype](https://xd.adobe.com/view/699d898f-a79f-43ec-be3b-054ec32a9048-3cce/?fullscreen&hints=off), here are some remarks:

- **Simple and minimal design**: The site appears generally simple, though it also
may feel bloated with too many elements by some users. It is quite good nontheless.

- **Equality of Use**: The site is not responsive and thus rescaling only makes
the elements smaller, to the point they may be hard to read. This is probably out of
the scope of the prototype anyway, and other than that the interface is well adapted
for every type of user, as long as it uses a desktop form factor. Additionally, it seems
like the black heart button does not cotrast well when the background is red (this is the
outline color when an element is marked as favorite).

- **Perceptible Information**: all elements on the screen follow the same design
with a minimal UI, rounded corners and well thought out icons which are self-explanatory.

Huge thanks to Àlex for this awesome prototype, keep it up! Here are a couple of
screenshots of the UI:

![Search Results](https://user-images.githubusercontent.com/40824677/211171646-4f69c234-6b49-42a2-b879-471a07e21e7f.png)

![Map View](https://user-images.githubusercontent.com/40824677/211171644-a7e5d74f-b51f-4da2-bd8b-99a9791b95e6.png)

![Result Page - Top](https://user-images.githubusercontent.com/40824677/211171641-8eb79ace-484a-4ebb-86f3-78dc4f1c7949.png)

![Result Page - Bottom](https://user-images.githubusercontent.com/40824677/211171642-6d8bd99f-dd78-4a77-9393-4b111b37d0da.png)

## Accessibility Evaluation

To analyze the accessibility of the low-fidelity prototype created in
challenge 4, let us go over the *Universal Design Principles* to verify
if the prototype meets each of them:

- **Equality of Use**: the prototype has almost no responsible elements,
so they will look weird on non-desktop displays. This should not be the case.
- **Flexibility in Use**: the site allows for few user configurations:
other than the endless combination of filters the user can onable,
the user cannot do things like collapse the filter sidebar, enable
a dark mode or change the default font size.
- **Simple and Intuitive Design**: this principle is already present in my current
interface proposal, as the main page displays a simple search bar with not too many
confusing options, as well as icons for common actions like saving, sharing or
contacting display the common icons.
- **Perceptible Information**: the icons on the interface are all very much
self-explanatory and all menus on the interface follow the same design language.
Not much to improve here.
- **Tolerance of Error**: not currently implemented in the prototype, should be
added for cases like *search yields no results*, *user not logged in*, or
*invalid filter combination selected*.
- **Low Physical Effort**: All elements are displayed in the center of the page,
with no menus crawling to the sides where it is harder for users to reach with
a mouse. Good job on this part.
- **Size and Space for Approach and Use**: The UI is simple and intuitive to use,
but the layout could be redesigned a little bit, since there is a lot of space
between elements which is wasted, and the interview suggests that some information
was missing.

With all this done, in order to reach level `A` of accessibility it is important
to improve these areas:

- Add alternative text and titles to images, in case some image does not load
properly.
- Fix the issues with responsiveness, though it may be out of the scope of a
prototype of this kind.
- Add error messages when a user wants to perform a user-specific action such
as saving as favorite without being logged in, or when a search result
returns no results.
- Future prototypes should target wasted space and add missing information.
- Adding a short *undo* button after un-saving a house.

## Final Report

See the file [Final-Report-aperez-b.pdf](./Final-Report-aperez-b.pdf)

## Summary

In this fifth and final challenge, we have evaluated our prototype to see
if we have achieved substantial improvements or not. We have assessed
the improvement, both qualitatively and quantitatively, through the
user test. Through the *WCAG* accessibility guides, we have been able
to assess whether we are making the design accessible or not, noting
the improvements and changes so that they are not lost in future iterations
of the prototype. And finally, we have made a formal document
to present our work.

January 7th, 2023
