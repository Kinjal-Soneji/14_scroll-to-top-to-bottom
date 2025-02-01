# Scroll to Top and Bottom

A simple web application that demonstrates smooth scrolling functionality with a dynamic user list. The application fetches user data from an external API and provides convenient buttons to scroll to the top or bottom of the page.

## Features

- Fetches user data from DummyJSON API
- Displays a list of 100 users with their first and last names
- Smooth scroll-to-top functionality
- Smooth scroll-to-bottom functionality
- Loading state indication while fetching data
- Responsive design

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Fetch API
- DummyJSON API

## Project Structure

```
├── index.html
├── style.css
└── main.js
```

## Implementation Details

### HTML
- Basic structure with buttons for scrolling
- Container for user list
- Loading indicator

### CSS
- Handles visibility of loader and user list
- Manages display states through classes

### JavaScript
- Fetches user data from DummyJSON API
- Implements smooth scrolling behavior
- Manages loading states
- Renders user list dynamically

## API Integration

The application uses the DummyJSON API endpoint:
```
https://dummyjson.com/users?limit=100
```

## Usage

1. Clone the repository
2. Open `index.html` in a web browser
3. The application will automatically fetch and display the user list
4. Use the "Scroll To Bottom" button to smoothly scroll to the bottom of the page
5. Use the "Scroll to Top" button to smoothly scroll back to the top

## Functions

### `showLoader()`
- Shows loading indicator
- Hides user list

### `removeLoader()`
- Hides loading indicator
- Shows user list

### `fetchUsersList()`
- Asynchronously fetches user data
- Manages loading states
- Triggers display of users

### `displayUsersList(getUsers)`
- Renders the user list in the DOM
- Formats user data into list items

## Browser Compatibility

This application uses modern JavaScript features and the Fetch API. It is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

