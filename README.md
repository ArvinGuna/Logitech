# Tab Component Readme
 
This project implements a tab component in HTML, CSS, and JavaScript. It allows users to navigate between tabs, view content associated with each tab, delete tabs, and reset the component to its initial state.

## Features

- Tab navigation with next and previous buttons.
- Dynamically populated tab content.
- Ability to delete tabs.
- Reset functionality to restore the initial state.

## How to Use
### 1. Checkout main branch
  - If you're using Git, navigate to your project directory in the terminal or command prompt.
  - Use the following command to switch to the main branch:
  ```
  git checkout main
  ```

### 2. Run HTML file
  - After checking out the main branch, navigate to the directory where the **TABCOMPONENT.html** file is located.
  - Open the HTML file in a web browser of your choice. You can do this by double-clicking the file or right-clicking and selecting "Open with" and choosing a web browser.
  - Make sure to enable javascript in your browser
       
## Functionality

### 1. Overview:
  - Users can navigate between tabs using the previous and next buttons.
  - Tabs can be deleted individually using the delete button associated with each tab.
  - The reset button restores the tab component to its initial state, including the original content and tab order.

### 2. HTML Structure:
  - The tab component is structured with HTML elements.
  - The navigation wrapper (nav-wrapper) contains previous (prevBtn) and next (nextBtn) buttons.
  - The tab navigation (tab-nav) dynamically populates tab buttons.
  - The tab content container (container) dynamically populates tab content.

### 3. CSS Styling:
  - CSS styles define the appearance of the tab component, including button styles, tab content layout, and responsive design for small screens.

### 4. JavaScript Functionality:
  - JavaScript handles the dynamic creation of tab elements, tab navigation, content population, tab deletion, and resetting functionality.
  - Event listeners are attached to buttons for navigation, tab deletion, and resetting.

### 5. Initial Content:
  - The initial content of the tab component is defined in the allItems array.
  - This content is used to populate the tab component on page load and reset.
    
## Compatibility
  - The tab component is compatible with modern web browsers.
  - It includes responsive design for optimal viewing on small screens.

## Further Customization
  - Developers can customize the tab component by modifying the HTML structure, CSS styles, and JavaScript functionality to suit specific requirements.

## License
  - This project is available under the [MIT License](https://mit-license.org/). Feel free to use, modify, and distribute according to the terms of the license.

