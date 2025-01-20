# AutoDiff-Ocaml

# OCaml Automatic Differentiation Library with Web Interface

## Recent Updates

### 1. Added Web Interface
- Implemented a web-based interface using Dream for visualizing and running examples
- Added interactive visualization of computational graphs for each example
- Included real-time output display
- Added loading indicators for long-running examples

### 2. Neural Network Improvements
- Fixed and enhanced the neural network implementation
- Added proper initialization and gradient handling
- Improved training metrics and visualization
- Achieved 99% accuracy on binary classification task
- Added detailed training progress visualization

### 3. Computational Graphs
Added visualizations for different examples:
- Basic operations graph
- Simple derivative computations
- Large matrix operations
- Neural network architecture and training
- Computation graph visualization

### 4. Front-end Features
- Real-time graph generation using Graphviz
- Interactive example selection
- Progress indicators for long-running computations
- Clean and responsive UI design
- Detailed output formatting

### 5. Code Organization
- Separated frontend and backend code
- Added proper error handling
- Improved code documentation
- Removed unused dependencies (oplot)

## Running the Project

1. Build the project:
```bash
dune build
```

2. Start the web server:
```bash
dune exec frontend/server.exe
```

3. Access the web interface:
```
http://localhost:8080
```

## Example Descriptions

1. **Basic Operations**
   - Demonstrates basic tensor operations
   - Shows computational graph for operations

2. **Simple Derivatives**
   - Shows automatic differentiation for simple functions
   - Includes visualization of computation path

3. **Large Matrix Operations**
   - Demonstrates handling of large matrices
   - Includes performance metrics

4. **Neural Network**
   - Binary classification example
   - Shows training progress and metrics
   - Includes architecture visualization
   - Achieves 99% accuracy

5. **Computation Graph**
   - Visualizes the internal computation graph
   - Shows gradient flow and operations

## Dependencies
- core
- dream (web server)
- graphviz (for visualization)
- bigarray
- unix

## Note
The project now includes a comprehensive web interface for visualizing and understanding automatic differentiation concepts. Each example includes both computational output and visual representation of the operations being performed.
