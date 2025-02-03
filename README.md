# Zymark Bookmark Dashboard

A modern, feature-rich bookmark management system built with vanilla JavaScript. This dashboard provides a clean, customizable interface for organizing and accessing your bookmarks efficiently.

![Zymark Bookmark Dashboard (Offline)](https://github.com/user-attachments/assets/f9c2ee5e-73a0-40a3-bb28-d324c8340d02)

## Features

### Core Functionality
- **Section Management**: Create, edit, and delete custom sections to organize bookmarks
- **Bookmark Management**: Add, edit, and delete bookmarks with customizable icons and colors
- **Notes System**: Create resizable sticky notes within sections
- **Search Integration**: Quick web search through multiple search engines (Google, Yahoo, DuckDuckGo)
- **Drag & Drop**: Intuitive drag-and-drop interface for organizing bookmarks and notes

### Customization
- **Custom Icons**: Upload custom icons for bookmarks
- **Color Themes**: Customize bookmark colors and backgrounds
- **Background Images**: Set custom background images for the dashboard
- **Layout Options**: Adjustable grid layout with customizable columns per row
- **Clock Display**: Built-in digital clock with 12/24 hour format options

### Data Management
- **Click Tracking**: Track bookmark usage with click counters
- **Sorting Options**: Multiple sorting methods for bookmarks:
  - Custom order (drag & drop)
  - Alphabetical
  - Date created
  - Most clicked
- **Import/Export**: Import bookmarks from HTML files and export/backup your dashboard data
- **Local Storage**: All data is stored locally in the browser

### User Interface
- **Clean Design**: Modern, minimalist interface with smooth animations
- **Context Menus**: Right-click menus for quick actions
- **Responsive Layout**: Adapts to different screen sizes
- **Visual Feedback**: Hover effects and transitions for better user experience

## Installation

1. Download HTML File from this repository.

2. Open `ZyMark Bookmark Dashboard.html` in your web browser.

No additional setup or dependencies required - the dashboard runs entirely in the browser.

## Usage

### Adding Bookmarks
1. Click the "Add Bookmark" button in the toolbar
2. Enter the bookmark title and URL
3. (Optional) Add a description and custom icon
4. Select a section for the bookmark
5. Click "Save"

### Creating Sections
1. Click "Add Section" in the toolbar
2. Enter a section name
3. Click "Create Section"

### Managing Notes
1. Click "Add Note" in the toolbar
2. Enter title and content
3. Select note size (1x1, 1x2, 2x1, or 2x2)
4. Choose a section
5. Click "Save"

### Importing/Exporting
- Use "Import Bookmarks" to import HTML bookmark files
- Use "Backup Bookmarks" to export your dashboard data
- Use "Clear All" to reset the dashboard (warning: this deletes all data)

## Browser Support

The dashboard is compatible with modern web browsers:
- Chrome
- Firefox (Tested On)
- Safari
- Edge

## Local Storage

All dashboard data is stored in your browser's local storage. To prevent data loss:
- Regularly use the backup feature
- Don't clear browser data without backing up first
- Import/export when switching browsers

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

The Unlicense

## Acknowledgments

- Icons provided by [None at this time]
- Inspired by Monknow Bookmark Dashboard (which saves all your bookmarks online on a server in China)
- Built with vanilla JavaScript and CSS

## Roadmap

Future features under consideration:
- Dark/light theme toggle
- Browser extension integration for saving bookmarks in one click
- Allow search of your bookmarks in the search bar
- Add drag-and-drop section reordering
- Display peak usage times and days
- Scheduled automatic backups, Porbably will have to nag user every minute after 1 day since there last backup until the program is turned into a server or browser extention.
