# Expense Tracker App

This is an Expense Tracker App built with Swift, SwiftUI, and Supabase(similar to firebase) to help users manage their expenses by tracking their spending in different categories. The UI is based off of the now discountinued app "Mint." 
The app's main view features a chart that track's the monthly spending history of a user. If you drag over the chart line, you are able to see the history of total spending per specific day of the month. 

It also features the most recent transactions that occoured as well, categorized (transportation, restaurant, etc.) showing details of the merchant, date, and amount. The amount is positive if it is a credit transaction and negative if
it is a debit transaction. The icons are loaded from a third party library; SWIFTUIFontIcon. The app also features a light and dark mode and uses supabase to handle use authentication for tracking transactions specific to a user.

The user interface is clean and intuitive, optimized for IOS devices.

# Prerequisites
Make sure you have the following installed on your machine:

Xcode (version 12 or above)
macOS (Catalina or above)


# Installation
Open your terminal and run the following command to clone the repository: git clone https://github.com/abdulcodes0174/Expense_tracker_app.git

Navigate to the project directory: cd Expense_tracker_app

Open the Project in XCode by: Typing open Expense_tracker_app.xcodeproj in the terminal
OR alternatively you can double-click the Expense_tracker_app.xcodeproj file in Finder

Install Dependencies (if required): 
Since this project utilizes Swift Package Manager (SPM) to manage dependencies, to update to the latest package versions, follow these steps in Xcode:

- Go to File > Swift Packages > Update to Latest Package Versions.

# Running the App
Select your target device or use an iOS simulator.
Press Cmd + R or click the "Run" button in Xcode to build and launch the app.
You should see the Expense Tracker App interface on the simulator or device.

# Usage
Open the app.
Sign in.
Use the "Add Transaction" button to record new expenses.
Browse through recent transactions and analyze spending patterns.
