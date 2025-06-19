# 🌤 Weather Data Analysis Tool

## 📘 Project Description

Create a Python application that can **fetch, process, and display weather data** for different cities. Users can input a city name to retrieve its **current weather** and **historical weather data for the past seven days**. The application also includes **simple statistical analysis** on historical data and allows saving the results to a file.

---

## ✨ Key Features

### 1. User Input
- Accepts user input for the **city name**
- Validates input to ensure it’s a non-empty string

### 2. API Integration (Functions and Modules)
- Integrates with a **weather API** to fetch:
  - Current weather data
  - Historical weather data (last 7 days)
- Uses **modular code design**:
  - Functions for data fetching, processing, and displaying

### 3. Math Operations
- Calculates:
  - **Average**
  - **Median**
  - **Mode**  
  ...of historical temperature data

### 4. String Manipulation
- Outputs user-facing information in a **readable and well-formatted** manner
- Includes proper units (e.g., °C/°F, % humidity)

### 5. Iterables (Sequences, Dictionaries, Sets)
- Stores data using appropriate data structures:
  - Lists for sequences
  - Dictionaries for daily weather data
  - Sets if applicable

### 6. Virtual Environments and Packages
- Uses a **Python virtual environment**
- Includes a `requirements.txt` to manage dependencies

### 7. Flow Control
- Uses **if/else statements** and **loops** to control application logic
- Handles scenarios like invalid cities or no data returned

### 8. Exception Handling
- Implements **try/except blocks** to handle:
  - Network/API issues
  - Input errors
  - File I/O errors

### 9. Date and Time
- Uses Python's `datetime` module to handle and format dates
- Calculates past 7 days from the current date

### 10. File Processing
- Saves:
  - Raw weather data
  - Statistical summaries
- In formats like **CSV** or **JSON**

### 11. Code Style and Linting
- Follows **PEP8 guidelines**
- Uses tools like `pylint` or `flake8` to maintain code quality

---

## ✅ Assessment Criteria

- **Code Quality**: Readable, modular, PEP8-compliant
- **Error Handling**: Gracefully handles exceptions without crashing
- **Correctness**: Provides accurate statistical results
- **Documentation**: Well-commented code + clear usage instructions
- **Packaging**: Proper use of virtual environments and dependency management

