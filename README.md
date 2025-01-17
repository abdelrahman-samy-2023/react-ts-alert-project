# React Alert Project

## Project Description

This project is a React application that utilizes TypeScript to create a flexible and reusable Alert component. This component allows you to display various messages to users, such as alerts, information, success messages, warnings, and errors. Icons from the `lucide-react` library are used to enhance the appearance of the alerts, making them more visually appealing.

## Components

### 1. `App.tsx`
- Contains the main `App` component that renders a set of different alerts using the `Alert` component.
- Passes the alert type, icon, title, and description (if available) to the `Alert` component.

### 2. `Alert.tsx`
- The `Alert` component that receives props such as type, icon, title, description, and children.
- Displays the alert based on the specified type, with the option to close the alert using a close icon.

### 3. `index.scss`
- Contains custom styles for each type of alert.
- Uses SCSS variables to define colors and backgrounds for each alert type.

### 4. `index.ts`
- Contains the definition of the `AlertTypes` type, which specifies the different available alert types.

## How to Use

1. Make sure to install all dependencies by running:
   ```bash
   npm install
   ```

2. Start the application using:
   ```bash
   npm start
   ```

3. You can modify the `App.tsx` component to add or change alerts as needed.

## Demo

https://abdelrahman-samy-2023.github.io/react-ts-alert-project/

## Contributing

If you would like to contribute to this project, please open a pull request with your changes.

## License

This project is licensed under Abdelrahman Samy - see the LICENSE file for details.
