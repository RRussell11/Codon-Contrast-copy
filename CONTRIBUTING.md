# Contributing to Codon-Contrast SARS2 Work

Thank you for your interest in contributing to the Codon-Contrast SARS2 Work project!

## How to Edit Files

### On GitHub Web Interface

1. **Make sure you are signed in** to your GitHub account
2. Navigate to the file you want to edit
3. Click the **pencil icon** (✏️) in the upper right corner of the file view
   - This is the **Edit button** that allows you to make changes directly in the browser
4. Make your changes in the editor
5. Scroll down to the "Commit changes" section
6. Add a descriptive commit message
7. Choose "Create a new branch" if you don't have write access
8. Click "Propose changes" or "Commit changes"

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RRussell11/Codon-Contrast-copy.git
   cd Codon-Contrast-copy
   ```

2. **Create a new branch:**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes** to the relevant files

4. **Run tests** to ensure everything works:
   ```bash
   python test_sars2_temp.py
   ```

5. **Commit your changes:**
   ```bash
   git add .
   git commit -m "Description of your changes"
   ```

6. **Push to GitHub:**
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Create a Pull Request** on GitHub

## Running Tests

This project includes a test suite to validate functionality. To run the tests:

```bash
python test_sars2_temp.py
```

Or using Python's unittest discovery:

```bash
python -m unittest discover
```

## Code Style

- Follow PEP 8 guidelines for Python code
- Include docstrings for all functions and classes
- Add comments for complex logic
- Keep functions focused and modular

## Questions or Issues?

If you cannot find the edit button or have trouble contributing:
- Make sure you are **signed in** to GitHub
- Verify you have the necessary permissions for the repository
- Check that you're viewing the file (not a directory)
- Look for the pencil icon (✏️) in the upper right of the file view

For additional help, please open an issue on the repository.
