# Sorting Algorithm Visualization with Pygame

This project is a visual representation of sorting algorithms using the Pygame library in Python. The program displays the step-by-step sorting process of a randomly generated list.

## Features

- **Bubble Sort and Insertion Sort:** Two sorting algorithms are implemented for visualization.
- **Real-time Visualization:** The sorting process is visually represented in real-time.
- **User Interaction:** Users can reset the list, choose the sorting direction (ascending/descending), and switch between Bubble Sort and Insertion Sort.

## Getting Started

1. **Prerequisites:**
   - Ensure you have Python installed.
   - Install the required library by running `pip install pygame` in your terminal.

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/sorting-visualization.git
   cd sorting-visualization
   ```

3. **Run the Program:**
   ```bash
   python sorting_visualization.py
   ```

4. **Controls:**
   - `R`: Reset the list.
   - `SPACE`: Start sorting.
   - `A`: Set sorting direction to ascending.
   - `D`: Set sorting direction to descending.
   - `I`: Switch to Insertion Sort.
   - `B`: Switch to Bubble Sort.
   - `ESC` or close the window to exit.

## Customization

- Adjust the parameters in the code to customize the number of elements in the list and the range of values.

```python
n = 50           # Number of elements in the list
min_val = 0      # Minimum value for list elements
max_val = 100    # Maximum value for list elements
```

## Acknowledgments

- The Pygame library: [Pygame](https://www.pygame.org/)
- Inspired by the work of others in creating sorting visualizations.

Feel free to contribute, report issues, or suggest improvements!
