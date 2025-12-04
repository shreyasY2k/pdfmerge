# PDF Merger

A client-side PDF merger tool that allows users to combine multiple PDF files into a single document. Built with vanilla JavaScript and hosted as a static site - no server required!

## Features

- 🔄 **Client-side processing** - No files are uploaded to any server
- 📱 **Responsive design** - Works on desktop and mobile devices
- 🎨 **Modern UI** - Clean, animated interface with drag-and-drop support
- ⚡ **Fast performance** - Uses PDF-lib for efficient PDF manipulation
- 🔒 **Privacy-focused** - All processing happens in your browser
- 📊 **File management** - Reorder, preview, and remove files before merging

## How to Use

1. **Upload PDFs**: Click "Choose Files" or drag and drop PDF files onto the upload area
2. **Reorder Files**: Use the up/down arrows to arrange files in your desired order
3. **Remove Files**: Click "Remove" to delete unwanted files from the list
4. **Merge**: Click "Merge PDFs" to combine all files into one document
5. **Download**: The merged PDF will automatically download to your device

## GitHub Pages Deployment

To host this on GitHub Pages:

1. **Create a new repository** on GitHub
2. **Upload the files** to your repository:
   - `index.html` (the main application file)
   - `README.md` (this file)

3. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your site**: Your PDF merger will be available at:
   `https://[your-username].github.io/[repository-name]`

## Technical Details

### Dependencies
- **PDF-lib**: JavaScript library for creating and modifying PDF documents
- **Google Fonts**: Clash Display and JetBrains Mono for typography

### Browser Compatibility
- Modern browsers with ES6+ support
- File API and ArrayBuffer support required
- Works on Chrome, Firefox, Safari, Edge (latest versions)

### File Size Limits
- Limited by browser memory (typically handles files up to several hundred MB)
- Performance may vary based on file size and device capabilities

## Security & Privacy

- **100% client-side**: No files are ever uploaded to external servers
- **Local processing**: All PDF manipulation happens in your browser
- **No data collection**: No analytics or tracking implemented
- **Open source**: Full source code is available for review

## Customization

The application uses CSS custom properties for easy theming:

```css
:root {
    --primary: #0066ff;      /* Main brand color */
    --secondary: #ff6b35;    /* Secondary accent */
    --accent: #00d4aa;       /* Highlight color */
    --dark: #0a0a0a;         /* Background */
    --gray: #1a1a1a;         /* Card backgrounds */
    /* ... more variables */
}
```

## File Structure

```
pdf-merger/
├── index.html          # Complete application (HTML, CSS, JS)
└── README.md          # Documentation
```

## Limitations

- **PDF format only**: Only works with valid PDF files
- **Browser memory**: Large files may cause performance issues
- **No OCR**: Cannot merge scanned documents that need text recognition
- **No password-protected PDFs**: Encrypted PDFs are not supported

## Contributing

Feel free to fork this project and submit pull requests for improvements:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you encounter any issues:

1. Check that your PDF files are valid and not corrupted
2. Try with smaller files if experiencing performance issues
3. Ensure your browser is up to date
4. Open an issue on GitHub with details about the problem

---

**Note**: This tool processes files entirely in your browser for maximum privacy and security. No files are transmitted over the internet during the merging process.
