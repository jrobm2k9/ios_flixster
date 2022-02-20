# Flixster

Flixster is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flixster Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF
<img src="https://i.imgur.com/Sbr8eza.gif" width=250><br>

### Notes
I had trouble with the interitem spacing, I followed the instructions exactly but it still had a giant space in between the 2 columns.  I searched the discussion page and found another user that had the same issues I had and used the code that was posted as a solution and it worked.

---

## Flixster Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [x] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="https://i.imgur.com/svJBmTF.gif" width=250><br>

### Notes 
Required: ignore typos

Where do I begin?!?! The biggest challenge I had was with the AlamofireImage package, it kept throwing an error.  The error was "This statement is ambiguous without more context" and it pointed to a file "combine.swift" in the alamofireimage package.  After a bit of research, I decided to delete the file because it was not a required file, but after that, the error again reared its ugly head in the httpheader swift file in that same package.  So, I spent hours searching the web, i completely re-did the project 3...............(pause for gasp)............. 3 times, the first and second time, I received the same error.  I reached out to CodePath help, they made good suggestions, but it didn't resolve the issue.  As I was nearing my breaking point, I decided to delete xcode and reinstall it ("turn it off and back on again" - generic helpdesk), after resinstalling it, I had the same error.  At this point, I was done, I had pretty much given up, it was already past the due date and nothing was working, BUT, I received a message saying that I could submit it at a later date!  This sparked my enthusiasm, I was determined to find the cause so that I could help another in my same predicament.  I started xcode...... opened my project....... checked the areas that were recommended by the CodePath help (all good), made some changes to the main.storyboard and wallah!!!! It built!! This is one of those programmer memes where you didn't much, if anything at all, and the code suddenly works.  Maybe my mac had had it with me and wanted to put me through a little turmoil or maybe I'm just bad at this, either way, it works now, it's late, I'm tired, mentally, goodni......zzzzZZZZzzzzzz

