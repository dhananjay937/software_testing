# 📌 Software Testing Projects

This repository contains two basic testing projects using **PyTest**:
1. **API Testing** - Tests a public API using `requests` and `pytest`
2. **Calculator Unit Testing** - Tests a simple Python calculator

---

## 🚀 1. API Testing Project

### **📖 Description**
This project tests a public REST API (JSONPlaceholder) to validate GET, POST, and DELETE requests using `pytest`.

### **🛠 Installation**
Make sure you have **Python 3.x** installed.
Then, install dependencies:

```bash
pip install pytest requests
```

### **📄 Files**
- `test_api.py` → Contains test cases for API endpoints

### **📝 Test Cases**
- `test_get_posts()` → Tests fetching all posts
- `test_create_post()` → Tests creating a new post
- `test_delete_post()` → Tests deleting a post

### **▶️ Running Tests**
Run the tests using:
```bash
pytest test_api.py
```

---

## 🚀 2. Calculator Unit Testing Project

### **📖 Description**
A simple calculator with basic arithmetic operations (`add`, `subtract`, `multiply`, `divide`) tested using `pytest`.

### **🛠 Installation**
Install `pytest`:
```bash
pip install pytest
```

### **📄 Files**
- `calculator.py` → Contains basic arithmetic functions
- `test_calculator.py` → Contains unit test cases

### **📝 Test Cases**
- `test_add()` → Tests addition function
- `test_subtract()` → Tests subtraction function
- `test_multiply()` → Tests multiplication function
- `test_divide()` → Tests division function (handles zero division)

### **▶️ Running Tests**
Run the tests using:
```bash
pytest test_calculator.py
```

---

## 📌 Notes
- PyTest automatically discovers test files that start with `test_`.
- You can view detailed test results using:
  ```bash
  pytest -v
  ```
- To run tests with coverage:
  ```bash
  pip install pytest-cov
  pytest --cov=.
  ```

---

### 🔥 Happy Testing! 🚀

