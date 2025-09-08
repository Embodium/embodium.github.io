# Static Assets Structure

This directory contains static assets organized by project to avoid conflicts in the monorepo.

## Directory Structure

```
static/
├── portfolio/          # Portfolio website assets
│   ├── css/           # Compiled CSS files (SMUI themes, etc.)
│   ├── js/            # JavaScript files
│   └── images/        # Images, icons, etc.
├── admin/             # Admin dashboard assets (future)
│   ├── css/
│   ├── js/
│   └── images/
└── blog/              # Blog assets (future)
    ├── css/
    ├── js/
    └── images/
```

## Usage

- **CSS**: Generated SMUI themes and custom stylesheets
- **JS**: Client-side scripts, web workers, etc.
- **Images**: Logos, icons, backgrounds, etc.

## Benefits

- **Namespace isolation**: Each project has its own asset directory
- **Conflict prevention**: No asset name collisions between projects
- **Clear ownership**: Easy to identify which assets belong to which project
- **Scalable**: Easy to add new projects without restructuring
