
# React Native Task Manager App ⚛ ✅

A simple task manager application built using React Native. This app allows users to create, view, and delete tasks in an intuitive interface.

## Features

- Add tasks using a text input field.
- Display a list of tasks with a clean UI.
- Delete tasks by tapping on them.
- Responsive design optimized for iOS and Android.

## Demo

### Screenshots
- **Main Screen**: Displays a list of tasks.
<img src="/todoList/assets/tasks.PNG" alt="Main Screen" width="175" />

- **Task Input**: Add tasks using the input field and "+" button.
<img src="/todoList/assets/taskinput.PNG" alt="Task Input" width="175" />

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/kevinlwong/react-native-task-manager.git
   cd react-native-task-manager
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   npm start
   ```

4. Run the app:
   - For iOS:
     ```
     npm run ios
     ```
   - For Android:
     ```
     npm run android
     ```

## Code Structure

- **`App.js`**: The main component that handles task state, adding and removing tasks, and rendering the UI.
- **`components/Task.js`**: A reusable component for displaying individual tasks.

## How to Use

1. Write a task in the input field at the bottom of the screen.
2. Press the "+" button to add the task to the list.
3. Tap on a task in the list to mark it as complete and remove it.

## Dependencies

- `react-native`
- `react`
- `react-native-keyboard-aware-scroll-view` (for smooth keyboard management)

## Styling

All styles are defined in the `StyleSheet` object in `App.js` for consistent UI:

- **Container**: Background color and padding.
- **Tasks Wrapper**: Styling for the task list and title.
- **Input Field**: Rounded edges and padding for user input.
- **Add Button**: Circular button with "+" sign for adding tasks.

## Future Improvements

- Add persistent storage for tasks (e.g., AsyncStorage or a backend).
- Allow task editing.
- Add animations for task removal.
- Implement categories or priorities for tasks.

## Contact

For any questions or feedback, please reach out to `kevinwong973@gmail.com` or `kevinlwong@cpp.edu`.
