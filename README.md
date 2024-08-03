# Pokemon-Generation-7-Dive-Deep-using-SQL

This project provides a detailed analysis of Pokémon Generation 7 data using SQL. The analysis is performed within a Python environment, utilizing SQLite for database management. The notebook dives deep into various aspects of Pokémon, such as moves, abilities, items, and more.

## Project Overview

The notebook analyzes multiple datasets related to Pokémon Generation 7, including:

- **movesets**: Information about the moves each Pokémon can learn.
- **items**: Details about items used in the game.
- **moves**: Attributes of different Pokémon moves.
- **abilities**: Information about Pokémon abilities.
- **pokemon**: Stats and characteristics of Pokémon species.
- **natures**: Effects of different natures on Pokémon stats.
- **types**: Type effectiveness and interactions between different Pokémon types.

The project loads these datasets into a SQLite database and performs SQL queries to extract valuable insights.

## Key Features

- **Data Loading**: The project loads various Pokémon-related datasets into a SQLite database.
- **SQL Queries**: The notebook contains several SQL queries to explore and analyze different aspects of the Pokémon Generation 7 data.
- **Data Exploration**: The SQL queries help to understand moves, items, abilities, and other attributes related to Pokémon in Generation 7.

## Getting Started

### Prerequisites

To run the notebook, you'll need the following:

- **Python 3.x** installed.
- **SQLite3**: Used as the database engine for running SQL queries.
- **Pandas**: For data manipulation and analysis.
- **Jupyter Notebook**: To run the `.ipynb` file interactively.

You can install the required Python packages using pip:

```bash
pip install pandas sqlite3
```

### Running the Notebook

1. Navigate to the project directory:
   ```bash
   cd pokemon-gen7-sql-analysis
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open the `Pokemon Generation 7 Dive Deep using SQL.ipynb` file and run the cells to execute the analysis.

## Project Structure

- `Pokemon Generation 7 Dive Deep using SQL.ipynb`: The main Jupyter Notebook containing the SQL queries and analysis.
- `data/`: A directory where you should place your Pokémon datasets (e.g., `pokemon_gen7.csv`, `moves.csv`).

## Contributions

Contributions are welcome! If you have any suggestions, improvements, or additional queries to include, feel free to fork this repository and submit a pull request.

## Acknowledgements

- The Pokémon Company for the game data.
- The Python community for providing essential libraries like Pandas and SQLite.
