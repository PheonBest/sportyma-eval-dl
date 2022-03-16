# sportyma-eval-dl
Showcase application to manage soccer clubs. /!\ Shown data is automatically generated, hence fake.

# Tools
The app was developped with Expo.
The used modules are:
* react-hook-form
* redux
* expo-image-picker
* react-navigation
* react-native-fontawesome (Icônes)
* react-native-gesture-handler (Boutons natifs)
* react-native-paper (DataTable)

# Data
The conceptual model is the following:
![Alt text](documentation/uml-sportyma-eval.drawio.png?raw=true "Modèle de données")

This app uses two datasets, which are soccer-wiki and world_countries_list.

# Functionalities
* Access to soccer clubs list.
* Access to players season history.
* Access to players statistics per club per season.
* Create a new club.
* Supports portait and landscape orientation.

# Screens
Home screen: list of soccer clubs.
On a click on a club, a page containing its details open with the club's players for the current season.
