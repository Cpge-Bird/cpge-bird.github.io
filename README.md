# CPGE Bird Website Documentation

This project is a webpage for **CPGE Bird**, a club for technology and robotics enthusiasts. The page is designed with a modern look and responsive design, featuring a **popup notification** with a **confetti circle effect** to celebrate the club's opening.

## Features Overview

| **Feature**                | **Description**                                                                                                      |
|----------------------------|----------------------------------------------------------------------------------------------------------------------|
| **Navigation Bar**          | Contains links to different sections of the website like Home, Projects, About Us, and Contact. Includes a search bar.|
| **Main Content**            | Displays a header and description of the club alongside an image, with animations for smooth appearance.             |
| **Footer**                  | Shows the copyright information and a link to the website designer's page.                                            |
| **Popup Notification**      | A popup that appears when the page loads, notifying the user of the club's opening with a countdown timer.            |
| **Confetti Circle**         | A confetti animation within a circular container, celebrating the event. Stops when the popup is closed.              |
| **Responsive Design**       | The layout adjusts for different screen sizes, ensuring the page is accessible on desktops, tablets, and smartphones. |

## Detailed Components

### 1. **Navigation Bar**

| **Property**           | **Description**                                                                                   |
|------------------------|---------------------------------------------------------------------------------------------------|
| **Logo**               | The club's logo (an image). Positioned on the left side of the navigation bar.                     |
| **Menu Links**         | Links to Home, Projects, About Us, and Contact pages. On hover, the links change background color. |
| **Search Bar**         | A text input field where users can search for specific terms. The search dynamically filters content. |

### 2. **Main Content Section**

| **Property**           | **Description**                                                                                   |
|------------------------|---------------------------------------------------------------------------------------------------|
| **Title**              | "Beurd Byte Builders" - The name of the club, styled with a large font and shadow effect.          |
| **Description**        | A paragraph explaining the club's focus on technology and robotics.                                |
| **Image**              | An image of an Arduino board displayed on the right side. The image animates with a floating effect.|

### 3. **Footer**

| **Property**           | **Description**                                                                                   |
|------------------------|---------------------------------------------------------------------------------------------------|
| **Text**               | Copyright information for the club, followed by a link to the designer's website.                  |
| **Background**         | A solid blue background with a shadow effect.                                                      |

### 4. **Popup Notification with Countdown**

| **Property**           | **Description**                                                                                   |
|------------------------|---------------------------------------------------------------------------------------------------|
| **Popup Message**      | A notification that appears 1 second after the page loads, informing the user about the club opening.|
| **Countdown Timer**    | Displays the number of days until the official website launch. Updated dynamically every second.    |
| **Close Button**       | Allows the user to close the popup. The confetti animation stops when the popup is closed.          |

### 5. **Confetti Circle Effect**

| **Property**           | **Description**                                                                                   |
|------------------------|---------------------------------------------------------------------------------------------------|
| **Confetti Canvas**     | A circular canvas that contains confetti animations. Particles fall from random positions inside the circle. |
| **Confetti Behavior**   | The confetti moves downwards and resets at the top when it reaches the bottom of the circle.       |
| **Confetti Colors**     | Particles are randomly assigned vibrant colors.                                                   |
| **Stop Confetti**       | When the popup is closed, the confetti animation stops.                                           |

## Responsive Design

| **Screen Size**         | **Behavior**                                                                                      |
|------------------------|---------------------------------------------------------------------------------------------------|
| **Desktop**             | Full navigation bar with menu items, larger images, and content laid out in two columns.           |
| **Tablet**              | The navigation bar shrinks, and the search bar becomes smaller. Main content resizes to fit.       |
| **Mobile**              | The layout becomes vertical, with content centered. Navigation links are hidden for a cleaner view.|

## Code Structure

### 1. **HTML**
The HTML provides the structure for the webpage, including the navigation bar, content sections, popup notification, and confetti animation.

### 2. **CSS**
The CSS styles the layout, animations, and responsive behavior. Key animations include:
- **Fade-In Animation**: Applied to the main content and popup for smooth appearance.
- **Popup Slide-In Animation**: The popup enters with a scale transformation.
- **Confetti Animation**: The confetti particles move within a circular boundary.

### 3. **JavaScript**
JavaScript is used to handle dynamic behaviors, such as:
- **Popup Display**: The popup appears 1 second after page load.
- **Close Popup**: The popup closes when the user clicks the close button, and the confetti stops.
- **Countdown Timer**: The number of days remaining until the website launch is dynamically updated.

## Usage Instructions

1. **View the Page**: Load the HTML file in a browser to see the page layout and features.
2. **Interact with the Popup**: The popup will appear after 1 second, displaying the countdown to the website launch. Close it by clicking the 'X' button.
3. **Responsive Design**: Resize the browser window or view the page on different devices to see how the layout adapts.

---

This documentation provides an overview of the structure and features of the cpge bird webpage, detailing the layout, design elements, and dynamic effects like the confetti circle.
