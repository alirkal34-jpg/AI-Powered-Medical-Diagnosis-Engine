# Contributing to AI-Powered Medical Diagnosis Engine

First off, thank you for considering contributing to this project! 🎉

## 📋 Table of Contents
- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Development Setup](#development-setup)
- [Pull Request Process](#pull-request-process)
- [Coding Standards](#coding-standards)
- [Commit Guidelines](#commit-guidelines)

---

## 📜 Code of Conduct

This project adheres to a Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to alir.kal34@gmail.com.

---

## 🤝 How Can I Contribute?

### Reporting Bugs 🐛
- Use the GitHub Issues tracker
- Check if the bug has already been reported
- Include detailed steps to reproduce
- Provide system information (OS, Python version, etc.)

### Suggesting Enhancements 💡
- Open an issue with the tag "enhancement"
- Clearly describe the feature and its benefits
- Provide examples if possible

### Code Contributions 🔧
- Fork the repository
- Create a feature branch
- Write clean, documented code
- Add tests if applicable
- Submit a pull request

---

## 🛠 Development Setup

### Prerequisites
```bash
Python 3.8+
pip
git
```

### Installation Steps
```bash
# 1. Fork and clone the repository
git clone https://github.com/YOUR_USERNAME/AI-Powered-Medical-Diagnosis-Engine.git
cd AI-Powered-Medical-Diagnosis-Engine

# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
cd Automatic-Medical-Diagnosis-using-DDXPlus-Dataset
pip install -r requirements.txt

# 4. Run tests (if available)
python -m pytest
```

---

## 🔄 Pull Request Process

### Before Submitting
1. ✅ Update the README.md if needed
2. ✅ Follow the coding standards
3. ✅ Test your changes thoroughly
4. ✅ Update documentation

### PR Template
```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Performance improvement

## Testing
Describe how you tested your changes

## Checklist
- [ ] Code follows PEP 8
- [ ] Comments added where necessary
- [ ] Documentation updated
- [ ] Tests pass locally
```

---

## 💻 Coding Standards

### Python Style Guide
- Follow **PEP 8** guidelines
- Use **type hints** where appropriate
- Write **docstrings** for all functions/classes
- Keep functions small and focused

### Example
```python
def predict_pathology(patient_data: dict) -> str:
    """
    Predict pathology based on patient symptoms.
    
    Args:
        patient_data (dict): Dictionary containing patient symptoms
        
    Returns:
        str: Predicted pathology name
        
    Raises:
        ValueError: If patient_data is invalid
    """
    # Implementation here
    pass
```

### File Organization
- One class per file (when possible)
- Group related functions
- Keep imports organized (standard → third-party → local)

---

## 📝 Commit Guidelines

### Commit Message Format
```
<type>(<scope>): <subject>

<body>

<footer>
```

### Types
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code formatting
- `refactor`: Code restructuring
- `test`: Adding tests
- `chore`: Maintenance tasks

### Examples
```bash
feat(model): add XGBoost classifier
fix(preprocessing): handle missing values correctly
docs(readme): update installation instructions
```

---

## 🧪 Testing

### Running Tests
```bash
# Run all tests
python -m pytest

# Run specific test file
python -m pytest tests/test_preprocessing.py

# Run with coverage
python -m pytest --cov=src
```

### Writing Tests
- Write unit tests for new functions
- Test edge cases
- Use descriptive test names

---

## 📚 Documentation

### Code Documentation
- Add docstrings to all public functions
- Include parameter types and return values
- Provide usage examples

### README Updates
- Keep installation steps current
- Document new features
- Update examples if API changes

---

## 🎯 Priority Areas

We especially welcome contributions in:
1. 🧠 **Model improvements** (new algorithms, hyperparameter tuning)
2. 📊 **Visualizations** (new charts, interactive plots)
3. 🌐 **Web interface** (Flask/FastAPI integration)
4. 📖 **Documentation** (tutorials, examples)
5. 🧪 **Testing** (unit tests, integration tests)

---

## 💬 Questions?

Feel free to:
- Open an issue for discussion
- Contact: alir.kal34@gmail.com
- Check existing issues and PRs

---

## 🙏 Thank You!

Your contributions make this project better for everyone. We appreciate your time and effort! ⭐

---

## 📄 License

By contributing, you agree that your contributions will be licensed under the MIT License.