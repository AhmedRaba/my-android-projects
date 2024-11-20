# My Android Projects Collection 🚀

This repository contains a collection of Android applications that I have developed as part of my portfolio, showcasing a range of modern Android development practices and technologies.

# [CryptoTracker](https://github.com/AhmedRaba/CryptoTracker) 📊  

A sleek and modern cryptocurrency tracking app built using **Jetpack Compose**. The app provides a list of cryptocurrencies with key details like market cap, price, and 24-hour changes. It also adapts to landscape mode to display both the coin list and detailed information on the same screen, utilizing **Adaptive Navigation** for an optimized user experience.

This app was developed as part of **Philipp Lackner’s course**, *The Best Practice Guide to Android Architecture*, showcasing the latest best practices in Android development.


## Features ✨  
- 📋 **Cryptocurrency List**: Displays a list of cryptocurrencies with real-time data, including:
  - Market Cap
  - Current Price
  - 24-Hour Change
- 📱 **Adaptive Navigation**:
  - **Portrait Mode**: View the list or coin details individually.
  - **Landscape Mode**: View both the list and selected coin details side by side for a master-detail experience.
- 🧼 **Clean Architecture**: Ensures a modular, maintainable, and testable codebase.
- 🚀 **Reactive and Modern Design** with MVI pattern.


## Screenshots 📷  

<div align="center">

| Coin List Screen                      | Coin Details Screen               |
|------------------------------------|--------------------------------------|
| <img src="https://github.com/user-attachments/assets/f5320169-5651-4ab1-bcda-9e60e8ff585f" alt="Category Screen" width="300"/> | <img src="https://github.com/user-attachments/assets/a9c56f7d-64d6-4d6a-8eb7-ce701882b1fc" alt="News Details Screen" width="300"/> |

| Landscape Screen                     |
|------------------------------------|
| <img src="https://github.com/user-attachments/assets/4b55dcfe-929f-4b63-915a-ebc14561c108" alt="Drawer Screen" width="700"/> |


</div>


## Demo 🎥  
<div align="center">

https://github.com/user-attachments/assets/199f1549-8ae8-40d6-acb5-b04fd3d5d99d

</div>


## Technologies Used 🛠️  

- **Jetpack Compose**: For building modern, declarative UIs.  
- **Kotlin**: A concise and expressive programming language.  
- **Koin**: For dependency injection, keeping the app modular and testable.  
- **Ktor**: For seamless API integration to fetch cryptocurrency data.  
- **Adaptive Navigation**: To provide context-aware navigation for different screen orientations.  
- **MVI Architecture**: Ensures unidirectional data flow and scalability.  
- **Clean Architecture**: A modular approach with clear separation of concerns.  


## How It Works ⚙️  

1. **API Integration**: Fetches live cryptocurrency data using **Ktor**.  
2. **Dependency Injection**: Managed with **Koin** for clean code structure.  
3. **Reactive UI**: Updates dynamically using Jetpack Compose and MVI.  
4. **Adaptive Navigation**:  
   - **Portrait Mode**: Focused experience with a single screen at a time.  
   - **Landscape Mode**: Enhanced experience with a split-screen layout for coin list and details.  

---

# [NewsApp](https://github.com/AhmedRaba/NewsApp) 📰

Welcome to **NewsApp**! This Android application allows you to stay updated with the latest news from various categories and sources.

## Screenshots

<div align="center">

| Category Screen                    | News Screen                          |
|------------------------------------|--------------------------------------|
| <img src="https://github.com/user-attachments/assets/dbc1e724-2e3a-4cda-a4eb-3e9d9b6a85b2" alt="Category Screen" width="300"/> | <img src="https://github.com/user-attachments/assets/4f1ce9db-e50d-40c5-85e1-56e9f1584a84" alt="News Screen" width="300"/> |

| News Details Screen                | Settings Screen                      |
|------------------------------------|--------------------------------------|
| <img src="https://github.com/user-attachments/assets/3b10b4e4-afdf-4652-b01b-abec1fc09a39" alt="News Details Screen" width="300"/> | <img src="https://github.com/user-attachments/assets/14b9d7f8-182f-4490-8ad6-f1aec5e59be4" alt="Settings Screen" width="300"/> |

| Drawer Screen                      | Arabic Category Screen               |
|------------------------------------|--------------------------------------|
| <img src="https://github.com/user-attachments/assets/98b4f2fd-89eb-4c23-a765-5df7bcc68712" alt="Drawer Screen" width="300"/> | <img src="https://github.com/user-attachments/assets/837e4180-173e-4ab6-a94f-6cdced72ba71" alt="Arabic Category Screen" width="300"/> |

</div>

## App Demo 🎥

Check out the video below to see the app in action!

<div align="center">
   

https://github.com/user-attachments/assets/88494c99-d998-439f-9daa-c50b7e9d6ebc


</div>

## Key Features 🌟

- **MVVM Architecture**: Follows the Model-View-ViewModel design pattern for a clean separation of concerns.
- **Repository Pattern**: Manages data operations, providing a unified API for accessing data from multiple sources such as RoomDB and network requests.
- **Caching with RoomDB**: Efficiently store news articles offline for quick access.
- **Retrofit Integration**: Fetch news data from multiple sources seamlessly.
- **Search Functionality**: Easily search for news articles by category or source.
- **Language Support**: Change the app's language to suit your preferences. 🌍

## Tech Stack ⚙️

- **Kotlin**: For building the Android application.
- **Room**: For local database management.
- **Retrofit**: For network operations and API calls.
- **MVVM**: For architecture design.
- **Dagger Hilt**: For dependency injection.
- **Coroutines**: For handling asynchronous tasks.

Feel free to explore the code and contribute to the project! 🚀


---

# [DevStore](https://github.com/AhmedRaba/DevStore) 

Welcome to Codespire, a Dev Store app designed to manage and sell coding projects across various categories. This Android application includes features for user authentication, project ratings, and secure payments.
this is my graduation project which i got (A) for it

## Features 🌟

- **User Authentication:** Register, log in, and manage user sessions securely. 🔒
- **Project Management:** Browse, search, and view coding projects across different categories. 📁
- **Project Ratings:** Rate projects and view ratings from other users. ⭐
- **Payment Integration:** Handle payments securely with integrated payment methods. 💳
- **Navigation:** Seamless navigation using a BottomNavigationView. 🧭

## Technologies Used 🛠️

- **Retrofit:** For network operations and API integration. 🌐
- **SharedPreferences:** For storing user sessions and preferences. 🗃️
- **MVVM (Model-View-ViewModel):** Ensures a clean architecture and separation of concerns. 📊
- **Navigation Component:** Manages app navigation efficiently. 🗺️
- **Material Design:** Provides a modern and intuitive user interface. 🎨
- **Coroutines:** Handles asynchronous operations smoothly. ⏳


## Project Demo 🎥

See the Dev Store app in action with this demonstration video:
[Link to Demo Video](https://drive.google.com/file/d/1acc2kCVpB-UGK5SZIRy751ioOpXG1S9K/view?usp=drive_link)



---

# [QuoteApp](https://github.com/AhmedRaba/QuoteApp) - Inspirational Quotes Application

**QuoteApp** is an Android application that uses Retrofit to fetch quotes from Api Ninjas.

This Android app allows users to manage quotes, including adding, viewing, and deleting them. It utilizes Room for local data storage and offers a user-friendly interface.

 <div align="center">
  <video src="https://github.com/AhmedRaba/QuoteApp/assets/83189595/7a807100-43ef-459c-b503-f79b5619c6b9" width="400" />
</div>



## Features

* Fetch quotes from API Ninjas
* Add new quotes with the author to favorites.
* Share quotes via social media or messaging apps
* Choose from different quote categories (e.g., Inspirational, Love, Success, etc.)
* View a list of all quotes you saved.
* Unfavorite saved quotes.
* User-friendly interface with Material Design
* Save quotes as images.

## Technologies Used

* Retrofit
* Room Database
* MVVM
* Navigation component
* Material Design
* Coroutines
* Dagger Hilt

----

# [To-Do List App](https://github.com/AhmedRaba/TodoApp) 📝

A simple and intuitive To-Do List app that allows users to manage tasks efficiently. Users can add tasks based on selected dates, update tasks, and delete them as needed. Designed with a focus on clean architecture and modern Android development practices.


## Screenshots

<div align="center">

| Tasks List                            | Add Task                           |
|------------------------------------|--------------------------------------|
| <img src="https://github.com/user-attachments/assets/a6572b9d-77e5-4de4-99db-d0626eda36f6" alt="Tasks List" width="300" style="border: 1px solid #ccc; padding: 5px;"/>  | <img src="https://github.com/user-attachments/assets/b03b8acd-285b-4cbf-9ea3-7f7b0ca05126" alt="Add Task" width="300" style="border: 1px solid #ccc; padding: 5px;"/> |

| Edit Task                          |
|------------------------------------|
| <img src="https://github.com/user-attachments/assets/88e99210-b8d6-4033-82ff-8b983776993c" alt="Edit Task" width="300" style="border: 1px solid #ccc; padding: 5px;"/> |

</div>



## 📱 App Features

- **Add Tasks by Date**: Users can select a specific date and add tasks for that day.
- **Edit Tasks**: Modify existing tasks with ease.
- **Delete Tasks**: Remove tasks you no longer need.
- **User-Friendly Interface**: Designed for simplicity and ease of use.


## ⚙️ Technologies and Architecture

This app is built using the following modern Android development technologies:

### **Architecture**
- **MVVM (Model-View-ViewModel)**: Ensures separation of concerns and makes the app lifecycle-aware.
- **Repository Pattern**: Provides a clean API for data access by abstracting data sources.

### **Libraries & Frameworks**
- **Room Database**: Manages local data storage efficiently with SQLite.
- **Navigation Component**: Handles in-app navigation with ease, supporting arguments between destinations.
- **LiveData & ViewModel**: For reactive and lifecycle-aware data handling.




