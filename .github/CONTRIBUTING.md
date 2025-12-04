# Contributing to PayStub-Generator-Java-CLI-Tool

Thank you for considering contributing to the **PayStub-Generator-Java-CLI-Tool**!

We welcome contributions from everyone. Our goal is to maintain a high-quality, professional, and robust CLI tool. To ensure consistency and efficiency, please follow these guidelines.

## 1. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. Please review the [CODE_OF_CONDUCT.md](https://github.com/chirag127/PayStub-Generator-Java-CLI-Tool/blob/main/CODE_OF_CONDUCT.md) file for details on expected behavior.

## 2. How to Contribute

### 2.1. Reporting Bugs

If you find a bug, please check if it has already been reported. If not, create a new issue on GitHub. Provide a clear and descriptive title, detailed steps to reproduce the bug, expected behavior, and actual behavior. Include relevant environment information (e.g., Java version, OS).

### 2.2. Suggesting Enhancements or Features

We are open to suggestions! Please open a new issue describing your proposed enhancement or feature. Be as detailed as possible about the benefits and use cases.

### 2.3. Contributing Code

We appreciate code contributions! To contribute code:

1.  **Fork the repository:** Create your own fork of `chirag127/PayStub-Generator-Java-CLI-Tool`.
2.  **Clone your fork:** `git clone https://github.com/chirag127/PayStub-Generator-Java-CLI-Tool.git`
3.  **Set up your development environment:** Ensure you have Java 17+ and Maven installed. The project uses Maven for build and dependency management.
    bash
    # Clone the repo
    git clone https://github.com/chirag127/PayStub-Generator-Java-CLI-Tool.git
    cd PayStub-Generator-Java-CLI-Tool

    # Build the project (ensures dependencies are downloaded and compiled)
    mvn clean install
    
4.  **Create a new branch:** Base your work on the `main` branch. Use a descriptive branch name, e.g., `feature/add-deduction-type` or `bugfix/fix-calculation-error`.
    bash
    git checkout -b feature/your-feature-name
    
5.  **Implement your changes:** Write clean, well-documented code. Follow the existing coding style and architectural patterns (e.g., SOLID principles, modular design).
6.  **Write tests:** Ensure your changes are covered by unit tests. New features should have corresponding tests. Run tests to verify:
    bash
    mvn test
    
7.  **Lint and format:** The project uses **Ruff** (via Maven plugins or equivalent Java linters like Checkstyle/PMD if configured). Ensure code adheres to established formatting standards. The goal is zero linting errors.
8.  **Commit your changes:** Use clear and concise commit messages. Adhere to conventional commit message standards if possible.
    bash
    git add .
    git commit -m "feat: Add support for overtime calculations"
    
9.  **Push to your fork:** `git push origin feature/your-feature-name`
10. **Open a Pull Request (PR):** Submit a PR from your fork's branch to the `main` branch of the `chirag127/PayStub-Generator-Java-CLI-Tool` repository.

## 3. Pull Request Process

*   **Clear Description:** Provide a detailed description of your PR, explaining the changes and their purpose. Reference any related issues.
*   **Code Review:** Your PR will be reviewed by project maintainers. Be prepared to address feedback and make necessary adjustments.
*   **CI Checks:** All PRs will be subject to automated checks (CI/CD pipeline) to ensure code quality, test coverage, and adherence to standards. Your changes must pass all checks.

## 4. Development Standards & Principles

*   **Modularity:** Design components for reusability and maintainability.
*   **SOLID Principles:** Adhere to Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion principles.
*   **DRY (Don't Repeat Yourself):** Avoid redundant code.
*   **YAGNI (You Ain't Gonna Need It):** Implement only what is necessary now.
*   **Error Handling:** Implement robust error handling and logging.
*   **Documentation:** Write clear and concise comments for complex logic and public APIs.

## 5. Project Structure (Example - Subject to change)


PayStub-Generator-Java-CLI-Tool/
├── src/
│   ├── main/java/com/example/paystub/
│   │   ├── cli/ (CLI related classes, e.g., CommandLineParser)
│   │   ├── core/ (Core business logic: calculations, data models)
│   │   ├── io/ (Input/Output handling, e.g., file readers/writers)
│   │   └── util/ (Utility classes)
│   └── test/java/com/example/paystub/
│       └── (Unit tests for core logic, CLI, etc.)
├── pom.xml (Maven project configuration)
├── README.md
├── LICENSE
└── .gitignore


## 6. Tools & Technologies

*   **Language:** Java 17+
*   **Build Tool:** Maven
*   **Testing:** JUnit 5
*   **Linting/Formatting:** Adopted Java standards (e.g., via Maven plugins like Checkstyle, PMD).

## 7. Getting Help

If you have questions or need clarification on any of these guidelines, please feel free to open an issue.

We look forward to your contributions!