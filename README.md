# rn-assignment6-11094101

## Design Choices

I used a combination of React Native components to implement the UI Design. I chose to use a FlatList to display the cart items, and a TouchableOpacity to handle the remove item functionality. I also used Ionicons to display the bag icon in the checkout bar.

## Data Storage

I used AsyncStorage to store the cart items. I implemented a function to load the cart items from storage when the component mounts and update the state accordingly. This allows the application to persist the cart items even when the user closes the app.

### Loading Cart Items

I implemented a function loadCartItems to load the cart items from storage when the component mounts. This function retrieves the cart items from storage and updates the state accordingly.

### Updating Cart Items

When the user removes an item from the cart, I update the cart items in storage using the AsyncStorage.setItem method.

## Screenshots

![345081996-88b5bc55-a621-4b21-8b88-38cbf4d2f94e](https://github.com/AdamsDawood/rn-assignment6-11094101/assets/172335697/9ea5985d-edb1-4ec6-bd4b-e2a5fdd4ecc3)
![345082113-d3c41829-90b0-458a-a408-1b193e842733](https://github.com/AdamsDawood/rn-assignment6-11094101/assets/172335697/955d406d-7477-47e2-8107-762bc41b1fac)
