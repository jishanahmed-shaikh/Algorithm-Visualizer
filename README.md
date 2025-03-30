# Data Structure Visualizer

This project provides a web-based tool for visualizing fundamental data structures and sorting algorithms. Users can create, manipulate, and sort arrays, linked lists, stacks, and queues through an interactive interface.

## Features

### Sorting Algorithms
Users can generate an array and visualize step-by-step sorting using one of the following sorting algorithms:
* Bubble Sort
* Insertion Sort
* Selection Sort
* Merge Sort

The sorting process is animated, displaying comparisons and swaps at each step.

### Data Structures
This project also implements and visualizes:
* **Linked Lists**: Insert and delete elements from the beginning or end.
* **Stacks**: Push and pop elements, maintaining Last-In-First-Out (LIFO) order.
* **Queues**: Enqueue and dequeue elements, maintaining First-In-First-Out (FIFO) order.

## How It Works
1. Users can generate a custom array by specifying size, minimum, and maximum values, or they can randomize it.
2. The sorting algorithm can then be applied, showing step-by-step transformations.
3. Linked lists, stacks, and queues can be manipulated through API endpoints.

## Installation & Usage

### Prerequisites
Ensure you have Python installed along with Flask:
```sh
pip install flask numpy
```

### Running the Application
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo/Data-Structure-Visualizer.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Data-Structure-Visualizer
   ```
3. Run the Flask server:
   ```sh
   python app.py
   ```
4. Open a web browser and go to:
   ```
   http://127.0.0.1:5000
   ```

## API Endpoints
The application provides API routes for interacting with the data structures:

### Sorting
- **POST /generateDS** - Generates a random array.
- **POST /sort** - Sorts an array using a specified algorithm.

### Linked List
- **POST /linkedlist/insert_beginning** - Inserts an element at the beginning.
- **POST /linkedlist/insert_end** - Inserts an element at the end.
- **POST /linkedlist/delete_beginning** - Deletes an element from the beginning.
- **POST /linkedlist/delete_end** - Deletes an element from the end.

### Stack
- **POST /stack/push** - Pushes an element onto the stack.
- **POST /stack/pop** - Pops an element from the stack.

### Queue
- **POST /queue/enqueue** - Adds an element to the queue.
- **POST /queue/dequeue** - Removes an element from the queue.

## Technologies Used
This project is built using:
* **Python (Flask)** - Backend framework
* **NumPy** - Array operations
* **JavaScript, HTML, CSS** - Frontend (for visualization)

## Future Enhancements
- Implement additional sorting algorithms (Quick Sort, Heap Sort, etc.)
- Improve visualization with animations and UI enhancements
- Add more data structures such as Binary Trees and Graphs

## Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests with improvements or additional features.

## License
This project is open-source and available under the [MIT License](LICENSE).

---

**Demo Screenshots:**

#### Sorting Animation
![ezgif-33acc2102d88d3](https://github.com/user-attachments/assets/05424c38-88dd-4876-b8e9-97381b997aae)


#### Stack Operations
![ezgif-30b603d00a850f](https://github.com/user-attachments/assets/5141cb43-cda8-4868-95ca-adf611f97977)


#### Queue Operations
![ezgif-3e6893721aeb7d](https://github.com/user-attachments/assets/edfcc38d-fbfb-4671-8156-15f9d2d40143)


---
Start visualizing data structures and sorting algorithms today!

