# Web Application Testing Project

This repository contains a web application along with its comprehensive testing documentation and automation suite.

## Repository Structure

```
.
├── .github/
│   └── workflows/          # CI/CD workflows
├── src/                    # Application source code
├── tests/                  # All test artifacts
│   ├── manual/            # Manual test documentation
│   └── automation/        # Automated test code
└── reports/               # Test execution reports
```

## Quick Start

1. Clone the repository:
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

2. Install dependencies:
```bash
npm install
```

3. Run the application:
```bash
npm start
```

4. Run tests:
```bash
npm test
```

## Testing Overview

- **Test Plan**: Located in `tests/manual/testplan.md`
- **Test Cases**: Located in `tests/manual/testcases/`
- **Test Reports**: Located in `reports/`
- **Automated Tests**: Located in `tests/automation/`

## Quality Assurance

- Manual test cases cover critical user flows
- Automated tests cover regression testing
- CI/CD pipeline runs tests on every push
- Test reports are generated automatically

## Contributing

Please read our contributing guidelines before submitting pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 