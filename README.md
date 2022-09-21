# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [X] (5pts) User can tap a cell to see more details about a particular movie.
- [X] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="http://g.recordit.co/7e8sH2EnTP.gif" width=250><br>

### Notes
**Describe any challenges encountered while building the app.**
This part of the app was far more difficult. I spent several hours troubleshooting the "This Class is not Key Value Coding-Compliant for the Key" and "Failed to instantiate the default view controller for UIMainStoryboardFile" errors. I tried reconnecting the storyboard to the outlets, but eventually restarted the full second part of the Flix app from scratch. This was a learning moment for me to create a feature branch in my repository to help with debugging, troubleshooting, and fixing my challenges more efficiently and effectively. 
---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [X] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [X] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [X] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [X] (2pt) User can view the app on various device sizes and orientations.
- [X] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="http://g.recordit.co/KAmn7dcfrW.gif" width=250><br>

### Notes
**Describe any challenges encountered while building the app.**
Scaling the app for different sized devices proved to be rather difficult, especially since I could not figure out how to have multiple live previews of different devices. I was also unable to get the app to stretch across the entire screen when in landscape mode. 
