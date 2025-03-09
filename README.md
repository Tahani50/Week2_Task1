# SwiftUI Animated List App

## Overview
This SwiftUI app displays a list of players with images and text. Users can navigate to a detailed view for each player and add or remove players dynamically with smooth animations.

## Features
- **List Implementation:** Uses `List` to display an array of player items.
- **Custom Cells:** Each list item includes an image and text.
- **Navigation:** Implements `NavigationStack` and `NavigationLink` to open a detail view when a player is selected.
- **Data Flow:** Passes player data to the detail screen.
- **Animations:** Smooth animations when adding or deleting items.
- **Interactions:** Uses `.onTapGesture()` to interact with the list.

## How It Works
1. **Displaying Players:**
   - The app initializes with a predefined list of players.
   - Each player is displayed in a custom cell containing an image and text.
   
2. **Navigation:**
   - Tapping a player in the list navigates to a detail screen displaying the player's full information.

3. **Adding Players:**
   - A button in the navigation bar allows users to add a new player.
   - Users enter player details in a form and add the player to the list.
   - The new player appears in the list with an animation.

4. **Deleting Players:**
   - Players can be removed from the list using the swipe-to-delete action.
   - The deletion is animated for a smooth user experience.

## Technologies Used
- **SwiftUI** for UI design
- **NavigationStack & NavigationLink** for navigation
- **@State & @ObservedObject** for state management
- **Animations** to enhance user experience

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/swiftui-animated-list-app.git
   ```
2. Open the project in Xcode.
3. Run the app on the iOS simulator or a real device.

