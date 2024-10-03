This Flutter app displays a list of products with details like an image, title, description, and price.

The app consists of multiple components:

ProductApp (main.dart):
This is the main entry point of the application. It wraps the app inside the MaterialApp and sets the home screen to ProductListScreen. It also sets the app theme.

ProductListScreen:
Displays a list of products using a ListView.builder(). Each product is represented by a ProductTile widget that shows basic information (title, description, price, and image). When tapped, it navigates to the ProductDetailScreen.

ProductTile:
Displays individual product information within a card layout. It shows a product’s image, title, description, and price. Tapping a tile navigates the user to a detailed view of the product (ProductDetailScreen).

ProductDetailScreen:
Shows detailed information about a single product. The screen includes a large image, the product's title, price, and description.

Product model:
A data class that defines the properties of a product: id, title, description, price, and imageUrl.

What i learned from this Applcation:

App Structure in Flutter:
I learned how to organize a Flutter app using multiple screens (ProductListScreen, ProductDetailScreen) and widgets (ProductTile).

Navigation in Flutter
I saw how to navigate between screens using Navigator.push() to move from a list view to a detailed view.

ListView and ListTile:
I explored using ListView.builder() to dynamically build a list of items and display them using ListTile.

State Management:
While this app doesn’t have complex state management, I learned how to pass data (Product) between screens using the constructor.

Network Images and Layout:
I learned how to fetch and display images from the internet using Image.network() and manage layout with Flutter’s BoxFit and SizedBox.
