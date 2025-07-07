# TOTO Number Analysis 🎯

A data analysis project exploring number frequency, patterns, and trends in Singapore TOTO lottery draws using Python. This project aims to gain insights from historical TOTO results through statistical techniques and data visualization.

---

## 📊 Project Overview

The goal of this project is to explore whether 
- Analyze the frequency of winning numbers.
- Visualize trends over time.
- Identify number distribution and repetition patterns.
- Explore and evaluate basic prediction strategies.

---

## 🧰 Tech Stack

- **Language**:
    - Python 3

- **Libraries**:
    - Pandas (For data manipulation and cleaning)
    - Matplotlib / Seaborn (For visualizing frequency and trends)
    - SciPy (For statistical calculations)

---

## 📁 Project Structure
```
toto-number-analysis/
├── toto_results.csv    # Historical TOTO draw data (input)
├── toto_analysis.py    # Main script with menu and analysis functions
├── README.md           # Project documentation
└── requirements.txt    # Python package dependencies
```

---

## ▶️ How to Use

1. **Clone the repository**:
    ```bash
    git clone https://github.com/cyuanjun/toto-number-analysis.git
    ```

2. **Change directory**:
    ```bash
    cd toto-number-analysis
    ```

3. **Create/Activate virtual environment (Optional)**:
    
    - #### Windows:
        - Creating virtual environment
        ```bash
        python -m venv toto_number_analysis_venv
        ```

        - Activating virtual environment
        ```
        toto_number_analysis\Scripts\activate
        ```
    - #### Mac:
        - Creating virtual environment
        ```bash
        python3 -m venv toto_number_analysis
        ```

        - Activating virtual environment
        ```
        source toto_number_analysis/bin/activate
        ```

    - #### Deactivating virtual environment (Windows/Mac)
        - Same for Windows / Mac
        ```bash
        deactivate
        ```

4. **Install necessary libraries from requirements.txt file into virtual environment**:
    ```bash
    pip install -r requirements.txt
    ```

5. **Running the script**:
    ```bash
    python toto_analysis.py
    ```

6. **Navigate with command-line-interface**:
    - Select the option that you want by typing into the command-line
    ```bash
    What data do you want to look at?
    1. Individual bar chart
    2. Grouped bar chart
    3. Overall frequency
    4. Backtest (Most Frequent)
    5. Backtest (Least Frequent)
    6. Confidence interval chart
    7. Monte carlo
    0. End
    ===========================
    Choice:
    ```

---






















































