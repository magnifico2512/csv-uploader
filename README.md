# CSV Upload Manager for Google Drive

A simple, powerful tool to upload CSV files to multiple Google Drive folders at once.

## ✨ Features

- 📁 **Multiple Folder Support** - Add unlimited folders
- 🔄 **Recursive Subfolder Expansion** - Expand folders to any depth
- 🎯 **Drag-and-Drop to Specific Folders** - Drop files directly on any folder
- ⭐ **Star Your Favorites** - Quick access to frequently used folders
- 📊 **Batch Upload** - Upload multiple files at once
- 🔒 **Secure** - Runs entirely in your browser, no data sent to servers
- 💾 **Remembers Your Folders** - Optional "Remember Me" keeps folders between sessions

## 🚀 How to Use

1. **Sign in with Google** - Grant access to your Google Drive
2. **Add Folders** - Click "Add Folder" to select upload destinations
3. **Expand Subfolders** - Click ▶ to see subfolders (any level deep)
4. **Upload Files** - Drag CSV files onto any folder or to the drop area
5. **Done!** - Files upload directly to your selected folders

## 🎯 Two Ways to Upload

### Method 1: Drag Directly to Folder
- Drag CSV files from your computer
- Hover over any folder (turns green)
- Drop! ✅

### Method 2: Select Then Drop
- Click a folder to select it (turns blue)
- Drag files to the drop area at the bottom
- Drop! ✅

## 🔐 Privacy & Security

- **100% Client-Side** - All code runs in your browser
- **No Backend Server** - Your data never leaves your computer
- **Open Source** - View the code yourself
- **Google OAuth** - Secure authentication via Google
- **You Control Access** - Revoke anytime at [Google Account Permissions](https://myaccount.google.com/permissions)

## 🛠️ Technical Details

- Pure HTML/CSS/JavaScript - no dependencies
- Uses Google Drive API v3
- Requires Google OAuth 2.0 with `drive` scope
- Works in all modern browsers

## 📝 Permissions Required

The app requests **full Google Drive access** (`drive` scope) to:
- List folders and subfolders you select
- Upload CSV files to those folders

**What it does NOT do:**
- Access files you don't explicitly select
- Modify or delete existing files
- Share your data with anyone
- Run when you're not using it

## 🐛 Troubleshooting

### "Access blocked: Authorization Error"
- This means Google OAuth isn't working
- Make sure you're accessing via HTTPS (GitHub Pages URL)
- Don't try to run the HTML file locally (file://)

### "This folder has no subfolders"
- Make sure you've granted the `drive` permission (not just `drive.file`)
- Sign out and sign back in to refresh permissions

### Folders not loading
- Check your internet connection
- Check browser console (F12) for errors
- Try refreshing the page

## 💡 Tips

- **Star frequently used folders** for quick access
- **Use "Show Starred"** to see only your favorites
- **Expand deeply nested folders** - unlimited levels supported
- **Upload multiple files at once** - no limit!

## 📄 License

Free to use and modify. No warranty provided.

## 🙏 Credits

Created to simplify bulk CSV uploads to Google Drive folders.

---

**Enjoy your streamlined CSV uploads!** 🎉
