# Infoplakat Doorbell Releases

Auto-update releases for Infoplakat Doorbell (Electron app).

## Files

- `latest.yml` - Windows update manifest
- `*.exe` - Windows installer

## Usage

These files are automatically downloaded by the Electron auto-updater.

## Publishing

After building a new version:
1. Update version in `package.json`
2. Run `npm run build:win`
3. Copy files to this directory
4. Commit and push to GitHub
