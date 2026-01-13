# FitZone Gym Management Website

A modern, responsive gym management website built with Flask, HTML, and CSS. This website showcases a professional gym's services, membership plans, and information.

## Features

- **Home Page**: Welcome message with gym highlights and key features
- **About Us Page**: Detailed information about the gym's mission, team, and facilities
- **Membership Page**: Comprehensive membership plans and additional services
- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Modern UI**: Clean, professional design with smooth animations and transitions

## Project Structure

```
gym-management-website/
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── README.md             # Project documentation
├── templates/            # HTML templates
│   ├── home.html        # Home page template
│   ├── about.html       # About Us page template
│   └── membership.html  # Membership page template
└── static/              # Static files
    └── css/
        └── style.css    # Main stylesheet
```

## Installation & Setup

1. **Clone or download the project**
   ```bash
   cd gym-management-website
   ```

2. **Create a virtual environment (recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   python app.py
   ```

5. **Open your browser**
   Navigate to `http://127.0.0.1:5000` to view the website

## Pages Overview

### Home Page (`/`)
- Hero section with compelling call-to-action
- Gym highlights showcasing key features
- Statistics section with impressive numbers
- Call-to-action sections for membership signup

### About Us Page (`/about`)
- Mission, vision, and values
- Company story and history
- Meet the team section with trainer profiles
- Facilities overview
- Awards and recognition

### Membership Page (`/membership`)
- Three-tier membership plans (Basic, Premium, Elite)
- Additional services and pricing
- Group fitness class schedule
- Membership benefits overview
- Contact information and location

## Technologies Used

- **Backend**: Flask (Python web framework)
- **Frontend**: HTML5, CSS3
- **Styling**: Custom CSS with modern design principles
- **Icons**: Emoji icons for visual appeal
- **Layout**: CSS Grid and Flexbox for responsive design

## Customization

### Changing Colors
The main color scheme can be modified in `static/css/style.css`:
- Primary color: `#e74c3c` (red)
- Secondary color: `#2c3e50` (dark blue)
- Accent colors: Various complementary colors

### Adding New Pages
1. Create a new HTML template in the `templates/` folder
2. Add a new route in `app.py`
3. Update navigation links in all templates

### Modifying Content
- Update text content directly in the HTML templates
- Modify membership plans and pricing in `membership.html`
- Change team member information in `about.html`

## Browser Support

This website is compatible with all modern browsers including:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## License

This project is open source and available under the MIT License.

## Contact

For questions or support, please contact the development team.