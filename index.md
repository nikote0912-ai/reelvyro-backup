---
title: REELVYRO Backup
---

# REELVYRO Backup

## About the application

REELVYRO Backup is a private administrative tool
designed to securely back up the REELVYRO
application database.

## Purpose

The application is designed to:

- Create encrypted PostgreSQL database backups.
- Store encrypted backups in Google Drive.
- Verify backup integrity.
- Support disaster recovery.
- Perform scheduled automated backups.

## Google Drive access

REELVYRO Backup uses the Google Drive API
with the limited drive.file permission.

The application uses this permission to manage
backup files that it creates or is explicitly
authorized to access.

## Security

Database backups are encrypted using AES-256
before being uploaded to Google Drive.

Encryption keys are stored separately
from the uploaded backup files.

The application is intended for authorized
REELVYRO administrative use.

## Privacy Policy

[Read our Privacy Policy](privacy.html)
