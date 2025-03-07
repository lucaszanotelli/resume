**JSON-Based CV Repository**

This repository stores my CV in a structured JSON format, leveraging the [JSON Resume](https://github.com/jsonresume) standard for easy maintenance and customization. The CV is hosted on **GitHub Pages** and can be viewed live at [zanotelli.dev](https://zanotelli.dev).

### Key Features:
- **JSON Format**: The CV is written in JSON, making it highly portable and easy to update.
- **Themed Output**: Utilizes the [resumed](https://github.com/rbardini/resumed) tool to export the CV into a beautifully formatted HTML page using the `stackoverflow` theme.
- **Hosting**: Deployed on GitHub Pages for seamless online access.

### How to Update/Run:
To generate or update the CV, use the following command:
```bash
resumed render resume.json --output docs/resume.html --theme jsonresume-theme-stackoverflow
```

This project is ideal for developers looking to manage their resumes programmatically and showcase them in a clean, professional format.

