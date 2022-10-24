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
<!-- Created: 2022/10/24 19:59:40 by aperez-b                       +@@@%@   -->
<!-- Updated: 2022/10/24 21:30:38 by aperez-b                                -->
<!--                                                                         -->
<!-- *********************************************************************** -->

# Part 1: Research: Exploring the scenario

### Table of Contents

- [Introduction](#introduction)
- [User Profiles](#user-profiles)
- [Research about competitors](#research-about-competitors)
- [Basic Aspects of Human-Computer Interaction](#basic-aspects-of-human-computer-interaction)
- [Summary](#summary)

## Introduction

In this practical activity, we will be performing the initial steps to create a housing search tool that will allow user to buy, sell or rent different kinds of houses. We will start by first defining the users that will make use of our tool, then we will look at the competitors to see how they have implemented certain features, and lastly we will analyse certain aspects of Human-Computer Interaction. Let's begin!
 
To build the best possible alternative to current house-searching trends, we need too first look at what is already out there. We will apply the method of benchmarking to the following popular sites:

- [idealista](https://www.idealista.com)
- [Homes](https://www.homes.com)
- [Fotocasa](https://www.fotocasa.es)

## User Profiles

Every tool has a target audience. As described in the resources, designing form every type of user is defining for no user at all. Let us begin by defining some user profile to know the kind of people that can potentially be interested in buying/selling/renting a house.


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

## Research about competitors

We will analyze these tools by separating between different key features to see what some services have and don't have.

### Benchmaking

| **Analysis Criteria** | **idealista** | **Home** | **Fotocasa** |
| :-------------------: | :-----------: | :------: | :----------: |
| **Search to buy or rent a house** | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) |
| **Search by location**: using address | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) |
| **Search by location**: using custom area | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![NO](https://user-images.githubusercontent.com/40824677/197592783-54196969-a6a4-41f0-b079-f5210cb72026.png) | ![NO](https://user-images.githubusercontent.com/40824677/197592783-54196969-a6a4-41f0-b079-f5210cb72026.png) |
| **Search by location**: using map | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) |
| **Filter by**: number of rooms & bathrooms | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) |
| **Filter by**: year built | ![NO](https://user-images.githubusercontent.com/40824677/197592783-54196969-a6a4-41f0-b079-f5210cb72026.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![NO](https://user-images.githubusercontent.com/40824677/197592783-54196969-a6a4-41f0-b079-f5210cb72026.png) |
| **Filter by**: parking | ![NO](https://user-images.githubusercontent.com/40824677/197592783-54196969-a6a4-41f0-b079-f5210cb72026.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![NO](https://user-images.githubusercontent.com/40824677/197592783-54196969-a6a4-41f0-b079-f5210cb72026.png) |
| **Filter by**: extras (pool, garden, terrace, etc) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) |
| **Details & Description** | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) |
| **Action**: save as favorite | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) |
| **Action**: consulting opportunities | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) |
| **Action**: share an ad | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | N/A | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) |
| **Action**: price-drop alerts | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) | ![NO](https://user-images.githubusercontent.com/40824677/197592783-54196969-a6a4-41f0-b079-f5210cb72026.png) | ![YES](https://user-images.githubusercontent.com/40824677/197593067-f5d77580-5c16-4bb2-9181-40bee70a676f.png) |

### Main Insights

| **Positive Insights** | **Things to Avoid** |
| :-------------------: | :-----------------: |
| Powerful search engine: able to search using many different filters, date ranges, acessibility, number of rooms, pools, number of bathrooms, number of parking spots, dimensions, number of stories, ... | Limited free options to share ads, in order to be viewed by many you have to pay |
| Houses for every type of user: from a very small house to a shared flat or apartment to a large house with pool | No option to directly share on popular social media apps (Instagram, Twitter, Facebook) |
| Good social features: ability to like and share houses, save, and chat with the seller | The services all have different layouts which makes things harder for the user, services lack a more modern dark mode |

## Basic Aspects of Human-Computer Interaction

In this final section we will consider some key Human-Computer Interaction features in the three example services I selected, namely metaphor, affordance, visibility, feedback and mental model.

### idealista

[idealista](https://www.idealista.com) - Buscas casa? Con idealista es más fácil. Más de 1.400.000 anuncios de pisos y casas en venta o alquiler. Publicar anuncios es gratis para particulares.

- **Metaphor**: Pressing on a heart to save an item colors it to indicate that such item has been marked as favorite.
- **Affordance**: Hovering on buttons make their color slightly darker to let the user now they are within the activation targets of such button.
- **Visibility**: Writing a non-existent place will return an error explaining that no location was found with those terms, and may offer similar searches.
- **Feedback**: Hovering search result images will open sample videos of the houses, or show the photos of the house like a slideshow
- **Constraint**: Every house in the search results has a button on the corner of the image with the text "3D" except in cases when the seller has not included a 3D sample of the house.
- **Mental Model**: Links on this site follow the usual format of being underlined and blue.

![idealista](https://user-images.githubusercontent.com/40824677/197597167-94fe4d92-1256-488c-8566-0276014fc5b3.png)


### Homes

[Homes](https://www.homes.com) - Homes.com is where your home search begins. Search homes for sale, rental properties by city or neighborhood, and find out information on recent home sales.


- **Metaphor**: When not loggued in, there is a silouette of a person to indicate where the user should log in. When the user is logged in the profile picture appears instead of the generic icon.
- **Affordance**: There are self-explanatory buttons all over the site: "Search", "Next", "Send a Message", etc.
- **Visibility**: Search results are split into two panels, one displaying lists of houses matching the search criteria and another on the right showing the map with pins to the places from the search results.
- **Feedback**: Trying to contact a seller without being logged in will bring up a card to enter login information or to enter contact details without an account.
- **Constraint**: When filtering by price, the maximum price you set cannot be lower than the minimum one.
- **Mental Model**: The homepage of the site is perfectly spaced, hosting a centered banner where the search input field is located, and there are cards below it containing suggestions for homes.

![Homes](https://user-images.githubusercontent.com/40824677/197597827-b7618527-358b-40ee-8d6e-38f8775b6396.png)


### Fotocasa

[Fotocasa](https://www.fotocasa.es) - Más de 1.500.000 pisos en venta y alquiler, casas y apartamentos nuevos o de segunda mano.


- **Metaphor**: There is a bell that represents the notification panel in the top of the site. When new notifications arrive, the bell has a badge to indicate that there are new/unread notifications.
- **Affordance**: The search bar has a filtering option on the left that includes a down arrow to indicate that a menu can be expanded.
- **Visibility**: The site features a hamburger menu on the left for easy access to menus on mobile devices.
- **Feedback**: Visual feedback when loading search results, shows background dim card where the text and photos will appear later on.
- **Constraint**: If you hit the report button but try to send the report without entering an email will result in a toast message saying: "Please fill out this field.".
- **Mental Model**: The panel on the left has a smooth transition as the rest of the site gets darkened to indicate that it is not what the user should focus on.

![Fotocasa](https://user-images.githubusercontent.com/40824677/197606273-fd9132e2-a1b4-4a5a-86de-12dc5c2f7ba3.png)


## Summary

This was my first assignment for Human-Computer Interaction, I quite enjoyed it as it helped me to understand how pages should be designed from the ground up, and also to value the huge amounts of work and put behind every site to make sure they follow all these aforementioned standards.

Oct  24th, 2022
