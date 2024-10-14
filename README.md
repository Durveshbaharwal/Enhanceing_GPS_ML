# Enhancing GPS Positioning Accuracy Using Machine Learning

## Overview

This project implements a **Least Squares Solution** approach using data derived from **Global Navigation Satellite Systems (GNSS)**. The goal is to enhance positioning accuracy by minimizing the error in the estimated location. The script processes raw GNSS data, applies a least squares estimation method, and outputs the improved position estimates.

## Features

- **Data Processing**: Cleans and preprocesses GNSS data.
- **Least Squares Estimation**: Implements the least squares method to refine position calculations.
- **Result Analysis**: Outputs position estimates and calculates residuals for error analysis.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Durveshbaharwal/Enhanceing_GPS_ML.git
    cd Enhanceing_GPS_ML
    ```
2. **Dependencies**: Ensure you have the required dependencies installed. You can install them using:
    ```bash
    pip install -r requirements.txt
    ```

3. **Running the script**: Execute the Python script:
    ```bash
    python least_squares_solution_from_gnss_derived_data_copy1.py
    ```

## Usage

- The script reads GNSS data from a source file.
- Applies the least squares method to estimate positions.
- Outputs the refined positions along with error metrics.

### Example

Here’s an example of how to use the script:
```python
import least_squares_solution_from_gnss_derived_data_copy1 as lss

# Load your GNSS data
data = lss.load_data('path_to_your_data_file')

# Run the least squares solution
results = lss.least_squares_estimation(data)

# Output the results
lss.print_results(results)
```

## Contributing
Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Open a Pull Request.

## Contact
For any questions, feel free to reach out via LinkedIn or open an issue on the repository.

