# EJ Tours Document Generator

A professional document generation web application for EJ Tours and Projects that creates quotes and invoices with PDF export functionality.

## Overview

This is a single-page web application that allows EJ Tours to generate professional business documents including quotes and invoices. The application features a modern, responsive design with smooth animations and user-friendly interface.

## Features

- **Document Generation**: Create professional quotes and invoices
- **Contact Information**: Capture company and customer contact details (email and phone)
- **PDF Export**: Generate and download PDF documents with custom formatting
- **Glassmorphic Confirmation**: Beautiful frosted-glass success modal with document summary
- **Premium UI**: Enhanced button visibility and professional glassmorphic design
- **Company Management**: Configure and save company details, contact info, and banking information
- **Customer Details**: Record customer phone numbers for quotes and invoices
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern Animations**: Smooth transitions and premium feel throughout
- **Data Persistence**: Company settings saved in browser localStorage

## New in This Version

### UI/UX Enhancements
- **Glassmorphic Success Modal**: Replaced basic alerts with beautiful frosted-glass modals
- **Document Summary Display**: Shows complete document details after generation
- **Enhanced Button Visibility**: Improved borders and shadows for better clarity
- **Premium Animations**: Smooth fade-in and slide-up effects
- **Backdrop Blur**: Professional background blur when modals are active

### Contact Information Enhancement
- **Company Email**: ejtoursandprojects@gmail.com displayed in PDF headers
- **Company Phone**: +27 74 931 0308 displayed in PDF headers
- **Customer Phone**: Capture and display customer phone numbers in "Bill To" section
- **Settings Page**: Add/edit company email and phone in settings

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
- Fill in:
  - Client name
  - Client phone number
  - Service description
  - Amount
  - Date (auto-filled with today's date)
- Click "Generate Quote" to create and download PDF

### 3. Creating Invoices
- Click on the "Invoice" card
- Enter:
  - Invoice number
  - Client name
  - Client phone number
  - Service information
  - Amount
  - Date (auto-filled with today's date)
- Click "Generate Invoice" to create and download PDF with banking details

### 4. Company Settings
- Click on the "Settings" card
- Update:
  - Company name
  - Address details
  - **Email address** (displays in PDF header)
  - **Phone number** (displays in PDF header)
  - Banking information
- Changes are automatically saved to browser storage

## Document Features

### PDF Layout
- **Professional header** with company branding
- **Company contact information** (email and phone in header)
- Document type and numbering
- **Client information section** with name and phone number
- Itemized service description
- Total amount calculation
- Banking details (invoices only)
- Validity notice (quotes only)
- Minimal border design
- Developer credit footer

### Contact Information Display
- **In Header**: Company email and phone number
- **In Bill To Section**: Customer name and phone number
- **Professional formatting**: Clean, easy-to-read layout

### Success Modal Features
- **Glassmorphic Design**: Frosted glass effect with backdrop blur
- **Document Summary**: Complete breakdown of generated document details
- **Premium Animations**: Smooth fade-in and slide-up transitions
- **Click-to-Close**: Close modal by clicking outside or using the Done button
- **Mobile Responsive**: Adapts beautifully to all screen sizes

### Enhanced Button Design
- **Improved Borders**: 2px borders on primary and secondary buttons
- **Subtle Shadows**: Enhanced depth with professional shadow effects
- **Better Contrast**: Input fields with 1.5px borders for clarity
- **Hover States**: Interactive feedback on all clickable elements

### Customization
- Company details configurable through settings
- Contact information editable in settings
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
- Company banking details and contact info are only stored locally
- PDF generation happens client-side
- Customer information is not saved after PDF generation

## Developer Information

- **Developer**: Gylan Gorrah
- **Company**: EJ Tours and Projects
- **Location**: Cape Town, Western Cape, South Africa
- **Application Type**: Single-page web application
- **Contact**: ejtoursandprojects@gmail.com

## What's New - Premium UI & Contact Enhancement

### UI/UX Improvements:
1. **Glassmorphic Success Modal**:
   - Beautiful frosted-glass modal with backdrop blur
   - Replaces basic browser alerts
   - Shows complete document summary
   - Smooth animations (fade-in, slide-up)
   - Click outside to close

2. **Enhanced Visual Hierarchy**:
   - Primary buttons: 2px white borders on gradient background
   - Secondary buttons: 2px borders for better definition
   - Input fields: 1.5px borders for improved visibility
   - Card borders: Subtle borders that darken on hover

3. **Premium Animations**:
   - Modal fade-in with backdrop blur
   - Content slide-up with spring easing
   - Button hover effects with elevation changes
   - Smooth transitions throughout

### Changes Made:
1. **Company Contact Fields**:
   - Added email field to company settings
   - Added phone field to company settings
   - Pre-populated with: ejtoursandprojects@gmail.com and +27 74 931 0308

2. **Customer Contact Fields**:
   - Added phone number field to Quote form
   - Added phone number field to Invoice form
   - Required field for all documents

3. **PDF Display**:
   - Company email and phone displayed in header (lines 39-44)
   - Customer phone displayed in "Bill To" section (line 73)
   - Professional formatting maintained

4. **Data Flow**:
   - Company contact info saved to localStorage
   - Customer phone captured with each document
   - All contact info properly displayed in generated PDFs

5. **Success Modal System**:
   - Custom `showSuccessModal()` function for document generation
   - Custom `showSettingsSuccessModal()` for settings confirmation
   - `closeModal()` with animation fade-out
   - Document summary displays: Invoice #, Client, Phone, Amount, Date
   - Glassmorphic styling: rgba backgrounds, backdrop-filter blur
   - Premium feel: subtle shadows, smooth corners, elegant typography

6. **Button Enhancements**:
   - All Cancel buttons now use `btn-secondary` class with borders
   - Primary buttons have white border overlay for depth
   - Improved hover states with elevation changes
   - Better active states for tactile feedback

## Support

For technical support or questions about the application, contact: ejtoursandprojects@gmail.com

## License

This application was developed specifically for EJ Tours and Projects.
