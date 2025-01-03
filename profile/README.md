# Documentation: Doc Management Panel

## Overview

The **Doc Management Panel** is a user-friendly interface designed to manage documents efficiently. It features a modern HTML table with 3D styling, intuitive action buttons, and a popup for creating new task entries. Notifications are displayed as toast popups with sound effects to enhance user interaction.

---

## Features

### 1. **Modern HTML Table with 3D Design**

The interface includes a modern table with advanced 3D styling and responsive design. 

- **Table Headers:**
  - **DocID**: Unique identifier for each document.
  - **Task Title**: Title of the task associated with the document.
  - **Task Description**: Detailed description of the task.
  - **Task For**: Assigned person or group for the task.
  - **CreatedOn**: Timestamp indicating when the task was created.
  - **UpdatedOn**: Timestamp indicating the last update of the task.
  - **Task Status**: Current status of the task.

- **Task Status Styling:**
  - **Completed**: Displayed in **green**.
  - **Pending**: Displayed in **orange**.
  - **Rejected**: Displayed in **red**.

- **Action Buttons:**
  - **Delete**: Removes the task from the table.
  - **View Details**: Opens a modal popup displaying the detailed information about the task.

---

### 2. **Add New Task Button**

- **Location:**
  - Positioned at the **bottom-right corner** of the page for easy access.

- **Design:**
  - A circular button with a `+` icon.
  - **Background**: Styled with a rare and visually appealing color theme.

- **Functionality:**
  - Clicking the button opens a **centered popup form**.
  - The popup disables background controls, ensuring user focus.

---

### 3. **Popup Form for Task Entry**

The popup form allows users to input new task details.

- **Fields:**
  - **Task Title**: A text input for the task's title.
  - **Task Description**: A textarea for entering detailed descriptions.
  - **Task For**: A dropdown menu to select the responsible person or group.
  - **Task Status**: A dropdown with options (`Completed`, `Pending`, `Rejected`).

- **Behavior:**
  - On form submission, the task is added to the table.
  - The background remains disabled until the popup is closed.

---

### 4. **Search and Filter Functionality**

Enhanced usability with real-time search and filter capabilities.

- **Features:**
  - Search tasks by **title**, **description**, or **status**.
  - Filter tasks by their **status** (e.g., Completed, Pending, Rejected).
  - Real-time updates to the table based on user input.

---

### 5. **Notifications with Toast Popups**

- **Purpose:**
  - Provide feedback for actions such as adding, deleting, or updating tasks.

- **Features:**
  - Displays non-intrusive notifications at the **top-right corner**.
  - Includes **sound effects** for better user engagement.
  - Automatically disappears after a set duration.

---

## User Interface Design

### **HTML Table**

- **3D Styling:**
  - Incorporates shadows and hover effects.
  - Ensures responsive design for optimal viewing on different devices.

- **Action Buttons:**
  - Styled with modern UI principles.
  - Includes hover animations for better user feedback.

---

### **Add Task Popup**

- **Centered on Screen:**
  - Designed as a modal with an overlay.

- **Form Styling:**
  - Features modern aesthetics with proper alignment and spacing.
  - Includes input validation for required fields.

- **Background Color:**
  - Fixed to **white** for both the page and the popup.

---

### **Button Styling**

- **Colors:**
  - Background: **Black**.

- **After-Click Effect:**
  - Includes CSS styling for a professional and modern look.

---

### **Notifications**

- **Toast Popups:**
  - Non-intrusive notifications appearing at the **top-right corner**.
  - Includes subtle **sound effects** for better engagement.

---

## How to Use

1. **View Tasks:**
   - The tasks are displayed in a table with options to delete or view details.

2. **Add a New Task:**
   - Click the circular `+` button at the bottom-right corner to open the popup form.
   - Fill in the required details and submit.

3. **Search and Filter Tasks:**
   - Use the search bar or filters to find tasks quickly.

4. **Receive Notifications:**
   - Observe toast popups for feedback after actions.

---

## Fonts and Colors

- **Font:**
  - A fixed modern, professional font is used throughout the application.

- **Colors:**
  - Background for the page and popup: **White**.
  - Buttons: **Black** with a CSS after-click effect.
  - Task status colors:
    - Green for Completed.
    - Orange for Pending.
    - Red for Rejected.

---

