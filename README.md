# MASA PatientCare EHR

Electronic health record and clinical patient history tracking platform for healthcare providers

## Technical Architecture

The application is structured following modular separation of concerns and modern object-oriented software patterns:

- **Component Layering**: UI presentation views, operational business logic, and persistent storage abstractions are cleanly isolated.
- **Defensive Engineering**: Robust input sanitization and defensive exception management preventing unhandled runtime faults.
- **Modern Developer Experience**: High-contrast interface aesthetics adhering to professional software engineering standards.

## Preview

![Application Interface](screenshots/app_interface.png)

## Prerequisites

- Python 3.10 or higher
- Required libraries:

```bash
pip install customtkinter pillow
```

## Execution

Launch the application via Python:

```bash
python "Patient Record Management System/index.py"
```

## Project Structure

```
.
├── Patient Record Management System
├── screenshots/
│   └── app_interface.png
├── .gitignore
├── LICENSE             # MIT License
└── README.md           # Developer documentation
```

## License

This project is licensed under the terms of the MIT License. Refer to the `LICENSE` file for details.
