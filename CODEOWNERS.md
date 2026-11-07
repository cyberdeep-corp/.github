# CyberDeep Corporate — Code Ownership
#
# This file defines the default code owners for this repository.
# Replace the example GitHub usernames with actual maintainer accounts.
#
# Documentation:
# https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners

# Default owner for all files
* @cyberdeep-corp

# GitHub community health files
/.github/ @cyberdeep-corp-db0

# Documentation
/docs/ @YOUR_GITHUB_USERNAME
*.md @cyberdeep-corp-db0

# Python backend
*.py @YOUR_GITHUB_USERNAME
/requirements*.txt @YOUR_GITHUB_USERNAME
/pyproject.toml @YOUR_GITHUB_USERNAME

# Frontend
*.html @YOUR_GITHUB_USERNAME
*.css @YOUR_GITHUB_USERNAME
*.js @YOUR_GITHUB_USERNAME
*.ts @YOUR_GITHUB_USERNAME
*.tsx @YOUR_GITHUB_USERNAME

# Configuration and deployment
/.github/workflows/ @YOUR_GITHUB_USERNAME
/Dockerfile @YOUR_GITHUB_USERNAME
/docker-compose.yml @YOUR_GITHUB_USERNAME
/vercel.json @YOUR_GITHUB_USERNAME

# Security-sensitive project files
/SECURITY.md @YOUR_GITHUB_USERNAME
/.env.example @YOUR_GITHUB_USERNAME
