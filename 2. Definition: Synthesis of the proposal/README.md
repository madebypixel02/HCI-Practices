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
<!-- Created: 2022/11/15 14:51:26 by aperez-b                       +@@@%@   -->
<!-- Updated: 2022/11/15 14:51:48 by aperez-b                                -->
<!--                                                                         -->
<!-- *********************************************************************** -->

# 2. Definition: Synthesis of the proposal  

## Table of Contents

- [Introduction](#introduction)
- [Flowchart](#flowchart)
- [User Testing](#user-testing)
  - [User 1](#user-1)
  - [User 2](#user-2)
  - [Reflections](#reflections)
- [Solutions Proposal](#solutions-proposal)
- [Summary](#summary)

## Introduction

In this second practice we will work on the first draft of our interface,
based on the research done on the previous practice. We will work on
this interface by creating a flowchart, performing user tests, and by
proposing our actual drafts of the interface, following the basic aspects
of Human-Computer Interaction.

In this practical activity I will focus on the following requirements:

1. Search for homes by location (maps, neighborhoods, municipalities, counties,
draw the search area on a map, etc.).
2. Check out homes based on their characteristics (number of rooms, bathrooms,
equipment, area, price, recently built construction, pool, parking, etc.).
3. Three actions should be related to homes, like saving as a favorite,
consulting opportunities, sharing an ad, or setting price drop alerts.

## Flowchart

### Search Homes by Location

  

![Search homes by location](https://user-images.githubusercontent.com/40824677/201877568-2b3a947d-c9f3-47f1-b5cb-742625cabe83.png)

The user will first type out the name of a place where they want to find
housing on a search box, if it is a specific address it will list only
results matching the address. If it is a Town or Country, the algorithm
will show recommendations based on previous searches or based on price
drops. In every case the user will see an option to draw an area on the
map to find housing in. If the search has no houses available or is
otherwise invalid, the user will be notified accordingly.

### Check Out Homes by Characteristics

  

![Check out homes by characteristics](https://user-images.githubusercontent.com/40824677/201883273-e4a74dc0-bfa9-4dd6-bc4e-b36cab70657b.png)

Once the user has found houses matching search results, they will be
able to filter results by filtering by number of rooms, price, bathrooms,
and other identifiers. On the search results page, the user will see a menu
on the side to tick or untick yes-or-no properties such as:

- Has pool?
- Has garden?
- Has elevator?
- Has basement?

Other filtering methods like prices, construction age, number of rooms,
or number of floors are numeric and should be filtered with a slider.

Every time the user changes the properties of a filter, the website will
automatically search for new results matching the new criteria. If no results
are available, the place where search results appear will be empty with a
message saying that no results were found matching the user's criteria. If
two or more filters are incompatible (e.g. having 5 floors in a flat,
elevator on house with single floor, etc), no results will be shown and an
error will be displayed.

### Actions Related to Homes

  

![Actions related to homes](https://user-images.githubusercontent.com/40824677/201890506-3f86ee84-c48b-4e26-b979-7318709221fe.jpg)

When a user hovers over the picture of a house, a small tooltip will appear
showing actions to save as favorite, share a link to the house, or notifications
for price drop alerts.

All of these actions will require the user to be loggud
in. If the user is not logged in, they will be taken to the login/signup page,
and after they are logged in the action they tried to perform will be done
automatically, so the user doesn't need to do it again. e.g. if the user tried
to save a house as favorite but was not logged in, they will go to the login page
and after logging in they will already have the house marked as favorite.

**Question**

How many steps does one have to do to complete each diagram and how muchs
time do you spends?

**Answer**

```txt
Diagram 1: took roughly 10 minutes to finish.
Diagram 2: took about 5 minutes to complete.
Diagram 3: this one took the longest, about 30 minutes.
```

Every flowchart has more or fewer steps to complete as the design gets more or
less complicated. The last one took so long since in order to design the process
of performing an action like setting price-drop notifications requires also
checking if the user has an account, which in itself requires asking the user if
they want to create a new account (if they do not have one).

**Question**

Is there only one way to complete the task? If a task can be completed in
different ways there should be branches.

**Answer**

If a task can be completed in several ways, it is better to use a different
flowchart to showcase the other ways to perform the task, because flowcharts
are only useful to visualize smaller tasks, and can get crowded very quickly.
For example, there are several ways in a website to access a login page
(from the homepage and from every action that requires a user to be logged
in), one cannot repeat itself and include how to log in or sign up for every
menu that has the option to do so.

**Question**

What issues are the most problematic in your opinion?

**Answer**

As I mentioned before, it is sometimes hard what to include on a diagram and
what not to include. There are several ways to access a certain menu on a site,
but it should not be repeated across multiple diagrams. Ideally, there would
be a single huge diagram where nothing is duplicated and everything is linked
and organized. But of course, such a diagram could fill a football stadium and
is therefore not practical for the real world.

**Question**

What issues are the clearest in your opinion?

**Answer**

Organizing the overall structure of the diagrams and keeping them concise was quite
challenging. We could go as deep as we wanted when it came to the diagram, so I decided
to keep things easy to understand while still including every important steps
in the tasks.

## User Testing

For this task I will contact two people matching two of the user profiles I created
last time. I will ask them some questions related to the UI of the three proposed
requirements, and some conclusions will be drawn afterwards. Some notes:


- For privacy reasons, I will use fake names instead of their real names.
- I didn't record the interviews; I only took some notes on the answers,
so the conversations don't show *exactly* the answers in the interview.

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

Alex: That's all folks! Thank you so much for this interview. I will let you
know how it goes once I finish it.
Patricia: You're welcome.
```

### Reflections

- As noted by Pablo, it should be possible to search houses by map from the get-go,
rather than after searching an area. That way the user can view other places of
interest nearby.
- As Pablo and Patricia mentioned, it is important to show the appropriate icons
in buttons. Oftentimes the user expects a certain icon to mean something in particular
(metaphor). Namely, an outward arrow will often mean *share*, or a bell icon will
often be associated with *notifications*.
- Like Pablo said, it is a good idea to not only save to favorites, but also to
save to other user-defined lists. I think the best approach is to save as favorites,
with the option to create and add tags to every search.

  
- The rest appears to be fine for now.

## Solutions Proposal

Here are my (mostly) hand-drawn sketches of the three features in action.

![Main Screen - Search box and map](https://user-images.githubusercontent.com/40824677/201931275-7581e162-4b8a-4ef9-9510-3e003a411563.png)

  

![Search Results - Filtering options](https://user-images.githubusercontent.com/40824677/201931265-080f23cf-19de-4e02-8d64-07183904c2d5.png)

![Search Result - Tooltip options (save, share, notify, contact)](https://user-images.githubusercontent.com/40824677/201931254-1ed1c8e7-4b8a-4660-929c-99c4de5a416a.png)

## Summary

This second practice was quite interesting. We had to design our own draft interface
for certain menus, and that was challenging considering my terrible drawing
abilities. It helped me understand and value the effort put behind every UI :)

November 13th, 2022
