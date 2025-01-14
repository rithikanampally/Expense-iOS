<<<<<<< HEAD
# Expense-iOS
=======
![GitHub Cards Preview](https://github.com/PurnaJear06/Expense-iOS/blob/main/EXPENSO_COVER.png)

# Expenso
A Simple Expense Tracker App 📱 built to demonstrate the use of SwiftUI, CoreData, Charts, Biometrics (Face & Touch ID), Export CSV and MVVM Architecture 🏗.

<br />

<br />

## Light Mode 🌞
Dashboard | Face & Touch ID | All Income | All Expense | Add Transaction 
--- | --- | --- |--- |--- 
![](https://github.com/sameersyd/Expenso/blob/main/art/dashboard.png) | ![](https://github.com/sameersyd/Expenso-iOS/blob/main/art/auth_faceid.png) | ![](https://github.com/sameersyd/Expenso-iOS/blob/main/art/income_stat.png) | ![](https://github.com/sameersyd/Expenso-iOS/blob/main/art/expense_stat.png) | ![](https://github.com/sameersyd/Expenso-iOS/blob/main/art/add_transaction_attach.png) 

<br />

## Dark Mode 🌚
Dashboard | Face & Touch ID | All Income | All Expense | Add Transaction 
--- | --- | --- |--- |--- 
![](https://github.com/sameersyd/Expenso/blob/main/art/dashboard_dark.png) | ![](https://github.com/sameersyd/Expenso-iOS/blob/main/art/auth_faceid_dk.png) | ![](https://github.com/sameersyd/Expenso-iOS/blob/main/art/income_stat_dk.png) | ![](https://github.com/sameersyd/Expenso-iOS/blob/main/art/expense_stat_dk.png) | ![](https://github.com/sameersyd/Expenso-iOS/blob/main/art/add_transaction_attach_dark.png) 

<br />

## Built With 🛠
- [SwiftUI](https://developer.apple.com/documentation/swiftui/) - SwiftUI is an innovative, exceptionally simple way to build user interfaces across all Apple platforms with the power of Swift.
- [CoreData](https://developer.apple.com/documentation/coredata) - Framework used to manage the model layer objects in the application.
- [Figma](https://figma.com/) - Figma is a vector graphics editor and prototyping tool which is primarily web-based.

<br />

## Project Structure
    
    Expenso # Target
    |
    ├── CoreData            # CoreData ManagedObject
    |
    ├── view
    │   ├── main                    # Main root folder
    |   │   ├── view                # SwiftUI MainView
    |   │   └── viewmodel           # ViewModel for MainView
    │   ├── Expense                 # Expense root folder
    |   |   |__ ExpenseView         # ExpenseView (Dashboard)
    │   ├── AddExpense              # Add Expense root folder
    |   |   |__ AddExpense          # Add Expense
    │   ├── ExpenseDetailed         # Expense Details root folder
    |   |   |__ ExpenseDetailed     # Expense Details
    │   ├── ExpenseFilter           # Expense Filter root folder
    |   |   |__ ExpenseFilter       # Expense Filter
    │   ├── ExpenseSettings         # Expense Settings root folder
    |   |   |__ ExpenseSettings     # Expense Settings
    │   ├── About                   # About root folder
    |   |   |__ about               # About
    ├── Helpers                     # All extension functions


<br />
>>>>>>> 3c37c50 (Initial commit)
