```markdown
# AGENTS.md - Guidelines for AI Coding Agents

These guidelines detail the expected practices for all AI coding agents working within this repository. Adherence to these principles ensures code maintainability, robustness, and efficiency.

## 1. DRY (Don't Repeat Yourself)

*   **Core Logic Reuse:** Wherever possible, reuse existing logic and data structures across multiple agents. Avoid creating new classes or functions with identical functionality.
*   **Abstraction:**  Implement common operations using abstract classes or interfaces.  This reduces code duplication.
*   **Template Design:** Use templates for common agent structures to standardize code.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimal Code:** Strive for the shortest possible code solution that achieves the required functionality.
*   **Clear Intent:** Each code element should have a single, well-defined purpose.
*   **Readability:**  Prioritize code that is easy to understand and follow.
*   **Avoid Over-Complexity:** Resist unnecessary features or intricate designs.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class or module should have a single, well-defined responsibility.
*   **Open/Closed Principle:** The system should be designed in a way that allows new features to be added without modifying existing code.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:**  Clients should not be forced to depend on methods they do not use.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Focus on Requirements:** Only implement functionality that is explicitly required based on the current requirements.
*   **Future-Proofing:**  Avoid adding features or optimizations that are unlikely to be needed in the future.
*   **Progressive Development:**  Implement features incrementally, only adding them when necessary.

## 5. Development Workflow & Practices

*   **Code Reviews:** All code must undergo mandatory peer review before merging.
*   **Unit Tests:** All code will be accompanied by comprehensive unit tests.
*   **Test Coverage:**  Aim for at least 80% test coverage.  Tools will be used to automatically measure and report coverage.
*   **Documentation:**  Provide clear and concise documentation for all agent components and their interactions.
*   **Versioning:**  Use a robust version control system (e.g., Git) with clear commit messages.
*   **Dependency Management:**  Use a dependency management tool (e.g., Pip, Poetry) to track and manage dependencies.
*   **Error Handling:** Implement robust error handling and logging.

## 6. Code Structure & File Size

*   **Maximum Code Length:** Each file must be no more than 180 lines of code.
*   **Modular Design:**  Break down the codebase into logical modules with well-defined interfaces.
*   **Clear File Naming:**  Use consistent and descriptive file names.

## 7. Testing & Quality Assurance

*   **Comprehensive Testing:**  Develop a robust test suite covering all critical functionality.
*   **Test Case Design:**  Create test cases that cover edge cases, boundary conditions, and error scenarios.
*   **Test Driven Development (TDD):** Consider utilizing TDD principles where appropriate.
*   **Automated Testing:**  Implement automated testing frameworks.

## 8.  Specific Requirements (Example - to be adapted):

*   **Data Models:**  Clearly define data models and their relationships.
*   **Event Handling:**  Provide a consistent approach to event handling across all agents.
*   **Agent Communication:** Define a clear protocol for agent communication.

## 9.  Documentation Standards

*   **README:** A comprehensive README file explaining the project's purpose, architecture, and usage.
*   **API Documentation:**  Generate API documentation using tools like Swagger.
*   **Component Documentation:** Each component will have a dedicated documentation section.

## 10.  Future Considerations

*   **Monitoring:** Implement basic monitoring capabilities to track agent performance.
*   **Scalability:** Consider scalability principles as the system grows.

These guidelines are intended to serve as a framework for development. Deviations must be justified and documented.  Ongoing review and adjustments are encouraged to maintain the integrity and quality of the AGENTS.md repository.
```