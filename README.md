# Binary Search Visualizer

This is a web application designed to visually demonstrate the **binary search algorithm**. Users can interactively add numbers to a sorted array and then search for a specific value. The application animates the search process, providing a clear, step-by-step visualization of how the algorithm works.

---

## Features

* **Interactive Array**: Dynamically add numbers to a list which is automatically kept sorted.
* **Animated Search**: Watch the binary search algorithm in action as it narrows down the search space.
* **Visual Feedback**:

  * Elements outside the current search range are visually faded out.
  * The found element is highlighted in green with a pulse animation.
  * If the element is not found, all elements turn red to indicate a failed search.
* **User-Friendly Interface**: A clean, modern design built with Tailwind CSS for an intuitive user experience.

---

## Technologies Used

* **React.js**: For building the interactive user interface.
* **Vite**: A fast build tool and development server for modern web projects.
* **Tailwind CSS**: A utility-first CSS framework for rapid and responsive styling.
* **JavaScript**: The core logic for handling state and running the search algorithm.

---

## Installation

To get a local copy up and running, follow these simple steps:

### 1. Clone the repository:

```bash
git clone [repository-url]
```

### 2. Navigate to the project directory:

```bash
cd [project-folder-name]
```

### 3. Install dependencies:

```bash
npm install
```

### 4. Start the development server:

```bash
npm run dev
```

The application will be accessible in your browser at [http://localhost:5173](http://localhost:5173).

---

## Usage

1. **Add Numbers**: Use the "Enter number" input field to add integers to the array. Click the **Add** button, and the number will be added and the array will be sorted automatically.
2. **Search**: Enter a number into the "Search number" input field and click the **Search** button. The visualization will begin.
3. **Observe**: Watch the array elements change color to see which parts of the array are being checked.

---

