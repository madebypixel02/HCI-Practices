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
<!-- Created: 2022/12/21 07:08:22 by aperez-b                       +@@@%@   -->
<!-- Updated: 2022/12/27 18:11:59 by aperez-b                                -->
<!--                                                                         -->
<!-- *********************************************************************** -->

# 4. Generation: Low-fidelity prototyping

## Table of Contents

- [User Journey](#user-journey)
- [Prototyping](#prototyping)
- [Fundamental Concepts of HCI](#fundamental-concepts-of-hci)

## User Journey

### Happy Path 1

TASK: Search a house from the search box or from a map

| **Happy Path 1** | **Discovery** | **Consideration** | **Use** | **Fidelity** |
| :--------------: | :-----------: | :---------------: | :-----: | :----------: |
| **Objective** | Search from search box or from map | Think of where I want to find a house | Select a house from search results | Search for more results after the first one |
| **Touchpoints** | Load up the homepage and find a search box or map icon | Find some basic filtering options or suggestions | Open a search result by clicking on it | Quickly see a search bar from the search results to search some other house or place |
| **Actions** | Click on the search box and type in a place to find houses, press enter or the search button | Once it is clear where I want a house, select a few to see which one interests me more | On the results page, you will see a list of items representing houses with An icon on the left and a short description on the right. Press one to expand it or press a quick action button (save, set notifications, etc) | On top of the results page, the search bar remains, click on it again to make a new search. |

### Happy Path 2

TASK: Filter search results by features (parking, date, has pool, etc)

| **Happy Path 2** | **Discovery** | **Consideration** | **Use** | **Fidelity** |
| :--------------: | :-----------: | :---------------: | :-----: | :----------: |
| **Objective** | Filter search results to fine-tune them to the user's preference | Consider how many rooms I want, if I need parking, or pool, etc | Select compatible filters | Add multiple filtering options |
| **Touchpoints** | Select those filters that are the most important | Check all filtering options available on the page to see if some filtering options are missing | e.g. I cannot request an elevator on a single-floor room | I can choose more than one filter at a time, e.g. a flat with a garden, parking, built after `2015` |
| **Actions** | On the results page, look at the left-side panel. Check or move the sliders according to filtering needs. Press enter or `Apply` to apply the seclected filters | Find where the filtering is on the list. Check the type of filter. If it is a slider position selectors in the proper place, otherwise simply press the checkbox to select it. Press enter or `Apply` | Select a filter, other incompatible filters will become unavailable (greyed out) | Select a filter, then select another, and so on. Select as many as are available, if applicable, then press enter or `Apply` to apply the filters. |

### Happy Path 3

TASK: Save result as favorite, share, set price-drop alerts, etc

| **Happy Path 3** | **Discovery** | **Consideration** | **Use** | **Fidelity** |
| :--------------: | :-----------: | :---------------: | :-----: | :----------: |
| **Objective** | Set price-drop alerts for a house | Check which results from the list interest me the most | Share a house with friends | View or update my saved elements |
| **Touchpoints** | Select the house I want | View all options on the page and look for the sharing options | Get my friends' contact information, if required | Add or remove elements to my favorites list |
| **Actions** | Hover the mouse on an image result, press the bell icon. Enter my email address or allow in-browser notifications for said house | Hover a result from the results page. View available options: share, set price-drop alerts, save as favorite, etc. Select an action that I wish to do. | Hover the mouse on an image result, press the arrow button. Select the clipboard icon to copy the house link or enter a friend's email address. Press enter to send them relevant information about the house | Select the heart icon on the top of the page. A new popup will display the different elements on your list. You can modify them from there (change their tags or remove them from the favorites list) |

## Prototyping

Prototype link: **[here](https://www.justinmind.com/usernote/tests/72708202/74128913/74128917/index.html)**

Description: I added three pages corresponding to the three important features chosen in previous practicals. 
The first one is the home page where the user is met with a large map or a search box to search for houses.
After a search is made, the user is taken to the search results page. Here two results are shown as sample and
the user is allowed to click on the first one, as well as play with the various filtering options on the left
pane. When the user presses the image of the first result, they are taken to the third and last page, which
focuses this result on the page, and adds some extra buttons to save as favorite, enable price-drop alerts,
share, or contact the seller. The user can also look at a carousel of images corresponding to the different rooms
in the house.


Design Principles for All:

- **Simple and Intuitive Use**: The site is simple and has no unusual features. It hosts a search bar which is available
in every page in case the user wants to perform a new search. The search results are displayed in easy to view cards,
with only the most relevant information on them.
- **Equality of Use**: The site has accessibility titles for all elements that may be hard to grasp for some users;
images have a short description when focused or hovered with a mouse, making it easy for screen readers to announce to
visually-impaired people. Also, all buttons have a short tooltip as well to clarify their meaning.
- **Perceptible Information**: Most buttons on the site are universal icons, which make them self-explanatory. For example,
the envelope icon represents sending an email, the heart icon represents saving as favorite, the `less than` (`<`) buttons
represent going back, etc.

## Fundamental Concepts of HCI

Here are the main concepts used:

- **Metaphor**: Pressing on a heart to save an item colors it to indicate that such item has been marked as favorite.
- **Affordance**: There are self-explanatory buttons on the sidebar: "Construction", "Pool", "Parking", etc.
- **Visibility**: Writing a non-existent place will return an error explaining that no location was found with those terms.
- **Feedback**: Hovering search result images will enlarge them to let the user know it is focused and can be clicked.
- **Constraint**: When filtering by construction date, the maximum date you set cannot be lower than the minimum one.
- **Mental Model**: The homepage of the site is simple and well spaced, hosting a centered banner where the search input field is located, and there is a map above to search by area instead.

December 21st, 2022
