# Heuristics - PTL System Balancing

## Installation and Setup

Follow these steps to set up and run the project:

### 1. Clone the Repository
```sh
git clone https://github.com/Davidgp04/Heuristics.git
cd Heuristics
```

### 2. Move to the `src` Folder
```sh
cd src
```

### 3. Install Dependencies
Ensure you have Python installed, then run:
```sh
pip install -r requirements.txt
```

## Running the Code

### Deterministic Constructive Method
To run the constructive heuristic method, use:
```sh
py main.py nombre_archivo.xlsx nombre_salida.xlsx [opcional]
```

### Randomized Variant
To run the randomized variant, use:
```sh
py randomized.py nombre_archivo.xlsx nombre_salida.xlsx [opcional]
```

### Parameters:
- `nombre_archivo.xlsx` → Input Excel file containing order data.
- `nombre_salida.xlsx` → Output Excel file where results will be saved.
- `[opcional]` → Any additional optional parameters (if applicable).

## Notes
- Ensure that the input file follows the required format.
- The output file will contain the processed order assignments.
- If you encounter any issues, check that all dependencies are installed correctly.
�
