# Cronjob-Scheduler
Project Overview
cronscheduler.sh is a Bash script designed to simplify cron job management on Linux and macOS systems. It provides an intuitive, menu-driven interface for users to view, schedule, delete, and backup cron tasks without manually editing crontab files.

Built for PID-08 as a Linux team project.

✨ Key Features
View Current Cron Jobs: List all active cron entries in a readable format.

Add New Jobs: Step-by-step prompts for scheduling (minute/hour/day/month/command).

Delete Jobs: Select and remove cron jobs from an interactive list.

Backup & Restore: Save crontab to a file (cron_backup.txt) or restore from backup.

User-Friendly UI: Navigate with keyboard arrows (thanks to dialog).

⚙️ Requirements
Linux or macOS (Unix-like systems).

Bash (v5+ recommended).

dialog package (for the terminal UI).

📝 Important Notes
User-Level Only: Modifies the current user’s crontab (no system-wide changes).

Backups: Saved as cron_backup.txt in the script’s directory (path editable in code).

Safety: Confirmation prompts prevent accidental deletions.
