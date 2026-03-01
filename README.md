# ShopSync

Personal inventory management tool for my Etsy shops.

## Overview

ShopSync helps me track and manage my LJChicBoutique Etsy shop. Built to replace manual spreadsheet tracking with automated data pulls from the Etsy API.

## Features (Planned)

- Track listing performance over time
- Monitor sales history and pricing effectiveness
- View inventory levels across multiple shops
- Analyze which listings get the most engagement

## Status

Currently in development. Personal use only.

## Tech Stack

- Backend: Python/Flask
- Database: PostgreSQL
- Frontend: React (planned)

## Setup

(To be added as development progresses)

## API Access

This application uses the Etsy API but is not endorsed or certified by Etsy, Inc.
```

**LICENSE**
```
MIT License

Copyright (c) 2026 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

**.gitignore**
```
# Python
__pycache__/
*.py[cod]
*$py.class
*.so
.Python
venv/
env/
.venv
*.egg-info/
dist/
build/

# Node
node_modules/
npm-debug.log*
yarn-debug.log*
dist/
build/

# Environment
.env
.env.local
.env.*.local

# Etsy API credentials
etsy_credentials.json
*.keystring
api_keys.json

# Database
*.db
*.sqlite
*.sqlite3

# IDEs
.vscode/
.idea/
*.swp
*.swo

# OS
.DS_Store
Thumbs.db

# Logs
*.log
logs/
```

**Basic folder structure (create empty directories):**
```
shop-sync/
├── README.md
├── LICENSE
├── .gitignore
├── backend/
│   └── (empty for now)
├── frontend/
│   └── (empty for now)
└── docs/
    └── (empty for now)
