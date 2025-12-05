# LeafSaver  

LeafSaver is a user-friendly budget tracking application designed to help users manage their finances, set financial objectives, and analyze spending habits. With integrated photo-logging, detailed tracking, and insightful breakdowns, LeafSaver provides users with the tools they need to take full control of their money.


## Purpose of LeafSaver  

The primary goal of LeafSaver is to promote responsible financial habits by enabling users to:
- Track their expenses efficiently.
- Set and monitor monthly budget goals.
- Analyze spending categories and trends.
- Utilize gamification to enhance engagement and progress tracking.
- Reduce financial anxiety through structured expense management.

## Features  

### Core Features  
- **User Authentication:** Secure login with username and password.  
- **Expense Categories:** Custom categories for organizing expenses and budgets.  
- **Expense Entry:** Log expenses with details such as date, time range, description, and category, with optional photo attachments.  
- **Monthly Budget Goals:** Set and track minimum and maximum monthly spending limits.  
- **Expense History:** View recorded expenses over a user-selectable timeframe, including attached photos.  
- **Category-Based Spending Summary:** Visual representation of total spending per category.  
- **Spending Graph:** A graphical view of spending trends, comparing actual expenses to budget limits.  
- **Budget Goal Performance Tracking:** Progress bars and feedback graphics help users stay on track.  
- **Cloud-Based Storage:** Firebase-powered real-time data synchronization across devices.  
- **Gamification (Tree Mechanic):** Users earn points by following their budget, which can be redeemed for decorative fruits for their personal tree.  

### Unique Features  
- **Gamification – Tree Growing Mechanic:** Users collect points by adhering to their budget. These points can be spent on various fruit types to customize their virtual tree.  
- **Emergency Fund:** A designated fund for unexpected expenses, automatically managed within the app and allows the user to see their current emergency fund and history of the users savings within a selectable period, within the selectable period the user will be able to see the date, description and emergency fund saved.  
- **Rounding Up Savings:** Transactions can be rounded up to the nearest rand, with the difference contributing to savings.  

### AI Chatbot Integration  
LeafSaver now includes an AI-powered financial assistant, providing:  
- **Personalized Budgeting Advice:** Allows the user to ask question realting to how the app works and get responses based on the question.   

## Design Considerations  
- **Intuitive User Experience:** A clean and simple interface ensures accessibility for all users.  
- **Responsiveness:** Compatible with Android devices running API 35 or higher.  
- **Gamification:** Reinforces responsible financial behavior through engaging mechanics.  
- **Persistence:** Firebase Realtime Database ensures real-time synchronization and data integrity.  
- **Visual Feedback:** Graphs and summaries make complex financial data easy to understand.  

## GitHub Usage  
LeafSaver utilizes GitHub for:  
- **Code Sharing:** Collaborative development with multiple contributors working on different features.  
- **Version Control:** Managed through branches and pull requests to maintain clean commit history.  
- **Progress Tracking:** Organized commit messages for clear project updates.  

## Technologies Used  
- **Language:** Kotlin  
- **Database:** Firebase  
- **SDK:** Medium Phone API 35 (Android 15.0 “VanillaIceCream”)  
- **IDE:** Android Studio (Ladybug Feature Drop 2024.2.2)  

## How to Run  

To set up and run LeafSaver on your local development environment, follow these steps:

### 1. Clone the Repository  
Open a terminal or command prompt and run the following command to clone the GitHub repository:  
"```sh" 
git clone <repository-url
Replace <repository-url> with the actual URL of your GitHub repository.

### 2. Open the Project in Android Studio  
1. Launch **Android Studio (Ladybug Feature Drop 2024.2.2)**.  
2. Click **File > Open**, then navigate to the cloned repository and select the project folder.  
3. Allow the IDE to sync all dependencies and configurations automatically.  

### 3. Set Up the Emulator or Device  
- **Using an Emulator:**  
  - Go to **Tools > Device Manager** in Android Studio.  
  - Click **Create Virtual Device** and select a suitable Android device profile.  
  - Choose **Medium Phone API 35 (Android 15.0 "VanillaIceCream")** as the system image.  
  - Click **Finish**, then **Start** the emulator.  

- **Using a Physical Device:**  
  - Connect your Android device via USB and enable **USB Debugging** (found under Developer Options).  
  - Ensure the device runs **Android 15.0 ("VanillaIceCream") or higher**.  
  - Run the command below to check if the device is connected:  
    ```sh
    adb devices
    ```

### 4. Build the Project  
1. Click **File > Build > Clean Project** to remove any unnecessary build artifacts.  
2. Click **File > Build > Rebuild Project** to compile and prepare all components.  

### 5. Configure Firebase  
LeafSaver uses Firebase for authentication and real-time database storage. To ensure a successful setup:  
- Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).  
- Enable **Authentication** and **Realtime Database** services.  
- Download the **google-services.json** file and place it in the project’s **app** folder.  
- Sync Firebase dependencies by clicking **Tools > Firebase** in Android Studio and following the setup guide.  

### 6. Run the Application  
- Click the **Run** button in Android Studio (or press `Shift + F10`).  
- Select the desired emulator or physical device.  
- Wait for the app to build and deploy successfully.  

### 7. Testing & Debugging  
- Use **Logcat** (`View > Tool Windows > Logcat`) for debugging logs.  
- Perform test transactions to check the expense tracking, budget goal setup, and AI chatbot interactions.  
- Review data synchronization using the Firebase Realtime Database dashboard.  

Once everything is set up, you're ready to use LeafSaver and take control of your finances! 🚀  

## Requirements  
- Android device or emulator running Medium Phone API 35 (Android 15.0 “VanillaIceCream”) or later.  
- Android Studio (Ladybug Feature Drop 2024.2.2) or later.  
- Active Firebase configuration (Authentication database and Real-time database).  

## YouTube Video Link   
https://youtu.be/iEfxlqMol_s?feature=shared

