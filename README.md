# ========================================
# RaffiAraha - Root .gitignore
# ========================================

# Dependencies
node_modules/
.pnp
.pnp.js

# Next.js
.next/
out/
build/
dist/

# Environment
.env
.env.local
.env.*.local

# Uploads (فقط .gitkeep نگه داشته شود)
uploads/*
!uploads/.gitkeep

# Backups
backups/*
!backups/.gitkeep

# Logs
*.log
npm-debug.log*
yarn-debug.log*
yarn-error.log*
pnpm-debug.log*

# OS
.DS_Store
Thumbs.db
desktop.ini

# IDE
.vscode/
.idea/
*.swp
*.swo

# Cache
.cache/
.temp/
.tmp/
