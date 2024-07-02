React Native Shopping App
This React Native Shopping App is a user-friendly application that offers a seamless shopping experience. The Home screen showcases a variety of products, while the Cart screen enables users to conveniently view and manage their selected items. Navigation within the app is made easy with a bottom tab navigator, allowing quick switching between the Home and Cart screens.
Design Choices
Navigation

Bottom Tab Navigator: The app utilizes a bottom tab navigator for effortless navigation between the Home and Cart screens, ensuring an intuitive user experience.
Stack Navigator: Each tab (Home and Cart) is equipped with a stack navigator to handle smooth transitions within the respective screens. This design allows for easy scalability and the seamless addition of new screens within each tab.

UI Components

Home Screen: The Home screen presents a curated list of products, each displayed with clear images, names, descriptions, and prices for enhanced browsing.

Cart Screen: This screen displays the items that have been added to the cart. Each item in the cart includes the product image, name, description, price, and a remove button to delete the item. A Checkout button is provided for proceeding with the purchase.

Data Storage
The app utilizes AsyncStorage for storing cart data locally, allowing the contents of the cart to be saved between app sessions.
Implementation Details

Navigation Setup
The navigation system is established using @react-navigation/native, @react-navigation/stack, and @react-navigation/bottom-tabs. The app features a bottom tab navigator with two tabs: Home and Cart. Each tab utilizes a stack navigator to manage screens within the tab.

Data Storage with AsyncStorage
Cart data is efficiently stored using AsyncStorage. Upon app initialization, the cart data is fetched from AsyncStorage and displayed. Users have the ability to add or remove items from the cart, and any modifications are saved to AsyncStorage.
