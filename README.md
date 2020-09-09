![GitHub Logo](https://skincity.se/themes/skincity_ver2.0/design/bilder/butik/logo_skincity.svg)

# Skincity Dev Test

Create a server (with a js library of your choosing). Have an endpoint return a list of skin types: 

```json
[
  {
    "id": "9238482347",
    "name": "Dry",
    "image": "https://services.skincity.com/api/askas-facade/includes/images/general/1512547141D7qEO.jpg"
  },
  {
    "id": "9238482347",
    "name": "Oily",
    "image": "https://services.skincity.com/api/askas-facade/includes/images/general/1512547136QFFLd.jpg"
  },
  {
    "id": "9238482347",
    "name": "Normal",
    "image": "https://services.skincity.com/api/askas-facade/includes/images/general/1512547130yNABP.jpg"
  },
]
``` 

The list returned is to be visualized in a react app using redux. Retrieve the list and add it to the redux store. Show a dropdown with the skin types names. When a new skin type is selected, update the redux store and visualize the selected types image. 

(If you have time setup a db where each array item is a row in a table and create an entity mapping to this table)
