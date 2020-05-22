# #30DaysOfKotlin
## GoogleDeveloperTraining-AndroidKotlinFundamentalApps
Build fundamental apps with kotlin for android, part of #30DaysOfKotlin created by google developer
training program.

### Lesson 1: Build your first app
Lesson 1 teaches you how to set up Android Studio to use Kotlin and how to build apps. You start
with "Hello World" and move up to an app that uses image files and a click handler. You learn how
Android projects are structured, how to use and modify views in your Kotlin Android app, and how to
 make sure your apps are backward-compatible. You also learn about API levels and the Android
 Jetpack libraries.

### Lesson 2: Layouts
In Lesson 2, you learn how to use the Android Studio Layout Editor to create linear layouts and
constraint layouts. You create apps that get and display user input, respond to user taps, and
change the visibility and color of views. This lesson also teaches you how to use data binding to
eliminate inefficient calls to the findViewById() method.

#### 2.1 Linear layout using the Layout Editor
#### 2.2 Add user interactivity
#### 2.3 Constraint layout using the Layout Editor
#### 2.4 Data-binding basics

### Lesson 3: Navigation
In Lesson 3, you learn how to create useful navigation in an app. You create a fragment and add it
to an app, then add navigation to the app using the Android Studio navigation graph. You add a
navigation drawer and an options menu to your app, and you work with the app's back stack, changing
 the destination of the system Back button. Finally, you learn how to invoke an external activity
 from within the app.

#### 3.1 Create a fragment
#### 3.2 Define navigation paths
#### 3.3 Define external activities

### Lesson 4: Activity and fragment lifecycles
In Lesson 4, you learn about the activity and fragment lifecycles, and you learn how to manage
complex lifecycle situations. You work with a starter app that contains several bugs related to the
Android lifecycle. You add logging to the app to better understand the app's lifecycle events, and
you fix the bugs that the app contains and add some enhancements to the app. You also learn about
Android Jetpack's lifecycle library, which can help you manage lifecycle events with code that's
better organized and easier to maintain.

#### 4.1 Lifecycles and logging
#### 4.2 Complex lifecycle situations

### Lesson 5: Architecture components
Lesson 5 teaches you how to use ViewModel and LiveData objects. You learn how to use ViewModel
objects to enable data to survive configuration changes such as screen rotations. You convert an
app's UI data into encapsulated LiveData and add observer methods that are notified when the value
of the LiveData changes.

You also integrate LiveData and ViewModel with data binding so that the views in your layout
communicate directly with ViewModel objects, without using the app's fragments to relay information.
This technique simplifies your code and eliminates the need for click handlers in the UI controllers.

#### 5.1 : ViewModel and ViewModelFactory
#### 5.2 : LiveData and LiveData observers
#### 5.3 : Data binding with ViewModel and LiveData
#### 5.4 : LiveData transformations

### Lesson 6: Room database and coroutines
Lesson 6 teaches you how to use the Room database library. Room takes care of many of the chores of
setting up and configuring a database, and simplifies the code for interacting with the database.
You learn how to use Kotlin coroutines to move database operations away from the main thread, and
you learn more about using ViewModel and LiveData with app navigation.

#### 6.1: Create a Room database
#### 6.2: Coroutines and Room
#### 6.3: Use LiveData to control button states

### Lesson 7: RecyclerView
Lesson 7 teaches you how to use a RecyclerView to efficiently display lists and grids of items. For
complex lists and grids, you learn ways to make RecyclerView more efficient and your code easier to
maintain and extend. You learn how to make items in a RecyclerView clickable. You also learn how to
add more than one view holder and layout to lists and grids in a RecyclerView, for example, to add
a header in your app.

#### 7.1: RecyclerView fundamentals
#### 7.2 DiffUtil and data binding with RecyclerView
#### 7.3 GridLayout with RecyclerView
#### 7.4 Interacting with RecyclerView items
#### 7.5: Headers in RecyclerView