# Sortify
Sorting Visualizer
A sorting algorithm visualizer implemented in C++ with SDL2 Library. This project visually demonstrates the process of various sorting algorithms, providing an educational tool for understanding their working principles.

Table of Contents
Introduction
Features
Installation
Usage
Sorting Algorithms
Visualization
Contributing
License
Acknowledgements
Introduction
Sorting algorithms are fundamental in computer science, used to arrange elements in a list in a specified order. This visualizer helps in understanding the mechanics of different sorting algorithms by providing a graphical representation of their process. The algorithms implemented are:

Selection Sort
Insertion Sort
Bubble Sort
Merge Sort
Quick Sort
Heap Sort
Features
Fixed List Size: The list size is set to 130 elements.
Randomize List: Generate a random list of 130 elements.
Algorithm Selection: Choose any of the implemented sorting algorithms to visualize.
Visual Delay: Faster algorithms are delayed to make their steps comprehensible.
Installation
Prerequisites
C++ Compiler: Ensure you have a C++ compiler installed (e.g., g++).
SDL2 Library: Install SDL2 and SDL2_ttf. On Linux, you can use:
bash
Copy code
sudo apt-get install libsdl2-dev libsdl2-ttf-dev
On Windows, download the development libraries from the SDL2 website.
Clone Repository
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/sorting-visualizer.git
cd sorting-visualizer
Build
Compile the project using your C++ compiler:

bash
Copy code
g++ -o sorting_visualizer main.cpp -lSDL2 -lSDL2_ttf
Usage
Run the executable:

bash
Copy code
./sorting_visualizer
Use the interface to randomize the list and select a sorting algorithm to visualize.

Sorting Algorithms
Selection Sort
Repeatedly selects the smallest element from the unsorted portion and swaps it with the first unsorted element.

Insertion Sort
Builds the sorted list one element at a time by repeatedly taking the next unsorted element and inserting it into its correct position.

Bubble Sort
Repeatedly steps through the list, compares adjacent elements and swaps them if they are in the wrong order.

Merge Sort
Divides the list into two halves, sorts each half recursively, and then merges the sorted halves.

Quick Sort
Selects a 'pivot' element, partitions the array around the pivot, and recursively sorts the partitions.

Heap Sort
Transforms the list into a max heap and then repeatedly extracts the maximum element to build the sorted list.

Visualization
Each sorting algorithm's process is visualized with bars representing elements. The height of a bar indicates the value of the element. The visualization provides a step-by-step view of the sorting process, with delays added to faster algorithms for better comprehension.

Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
SDL2 for providing the graphical framework.
Various online resources and tutorials for their guidance on implementing sorting algorithms and visualizations.
