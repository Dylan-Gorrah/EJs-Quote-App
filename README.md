# EJ Tours Document Generator

A professional document generation web application for EJ Tours and Projects that creates quotes and invoices with PDF export functionality.

## Overview

This is a single-page web application that allows EJ Tours to generate professional business documents including quotes and invoices. The application features a modern, responsive design with smooth animations and user-friendly interface.

## Features

- **Document Generation**: Create professional quotes and invoices
- **PDF Export**: Generate and download PDF documents with custom formatting
- **Company Management**: Configure and save company details and banking information
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Clean, professional interface with smooth animations
- **Data Persistence**: Company settings saved in browser localStorage

## Technology Stack

- **HTML5**: Semantic markup structure
- **Tailwind CSS**: Utility-first CSS framework for styling
- **Vanilla JavaScript**: Client-side logic and PDF generation
- **jsPDF Library**: PDF document generation
- **Google Fonts**: Typography (Sora and DM Sans fonts)
- **LocalStorage**: Browser-based data persistence

## How to Run

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for loading external CDN resources)

### Installation
1. Download or clone the project files
2. Ensure all files are in the same directory
3. Open `index.html` in your web browser

### Running Locally
```bash
# Option 1: Open directly in browser
Double-click on index.html

# Option 2: Use a local server (recommended for development)
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Then navigate to http://localhost:8000
```

## Usage

### 1. Home Screen
- Access three main functions: Quote, Invoice, and Settings
- Navigate using the interactive cards

### 2. Creating Quotes
- Click on the "Quote" card
- Fill in client name, service description, amount, and date
- Click "Generate Quote" to create and download PDF

### 3. Creating Invoices
- Click on the "Invoice" card
- Enter invoice number, client details, service information, amount, and date
- Click "Generate Invoice" to create and download PDF with banking details

### 4. Company Settings
- Click on the "Settings" card
- Update company name, address, and banking information
- Changes are automatically saved to browser storage

## Document Features

### PDF Layout
- Professional header with company branding
- Document type and numbering
- Client information section
- Itemized service description
- Total amount calculation
- Banking details (invoices only)
- Validity notice (quotes only)
- Minimal border design
- Developer credit footer

### Customization
- Company details configurable through settings
- Automatic date population
- Professional color scheme (Navy Blue and Orange accents)
- Watermark support for company logo

## File Structure

```
EJ's Doc App/
├── index.html          # Main application file (contains all code)
└── README.md          # This documentation file
```

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

## Security Notes

- All data is stored locally in browser localStorage
- No server-side processing or data transmission
- Company banking details are only stored locally
- PDF generation happens client-side

## Developer Information

- **Developer**: Gylan Gorrah
- **Company**: EJ Tours and Projects
- **Location**: Cape Town, Western Cape, South Africa
- **Application Type**: Single-page web application

## Support

For technical support or questions about the application, contact the developer.

## License

This application was developed specifically for EJ Tours and Projects.
