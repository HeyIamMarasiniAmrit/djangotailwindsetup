# Django + Tailwind CSS Setup

Minimal **Django 5.x** + **Tailwind CSS 3.x** starter template with modern frontend tooling.

Clean structure · No bloat · Ready for small to medium projects.

## Features

- Django 5.0+ (or latest stable)
- Tailwind CSS v3.4+ with JIT mode
- django-browser-reload (great dev experience)
- PostCSS + Autoprefixer
- `src/` folder structure (recommended modern layout)
- Basic example components & utility classes demo
- Works well with VS Code + Tailwind IntelliSense

## Quick Start

```bash
# 1. Clone and enter folder
git clone https://github.com/yourusername/djangotailwindsetup.git
cd djangotailwindsetup

# 2. Create & activate virtual environment
python -m venv .venv
source .venv/bin/activate    # Windows → .venv\Scripts\activate

# 3. Install Python dependencies
pip install -r requirements.txt

# 4. Install Tailwind & frontend dependencies
cd src/static_src
npm install
cd ../../

# 5. Build Tailwind CSS (first time)
npm run build:css --prefix src/static_src

# 6. Run development server
python manage.py runserver
<img width="615" height="933" alt="Image" src="https://github.com/user-attachments/assets/345c70ee-505c-45de-9778-568923a4575f" />
