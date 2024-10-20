<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>🧼 Data Cleaning Master 🧹</h1>
    <p>Welcome to <strong>Data Cleaning Master</strong>, a Python-based application that simplifies the process of cleaning datasets! This tool automates handling duplicates and missing values, making your data analysis smoother and more efficient. 🚀</p>
    <h2>📋 Project Overview</h2>
    <p>This application is designed to:</p>
    <ul>
        <li>✨ <strong>Remove Duplicates</strong>: Identifies and removes duplicate records from your dataset while keeping a copy of them for reference.</li>
        <li>🔍 <strong>Handle Missing Values</strong>: 
            <ul>
                <li>For <strong>numeric columns</strong>: Replaces missing values with the mean.</li>
                <li>For <strong>non-numeric columns</strong>: Drops rows containing missing values.</li>
            </ul>
        </li>
        <li>📁 <strong>Output</strong>: Saves the cleaned version of the dataset, along with files containing the removed duplicates.</li>
    </ul>
    <h2>🛠️ Features</h2>
    <ul>
        <li><strong>User Input</strong>: Accepts dataset file paths and names.</li>
        <li><strong>Randomized Processing Time</strong>: Adds a fun element with a randomized delay before processing, simulating a realistic data cleaning experience.</li>
        <li><strong>Duplicate Handling</strong>: Keeps a separate copy of all identified duplicates.</li>
        <li><strong>Missing Value Imputation</strong>: Uses statistical methods to handle missing values in numeric columns.</li>
        <li><strong>Easy-to-Use</strong>: Simple function call to clean your data and get the output.</li>
    </ul>
    <h2>🧑‍💻 How to Use</h2>
    <ol>
        <li>Clone the repository and navigate to the project directory:
            <pre><code>git clone https://github.com/100rabhhh/Data-Cleaning-Master.git
cd Data-Cleaning-Master
            </code></pre>
        </li>
        <li>Install the required libraries:
            <pre><code>pip install pandas numpy xlrd openpyxl</code></pre>
        </li>
        <li>Run the script:
            <pre><code>from app import data_cleaning_master
data_cleaning_master('path/to/your/dataset.xlsx', 'dataset_name')</code></pre>
        </li>
        <li>The cleaned data and duplicates will be saved in the same directory as your input dataset.</li>
    </ol>
    <h2>🚀 Example</h2>
    <pre><code># Example Usage
data_cleaning_master('sales_data.xlsx', 'Sales Dataset')</code></pre>
    <p>This will:</p>
    <ul>
        <li>🗂️ <strong>Input</strong>: 'sales_data.xlsx'</li>
        <li>🧼 <strong>Process</strong>: Clean the data by removing duplicates and handling missing values.</li>
        <li>💾 <strong>Output</strong>: Save <code>clean_sales_data.xlsx</code> and <code>duplicates_sales_data.xlsx</code>.</li>
    </ul>
    <h2>📊 Testing the Application</h2>
    <p>A Jupyter Notebook (<code>test.ipynb</code>) is included to test the <code>data_cleaning_master</code> function. The notebook demonstrates how to import the function and validate its performance on test datasets.</p>
    <h2>📌 Conclusion</h2>
    <p>The <strong>Data Cleaning Master</strong> project provides a streamlined and user-friendly solution for cleaning datasets, which is crucial in the field of data science and analytics. By automating tasks like removing duplicates and handling missing values, this application saves time and ensures data is ready for analysis. With its simple input process and easy-to-understand output, it empowers users to focus on analyzing clean data rather than worrying about the tedious steps of data cleaning.</p>
    <p>This project showcases the power of Python libraries such as <code>pandas</code> and <code>numpy</code> in handling data efficiently. It is ideal for beginners looking to understand data cleaning concepts as well as professionals seeking a quick tool to preprocess datasets. Happy Cleaning! 🧽✨</p>
     <h2>👥 Credits</h2>
    <p>Built by <a href="https://github.com/100rabhhh">Sourabh Jha</a></p>
    <h2>📄 License</h2>
    <p>This project is licensed under the MIT License.</p>
</body>
</html>
