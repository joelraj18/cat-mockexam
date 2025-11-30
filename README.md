# 🎓 cat-mockexam: CAT Exam Interface Clone

An attempt to replicate the user interface and key functionalities of the Common Admission Test (CAT) computer-based examination.

## ✨ Project Overview

This project is a high-fidelity simulation of the Common Admission Test (CAT) examination interface. The goal is to provide test-takers with a realistic environment to practice navigation, time management, and the use of integrated tools (like the on-screen calculator), thereby reducing anxiety on the actual exam day.

The application is built using modern web technologies to deliver a fast and responsive user experience that closely mimics the official testing platform.

## 💻 Tech Stack

This website is a Single Page Application (SPA) built with the following technologies:

| Category | Technology | Description |
| :--- | :--- | :--- |
| **Frontend Framework** | React | Used for building the component-based, interactive user interface. |
| **Markup** | HTML | The fundamental building blocks of the application structure. |
| **Styling** | CSS / Tailwind CSS | Tailwind CSS is used for rapid, utility-first styling, ensuring a clean and consistent design across all mock screens. |
| **Package Management** | npm | Used to manage and install project dependencies. |

## 🚀 Key Features

The mock interface includes all critical elements found in the real CAT exam:

* **Section Timer:** A strictly enforced countdown for each section.
* **Question Panel:** A dynamic display of question status (Answered, Not Answered, Marked for Review).
* **On-Screen Calculator:** A functioning virtual calculator provided for calculations during the exam.
* **Navigation:** Buttons for **Save & Next**, **Mark for Review**, and **Clear Response**.
* **Section Management:** Clear display of current and remaining sections (VARC, DILR, QA).

## 🔧 Installation and Setup

### Prerequisites

* Node.js (LTS recommended)
* npm (comes bundled with Node.js)

### Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/joelraj18/cat-mockexam.git](https://github.com/joelraj18/cat-mockexam.git)
    cd cat-mockexam
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Run the application in development mode:**
    ```bash
    npm start
    ```
    The application will open automatically in your browser at `http://localhost:3000`. Changes will hot-reload.

## 🤝 Contributing

Contributions are welcome! If you find a feature that could be more accurately cloned or a bug that needs fixing, please open an issue or submit a pull request.

## 📝 License

This project is licensed under the MIT License - see the `LICENSE` file for details.