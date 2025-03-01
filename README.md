# Telegram Clone for BeyondChats

## Overview

This project aims to create a pixel-perfect replica of the Telegram messaging application for both desktop and mobile views, using ReactJS. The design and functionality closely follow the actual Telegram UI/UX as possible.

## Live Link

- [Telegram Clone](https://telegram-clone-sooty.vercel.app/)

## Features

- **Responsive Design:** The UI is designed to be responsive and works seamlessly on both desktop and mobile devices.
- **Chats List:** Fetches and displays a list of chats using the provided API endpoint.
- **Messages:** Displays messages for each chat by fetching data from the provided API endpoint.

## Technologies & Packages Used

- ReactJS
- Vite (for development and build)
- Axios (for API requests)
- React Router (for navigation)
- Tailwind CSS (for styling)
- React Icons etc.,

## Run the Project Locally

1. **Clone the Repository**:

    ```sh
    git clone https://github.com/nazmul-nhb/telegram-ui-ux-nazmul.git
    cd telegram-ui-ux-nazmul
    ```

2. **Install Dependencies**:

    ```sh
    npm install
    ```

3. **Run the Application**:

    ```sh
    npm run dev -- --host
    ```

4. **Access the Site**: Open your browser and go to `http://localhost:5173/`, or `http://192.168.1.12:5173/` from other devices on the same network to view the application.

## Challenges and Considerations

- **Time Constraints:** Given the 48-hour limit, some advanced features may not be fully implemented.
- **UI/UX:** Efforts have been made to match the Telegram UI/UX as closely as possible within the given time frame. Some animations are missing due to time constraints.
- **API Integration:** Handled API integration to ensure data is fetched and displayed correctly.
