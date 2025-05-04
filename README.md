# react-native-todolist

# TaskList App (React Native)

A simple React Native application for managing your todo tasks.

## Key Features

* **View Tasks:** Displays a scrollable list of your todo items.
* **Add Tasks:** Easily add new tasks to your list.
* **Update Task Status:** Mark tasks as complete or incomplete.
* **Filter Tasks:** View all, completed, or pending tasks.
* **Delete Tasks:** Remove tasks from your list.
* **Persistent Data:** Tasks are saved locally using AsyncStorage.

## Technologies Used

* React Native

## Project Structure

The project includes:

* `components/`: Reusable UI components like the `Card` component.
* `screens/`: Application screens including the main task list view.

## Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [repository URL]
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd [project directory name]
    ```
3.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```
4.  **Start the application:**
    ```bash
    npx react-native run-android # For Android
    # or
    npx react-native run-ios   # For iOS
    ```

## Core Concepts Demonstrated

* **Layout:** Structuring the user interface.
* **Components:** Creating reusable UI elements (e.g., `Card`).
* **Mapping Lists:** Using the ES6 `map` function to render lists of components.
* **Scrollable Lists:** Displaying a large number of items efficiently.
* **Spread Operator:** Utilizing the spread operator for concise data manipulation.
* **Updating State:** Modifying the status of individual tasks.
* **Bottom Tab Navigation:** Implementing a simple tab menu for navigation.
* **Filtering Data:** Using the ES6 `filter` method to display specific tasks.
* **Deleting Items:** Removing tasks from the list.
* **Adding Items:** Creating new tasks.
* **Error Handling:** Implementing `try...catch...finally` blocks for error management.
* **Local Data Persistence:** Using `AsyncStorage` to save and retrieve task data.
* **`useRef` Hook:** Accessing and manipulating DOM elements (in this case, for scrolling).

## Further Development

Potential future enhancements include:

* More detailed task information (due dates, descriptions).
* Task prioritization.
* Searching and sorting functionality.
* Improved UI/UX.
