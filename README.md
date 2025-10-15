# PartnerLab2

Overview:

This lab is a SwiftUI memory game created by Aleks Lubczynski and Alex Teterin. The goal of this lab was to continue practicing SwiftUI interface programming while collaborating through Github.

Description:

The app is a car themed memory matching game where players tap the cards in order to reveal car images to try and match all of the pairs of two.

Project Demonstration:

Uses the _ObservedObject_ property to update the UI each time the game display changes.
The _LazyGrid_ layout is used to display the cards in a perfect area length matching the dimensions on the screen of the phone.

Main Components:

_EmojiMemoryGame_ acts as the view model which manages the game display and gives feedback to the UI. It interacts with the game model and reveals the card images into view when flipped.

_ContentView__ is the main interface which displays the game title, the grid of face up and down cards, as well as the tapping function in order to flip the cards to make the game work well.

_CardView_ represents how each of the cards look when it is faced up and shows the car image, when faced down it shows the blue background outer layer, and when its matched the cards disappear. 

Video Demo: 

Here is the link for the video showing the game working: 
