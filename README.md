Project Description
Overview
This is a React Native e-commerce application designed to provide a seamless shopping experience. The app features a comprehensive product listing, detailed product views, and a functional shopping cart with local storage capabilities. Users can browse products, view detailed information, add items to their cart, and manage their selections.

Key Features
HomeScreen:

Displays a list of available products fetched from an external API.
Provides navigation to detailed product views.
Includes a header with a logo, menu, search, and cart icons.
ProductDetailScreen:

Shows detailed information about a selected product.
Allows users to add the product to their cart.
Displays material and shipping information.
CartScreen:

Displays items added to the cart.
Allows users to remove items from the cart.
Calculates and shows the estimated total cost.
Provides a checkout button to navigate back to the HomeScreen.
Technologies Used
React Native: For building the user interface and navigation.
AsyncStorage: For local storage of cart items, ensuring data persistence across sessions.
Fetch API: For fetching product data from an external API.
React Navigation: For navigating between different screens in the app.
UI Elements
FlatList: For rendering product lists and cart items efficiently.
TouchableOpacity: For creating interactive buttons and clickable elements.
Image: For displaying product images and icons.
Text: For displaying textual information about products and cart items.
Navigation
The app uses a stack navigator to transition between the HomeScreen, ProductDetailScreen, and CartScreen, providing a smooth and intuitive navigation experience.

Local Storage
The cart items are stored locally on the device using AsyncStorage, ensuring that the user's selections are preserved even if the app is closed and reopened.

External API
The product data is fetched from Fake Store API, which provides a variety of products for display in the app.

Usage
HomeScreen: Browse through the list of products. Click on a product to view its details.
ProductDetailScreen: View detailed information about the selected product. Click the "ADD TO BASKET" button to add the product to your cart.
CartScreen: View items in your cart, remove items if needed, and see the total cost. Click "CHECKOUT" to navigate back to the HomeScreen.
This app provides a solid foundation for an e-commerce application, demonstrating key functionalities such as product listing, detailed views, cart management, and local storage.
