# Setup Guide

## Prerequisites
- Python 3.8 or higher
- Git 2.x or higher

## How to Run
\\ash
git clone https://github.com/surfingtheinanimatesenses/cse103-lab-LAB3.git
cd cse103-lab-LAB3
python3 src/main.py
\EOF
git add -A
git commit -m 'chore: reorganise into standard src/tests/docs layout'
cat << 'EOF' > .gitignore
# Python bytecode
__pycache__/
*.py[cod]
*.pyo

# Environment files
.env
.venv/
venv/
ENV/

# Build and distribution
dist/
build/
*.egg-info/
.eggs/

# IDE / Editor settings
.vscode/
.idea/
*.swp
*.swo

# Operating system files
.DS_Store
Thumbs.db

# Logs and temporary files
*.log
*.tmp
*.bak
