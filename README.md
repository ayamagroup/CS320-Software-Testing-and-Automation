# CS320-Software-Testing-and-Automation Portfolio

- **Project One:** Demonstrates the Contact service (Contact.java, ContactService.java, ContactTest.java, ContactServiceTest.java). These files showcase my approach to creating unit tests, handling data validation, and ensuring each method meets defined requirements.
- **Project Two:** Includes a summary and reflections report. This highlights my methodology for analyzing testing strategies, applying them based on the project’s constraints, and ensuring good coverage.

## Reflection

### Ensuring Functionality and Security
I rely on unit tests and boundary checks to confirm that each component behaves as expected. By setting up tests for normal data, invalid entries, and edge values, I cover likely failure points. Security is partly addressed by preventing unexpected inputs (e.g., null fields, overly long strings) that could lead to crashes or vulnerabilities. Continuous testing and code reviews also help detect issues before deployment.

### Interpreting User Needs
I translate requirements into specific, testable items. If a user needs a 10-character maximum for an ID, I write test cases for IDs with exactly 10 characters, more than 10, and fewer than 10. This process ensures functionality remains aligned with real user expectations, since I’m verifying each constraint directly in the code.

### Designing Software
I break each requirement into smaller, testable components. This modular approach helps clarify the scope of each function or service. If a service deals with data storage, I isolate that logic so I can test it independently. This design strategy keeps the codebase organized, makes tests straightforward to write, and reduces complexity when features expand.

