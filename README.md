# Cyber-Sec-Google-Dork

Welcome to **Cyber-Sec-Google-Dork**, a powerful and easy-to-use tool for performing Google Dork searches to uncover potential vulnerabilities in web applications. This tool is designed to help security researchers and bug bounty hunters automate the process of finding sensitive information exposed on the internet.

> **Disclaimer:**  
> This tool is **intended for educational purposes only**.  
> **It must not be used for any illegal or unauthorized activities.**  
> Always ensure you have explicit permission to perform testing on websites or systems.  
> **Unauthorized access to systems is illegal and unethical.**

---

## 🚀 Features

- **Automated Google Dork Search**: Performs Google search queries for specific dorks to identify vulnerable or misconfigured web applications.
- **Customizable Querying**: Enter your custom dork search queries and define the number of results to retrieve.
- **Result Saving**: Saves the results to a file for easy access and further analysis.
- **Simple and Interactive**: The tool is designed to be user-friendly with interactive prompts and an intuitive interface.

---

## ⚙️ Installation

To get started with Cyber-Sec-Google-Dork, follow these simple steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/cybersnippets/Cyber-Sec-Google-Dork.git
    ```

2. **Install the necessary dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

---

## 💻 Usage

1. Run the script:
    ```bash
    python google_dork_scanner.py
    ```

2. Follow the interactive prompts:
    - Enter the **Google Dork search query** (e.g., `"intitle:index.of"`, `"inurl:admin"`, etc.).
    - Enter the **number of results** you want to display (e.g., 10, 20, etc.).

3. The tool will display the **search results** and save them to a text file (`dork_results.txt` by default).

---

## 🎯 Example

```bash
[*] Enter the Dork Search Query: inurl:admin
[*] Enter the Number of Websites to Display: 5

[+] Searching for: inurl:admin

[+] Results:
https://example.com/admin
https://anotherexample.com/admin

[+] Results have been saved to dork_results.txt.
