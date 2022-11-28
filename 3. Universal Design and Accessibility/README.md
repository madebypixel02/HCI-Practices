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
<!-- Created: 2022/11/28 16:36:53 by aperez-b                       +@@@%@   -->
<!-- Updated: 2022/11/28 20:05:55 by aperez-b                                -->
<!--                                                                         -->
<!-- *********************************************************************** -->

# 3. Universal Design and Accessibility

## Table of Contents

- [Introduction](#introduction)
- [3.1. Universal Design Principles](#31-universal-design-principles)
- [3.2. Accessibility Evaluation](#32-accessibility-evaluation)
- [3.3. Accessibility Levels](#33-accessibility-levels)

## Introduction

The time has come to start the Generation stage, in which we will analyze the 7
principles of universal design to evaluate applications following the [*WCAG* guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/)
and accessibility tools.

Universal design refers to the design of products and environments to be used by
all people, to the greatest extent possible, without the need for adaptation
or specialized design. On the other hand, accessibility is used to describe
whether the design of a product, device or service can be used by people
of all abilities.

## 3.1. Universal Design Principles

### 3.1.1

Analyze the applicability of the **7 design principles for everyone** to evaluate
the applications of the case study. The document illustrates each principle with
a screenshot and justifies its application (It is not necessary that the 7
principles apply to the same application. If you prefer, you can use examples
from other apps or websites that you use for this type of service).

### Answer 3.1.1

Here are the *Universal Design Principles* and an example from the case study
for each of them:

- **Equality of Use**: *Homes* has a responsive interface, which means that
content will adapt to the size of the screen or window where the site is displayed.
The principle of equality of use is met on this site because, among other things,
content is *equally* accessible for users on desktop and smaller screens, with clear
layouts when resizing the browser window. This allows for users to enjoy a more unified
website experience across devices.

- **Flexibility in Use**: *Fotocasa* features a sidebar which can be expanded
and collapsed. This is a great expample of flexibility in use as the site could
have had a permanent sidebar,but rather chose to let their users access that
menu separately so as not to crowd the main page of the site with
not-so-important menus.

- **Simple and Intuitive Use**: *Idealista*'s homepage is rather simple,
it hosts a clear and concise header and footer, with the main focus of the
page on the large search bar. This search only has basic filtering options
such as a selector for buying or renting, searching for homes or specific
rooms in houses, and all is generally very easy for the average user (and even newcomers)
to understand without issues. A user that wants to use a homeseeker will *never*
get lost on a homepage like this, where the first thing you will do is search
for an area where you'd like to buy/rent a house.

- **Perceptible Information**: *yaencontre* has an option to open a map to
define an area to find homes. This option is easily found on their main
page, and is easily visible beacuse it uses a simple drawing of a map
with small price tags representing various houses on the map for sale. This is
a very clear way of presenting and showing the users how to access the map search
feature of the page. Small graphics and icons on this site do a great job of explaining
what various parts of the site do in a way that any user will find easy to understand.

- **Tolerance for Error**: *Homes* has the ability of saving places as favorite,
and as expected only allows users to save places from search results as favorite
provided that they are signed in with an account. If the user does not have an account,
a window pops up taking the main focus of the page saying *Uh Oh! Something went
wrong*, instead of performing some other unexpected error.

- **Low Physical Effort**: *Fotocasa*'s mobile interface is well thought out in
the sense that the user does not have to move their finger across the whole
screen to access the contents of the site. That way the user does not have
to press some things on the top of the window, others on the bottom of the
page, and some things with multiple fingers. The site simply keeps the
search bar and filters at the top and lists homes from search results
in a way that is easy to scroll through with a touchscreen. It is also
a good idea to keep the search bar at the top and not at the bottom of the
screen since most phones have a bottom navigation bar with navigation
gestures, so having a bottom bar or bottom buttons would likely overlap
and conflict with the system's gestures.

- **Size and Space for Approach and Use**: *Idealista* makes very good use of
both size and space on their site. They Have simple buttons with large targets
which allows any user (regardless of age, gender, disabilities, etc) on any device
(desktop with or without keyboard/mouse, smartphones, smartwatches) in any circumstance
(user sitting down, in motion) to use the site with no major complications.

### 3.1.2

Explain and draw how it is possible to **incorporate in your proposed solutions**
for the practice (challenge 2) criteria of **equality of use**, **tolerance of errors**
and that it complies with a **simple and intuitive design**.

### Answer 3.1.2

- **Equality of Use**: To facilitate users with vision impairments, it is a good
idea to add alternative (alt) text to images as well as transcripts for videos so
that screen readers will explain the content, thus unifying the website experience
for all users.

![Video Captions and Read Aloud mode](https://user-images.githubusercontent.com/40824677/204353865-3251dd1a-4143-40bd-8518-1eb0e6ca77d3.png)

- **Tolerance of Errors**: Sometimes a user will accidentally remove a house from
their list of favorites. To avoid issues like these it is a good idea to add a
small toast message to let the user undo certain important actions such as
unsaving a home or discarding an unsent message to a home seller.

![Undo Remove from favorites](https://user-images.githubusercontent.com/40824677/204356132-188694f8-67f6-4e2d-ace1-f7a075ae57c7.png)

- **Simple and Intuitive Design**: this principle is already present in my current
interface proposal, as the main page displays a simple search bar with not too many
confusing options, as well as icons for common actions like saving, sharing or
contacting display the common icons.

![Main Screen - Search box and map](https://user-images.githubusercontent.com/40824677/201931275-7581e162-4b8a-4ef9-9510-3e003a411563.png)

![Search Result - Tooltip options (save, share, notify, contact)](https://user-images.githubusercontent.com/40824677/201931254-1ed1c8e7-4b8a-4660-929c-99c4de5a416a.png)

## 3.2. Accessibility Evaluation

To do assessment analysis, you can make use of online
[*WCAG*](https://www.w3.org/WAI/standards-guidelines/wcag/) compliance review or
validation tools such as *TAW* and *WAVE*. Or, if you prefer, you will find attached
the reports generated with *TAW* level *AA*, with which you can carry out the analysis.

Choose three reports (out of three applications) and analyze compliance with *WCAG*
Perceivable (*A*) and Operable (*AA*) accessibility levels. On the basis of this
result, an accessibility evaluation analysis is prepared that includes:

1. In the three applications analyzed, what are the most common warnings you have
had to manually review?
2. Provide a solution for 3 failed points. The points must be different.
3. Provide examples of two characteristics that do not comply with each principle
(Perceivable and Operable), indicating the level of accessibility (*A*, *AA*).

## Answer 3.2

I will base my *Accessibility Evaluation* of the *WCAG* guideline compliance on
the **TAW** report for the sites *century21global.com*, *metrocuadrado.com* and
*habitaclia.com*

1. After checking out the three reports, there were multiple which appeared on
all three sites. The clear most common warnings on the sites were related to forms.
Things like *suggestions for incorrect values in forms*, *Identify values to be filled
in with special formats* or *prevent errors in legal, financial or data forms* were
common among the three reports, shown as warnings. Also, there were shared warnings
related to links having the same text but different href (link).
2. Here are three errors present on the reports and a possible (though not unique)
solution to them:

    - **Two headers of the same level with no content in between**: add some content
between the two headers or re-evaluate if the headers make sense in the first place.
Perhaps it is better to replace the headers with some formatted text with the
help of a `<span>` *HTML* element.
    - **Presence of empty lists**: the solution really depents on what the list represents
on the page. Perhaps the main navigation menu is made of a list `<ul>` with `<a>`
elements inside. If something like this were the case, the solution would be the
simplest: add the missing `<li>` elements wrapped around every `<a>` tag. If the
list served some other purpose it would be necessary to assess the semantic value
of that element on the page and whether or not it should be changed or deleted
alltogether.
    - **Images without "alt" attribute**: this time the solution is rather trivial:
add the missing alternative text to the image. This text is crucial in case the
image cannot be loaded and is also necessary for screen readers to detail the
content of the image for users with vision impairments to get a general idea
of what is displayed. This is why there is another check on the validation tool
named *Images that may require a long description*, made to ensure certain
images get a proper (lengthy) description.

3. Here are two examples of characteristics that failed compliance with *WCAG*
Perceivable (*A*) and Operable (*AA*) accessibility levels:

    - Perceivable (*A*)
      - Non-Existence of *h1* element (*century21global.com*)
      - *Form controls without associated label* (*metrocuadrado.com*)
    - Operable (*A*)
      - *Empty Links* (*habitaclia.com*)
      - *Appropriate content of headers and labels* (*metrocuadrado.com*)

## 3.3. Accessibility Levels

Now that we are clear about the critical concepts of accessibility, review the
proposal that you have drawn in challenge 2 and **incorporate at least 3 improvements**
that you have to make to meet accessibility **level *A*** of the **Perceivable**
key concept.

## Answer 3.3

Here are my three proposed improvements:

1. In cases where a house result has a demo video with sound, ensure it can be paused,
seeked, and that its volume can be changed inside the browser without changing the system
volume (*WCAG Success Criterion 1.4.2 Audio Control*).
2. Ignore alt text for images and other non-text that does not need to be readed by a screen
reader since it does not provide meaningful information to the user relying on a screen reader
(*WCAG Success Criterion 1.1.1 Non-text Content*).
3. If a search yields no results, provide the user with recommended results or alternative/similar
searches (*WCAG Success Criterion 3.3.3 Error Suggestion*).

November 28th, 2022
