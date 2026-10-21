# About the Project

This repository contains Python programs developed as part of the **S.Y. B.Tech. Computer Engineering curriculum**. It covers Python basics, NumPy, Pandas, Matplotlib, Seaborn, data analysis, and matrix operations.

The aim of this project is to understand Python programming concepts through practical examples, perform numerical computations, manipulate datasets, create visualizations, and analyze real-world data.

The programs are designed to be beginner-friendly and can be executed using **Jupyter Notebook** or a Python IDE such as VS Code or PyCharm.

## 🎯 Objectives

- Understand Python data types and built-in functions.
- Create and manipulate NumPy arrays.
- Perform vectorized operations and broadcasting.
- Generate random numbers and simulate distributions.
- Create and analyze Pandas Series and DataFrames.
- Clean datasets and handle missing values.
- Create graphs using Matplotlib and Seaborn.
- Analyze real-world datasets using statistical techniques.
- Solve matrix equations and perform linear algebra operations.

## 🛠️ Technologies Used

- **Language:** Python
- **Notebook Environment:** Jupyter Notebook
- **IDE:** VS Code / PyCharm
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn
- **Version Control:** Git and GitHub

## 📂 Project Structure

```text
python-programming-practicals/
│
├── README.md
├── requirements.txt
│
├── 01_python_data_types.py
├── 02_numpy_arrays.py
├── 03_vectorization_broadcasting.py
├── 04_random_simulation.py
├── 05_pandas_series_dataframe.py
├── 06_pandas_data_cleaning.py
├── 07_matplotlib_visualization.py
├── 08_matplotlib_subplots.py
├── 09_seaborn_visualization.py
├── 10_real_world_data_analysis.py
└── 11_numpy_matrix_operations.py
```

*Note: The filenames above are suggested names. Update them to match the actual files in your repository.*

## 📚 Practicals Covered

### 1. Python Data Types and Mathematical Operations

Demonstrates Python's built-in data types and their operations.

**Topics covered:**
- Integer, float, complex, string, list, tuple, dictionary, set, frozenset, Boolean, and NoneType.
- Type checking and type conversion.
- Built-in functions and basic mathematical operations.
- Mathematical functions using the `math` module.

**Functions used:** `type()`, `print()`, `len()`, `sum()`, `max()`, `min()`, `abs()`, `round()`, `math.sqrt()`, `math.ceil()`, `math.floor()`, `math.factorial()`.

### 2. NumPy Arrays and Array Operations

Creates one-dimensional and two-dimensional arrays and performs array manipulation.

**Topics covered:**
- Array creation and indexing.
- Slicing and reshaping.
- Basic mathematical operations.
- Sum and mean calculations.

**Functions used:** `np.array()`, `np.arange()`, `np.linspace()`, `np.reshape()`, `np.sum()`, `np.mean()`.

### 3. Vectorization, Broadcasting, and Universal Functions

Demonstrates efficient mathematical operations on NumPy arrays without writing explicit loops for every element.

**Topics covered:**
- Vectorized arithmetic.
- Broadcasting between compatible array shapes.
- Applying universal functions to array elements.

**Functions used:** `np.add()`, `np.sqrt()`, `np.exp()`.

### 4. Random Number Generation and Simulation

Generates random values, simulates distributions, and calculates basic statistics.

**Topics covered:**
- Uniform and normal random values.
- Random integers.
- Statistical summaries.
- Simple simulations, such as rolling a die.

**Functions used:** `np.random.rand()`, `np.random.randn()`, `np.random.randint()`, `np.random.normal()`, `np.mean()`, `np.std()`.

### 5. Pandas Series, DataFrames, and CSV Operations

Creates Series and DataFrames, reads tabular data, and exports data to CSV files.

**Topics covered:**
- Series and DataFrame creation.
- Importing CSV files.
- Viewing and describing datasets.
- Selecting columns and basic data analysis.
- Exporting results.

**Functions used:** `pd.Series()`, `pd.DataFrame()`, `pd.read_csv()`, `df.head()`, `df.tail()`, `df.describe()`, `df.to_csv()`.

### 6. Data Cleaning and Manipulation

Handles incomplete data and performs common data manipulation operations.

**Topics covered:**
- Detecting missing values.
- Filling or removing missing records.
- Replacing values.
- Filtering rows and selecting columns.
- Sorting and grouping data.

**Functions used:** `df.isnull()`, `df.fillna()`, `df.dropna()`, `df.replace()`, `df.sort_values()`, `df.groupby()`.

### 7. Basic Data Visualization with Matplotlib

Creates different types of graphs to represent data visually.

**Topics covered:**
- Line charts.
- Bar charts.
- Scatter plots.
- Histograms.
- Axis labels and graph presentation.

**Functions used:** `plt.plot()`, `plt.bar()`, `plt.scatter()`, `plt.hist()`, `plt.xlabel()`, `plt.ylabel()`, `plt.show()`.

### 8. Subplots, Styling, Legends, and Grid

Creates multiple plots in one figure and improves their readability.

**Topics covered:**
- Multiple plots and subplot layouts.
- Graph titles and legends.
- Grid lines and styling.
- Comparing multiple datasets.

**Functions used:** `plt.subplot()`, `plt.legend()`, `plt.grid()`, `plt.title()`.

### 9. Statistical Visualization with Seaborn

Creates statistical graphs using Seaborn.

**Topics covered:**
- Line plots.
- Bar plots.
- Histograms.
- Box plots.
- Scatter plots.

**Functions used:** `sns.lineplot()`, `sns.barplot()`, `sns.histplot()`, `sns.boxplot()`, `sns.scatterplot()`.

### 10. Real-World Dataset Analysis

Loads a real-world dataset and performs data analysis and visualization.

**Topics covered:**
- Dataset loading and exploration.
- Summary statistics.
- Missing-value detection and handling.
- Correlation analysis.
- Heatmap visualization.

**Tools used:** Pandas, Matplotlib, Seaborn.

**Functions used:** `pd.read_csv()`, `df.describe()`, `df.isnull()`, `df.corr(numeric_only=True)`, `sns.heatmap()`.

### 11. NumPy Matrix Operations and Linear Algebra

Solves systems of linear equations and performs matrix calculations.

**Topics covered:**
- Solving simultaneous linear equations.
- Matrix inverse and transpose.
- Eigenvalues and eigenvectors.
- Determinant and trace calculations.

**Functions used:** `np.linalg.solve()`, `np.linalg.inv()`, `np.linalg.eig()`, `np.linalg.det()`, `np.trace()`.

## ⚙️ Installation and Setup

### Step 1: Install Python

Download and install Python from the official website:

https://www.python.org/downloads/

Check whether Python is installed:

```bash
python --version
```

### Step 2: Clone the Repository

Replace `YOUR_USERNAME` with your GitHub username.

```bash
git clone https://github.com/YOUR_USERNAME/python-programming-practicals.git
cd python-programming-practicals
```

### Step 3: Create a Virtual Environment (Recommended)

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

If you use Command Prompt instead of PowerShell:

```cmd
.venv\Scripts\activate.bat
```

### Step 4: Install Required Libraries

```bash
python -m pip install -r requirements.txt
```

If a `requirements.txt` file is not available, install the libraries directly:

```bash
python -m pip install numpy pandas matplotlib seaborn jupyter
```

## ▶️ How to Run the Programs

### Using a Python IDE

Open the repository folder in VS Code or another Python IDE. Select the Python interpreter associated with your virtual environment, then run a program:

```bash
python 01_python_data_types.py
```

Replace the filename with the program you want to execute.

### Using Jupyter Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Create a new Python notebook, add the required code, and execute cells using **Shift + Enter**.

## 📊 Expected Results

Depending on the practical, the programs produce:

- Console output demonstrating data types and calculations.
- NumPy array and matrix results.
- CSV files containing processed data.
- Summary statistics and cleaned datasets.
- Line, bar, scatter, and histogram plots.
- Multi-plot dashboards and statistical visualizations.
- Correlation heatmaps and matrix calculations.

## 💡 Learning Outcomes

After completing these practicals, I can:

- Work with Python's basic data types and mathematical functions.
- Create and manipulate arrays using NumPy.
- Apply vectorization and broadcasting to numerical data.
- Read, process, clean, and export datasets using Pandas.
- Visualize information using Matplotlib and Seaborn.
- Perform basic exploratory data analysis on real-world data.
- Apply NumPy linear algebra functions to solve matrix problems.

## 🚀 Future Improvements

- Add sample datasets and practical output screenshots.
- Include Jupyter Notebook versions of the programs.
- Add more real-world data analysis projects.
- Improve visualizations with interactive dashboards.
- Add explanations and sample outputs for each practical.

## 👩‍💻 Author

**Siddhi Bhingole**  
S.Y. B.Tech. Computer Engineering Student

This repository is maintained for academic learning, practical submissions, and continuous improvement of Python programming and data analysis skills.

## 📄 License

This project is intended for educational and learning purposes. You may adapt the examples for practice, with appropriate attribution where applicable.
```

## 📄 Create `requirements.txt`

Create another file named `requirements.txt` in the same folder and add:

```text
numpy
pandas
matplotlib
seaborn
jupyter
```

## ⬆️ Upload the project to GitHub

Run these commands from your project folder:

```bash
git init
git add README.md requirements.txt
git add .
git commit -m "Add Python programming practicals"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/python-programming-practicals.git
git push -u origin main
```

If Git is already initialized and the remote repository is already connected, skip `git init` and `git remote add origin ...`. If you already have a GitHub repository, use its actual URL.

**One important tip:** Keep your actual `.py` files and any required sample datasets in the repository. The README explains the work, but the practical code files are what make the project complete and runnable.
