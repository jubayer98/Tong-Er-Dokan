# Wholesale Marketing Executive App

This is an Android OS-based application developed primarily for wholesale marketing executives. The app enhances the flexibility of sales executives by allowing them to sell their products using their Android devices.

## Methodology

### Layout and Structure

The application consists of multiple activities, each with a distinct layout, designed to facilitate various functions within the app. In Android development, a layout refers to the graphical user interface of an application, similar to a GUI in Java.

### Java Classes

We used eleven different Java classes for this application:

- **Splash.java:** The main class that starts the program. It uses multithreading to display a welcome logo for five seconds before moving to the next class, `Welcome.java`. It handles exceptions using try-catch-finally blocks.
- **Welcome.java:** Activates `activity_welcome.xml` to welcome the user and request permission to start the program. It contains a start button that triggers an intent to move to the next layout.
- **SalesDiaryActivity.java:** Represents `activity_sales_diary.xml`, designed as a menu chart where users can choose products to sell. Different image buttons for different products enhance the application's flexibility.
- **Qucone.java, Qucup.java, Qustick.java, Quscoop.java:** Each class represents respective layouts (`activity_qucone.xml`, `activity_qucup.xml`, `activity_qu_stick.xml`, `activity_qu_scoop.xml`). These layouts function as memo charts where users can select quantities and calculate totals.
- **FinalDiaryCone.java, FinalDiaryCup.java, FinalDiaryScoop.java, FinalDiaryStick.java:** Final classes that perform tasks based on user choices, displaying virtual memos and providing an exit option.

### Functionality

- **Splash Screen:** Displays a welcome logo for five seconds using multithreading.
- **Welcome Screen:** Welcomes the user and starts the main activity upon permission.
- **Sales Diary:** Provides a menu to select products, with different image buttons for different products. Users can choose quantities and calculate totals.
- **Product Selection:** Allows users to select product quantities, calculates the total amount, and saves the quantities.
- **Final Diary:** Displays a virtual memo of selected items and provides an exit button to minimize the application.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/jubayer98/Tong-Er-Dokan.git
   cd Tong-Er-Dokan
   ```
2. **Open in Android Studio:** Import the project into Android Studio.
3. **Build and Run:** Compile and run the application on an Android device or emulator.

---

Enjoy using the Wholesale Marketing Executive App and streamline your sales process with ease!
