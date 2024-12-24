# My Python Project

This is a sample Python project that demonstrates how to use Ruff for linting and formatting checks.

## Structure
- `src/example.py`: Sample Python code.
- `pyproject.toml`: Ruff configuration file.
- `.github/workflows/ci.yaml`: GitHub Actions CI for Ruff checks.

## Running Ruff Locally
To test Ruff locally, run the following commands:

```bash
pip install ruff
ruff check src
```
---

### **How to Test the Workflow**
1. **Create the Repository**:
   - Create a new GitHub repository and clone it.
   - Add the above files and push them to the repository.

2. **Trigger the Workflow**:
   - Make a change in `src/example.py` or open a pull request.
   - Check the **Actions** tab in the GitHub repository to see the Ruff CI workflow running.

3. **Fix Issues**:
   - Ruff will output errors or warnings. Fix them in the code and push the changes.

---

### **Expected Output in GitHub Actions**
When you run the workflow, it will catch issues like:
- Improper spacing in `print( "Hello, world!" )`.
- Missing newline at the end of the file.

---

Let me know if you need help setting this up or want to expand it further!

