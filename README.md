# 🧵 Haberdashery Management System

Desktop application for managing products in a haberdashery store (CASA DIACO).

## 📌 Description

This project is a Product Management System developed in Python as a final assignment.
It allows managing the product catalog, including stock control, pricing, and product organization.

## 🚀 Features

* Create, update and delete products (soft delete)
* Manage stock and availability
* Search products by name
* Filter products by category
* Associate multiple colors to products

## 🛠️ Technologies

* Python
* MySQL
* mysql-connector-python
* python-dotenv

## ⚙️ Setup

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USER/haberdashery-management-system.git
cd haberdashery-management-system
```

2. Create virtual environment:

```bash
python -m venv venv
```

3. Activate environment:

```bash
venv\Scripts\activate
```

4. Install dependencies:

```bash
pip install mysql-connector-python python-dotenv
```

5. Create `.env` file:

```env
DB_HOST=host
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=haberdashery_db
```

6. Run the project:

```bash
python main.py
```

## 🗂️ Project Structure

```
haberdashery-management-system/
│
├── models/
├── repositories/
├── views/
├── main.py
├── .env
└── README.md
```

## 📖 User Stories

* HU-01: Create product
* HU-02: Update product
* HU-03: Delete product (soft delete)
* HU-04: View and search products

## 📌 Notes

* `.env` file is not included for security reasons
* Requires MySQL running locally

## 👩‍💻 Author

Ariadna Cisterna Diaco
