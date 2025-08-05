# Geldmaat ATM Accessibility Simulator

A Flask web application designed to enhance ATM accessibility for visually impaired users through an interactive simulator and educational platform.

## 📋 Project Overview

This project was developed by Team 'Pending...' (Diogo, Elnara, Roy, Wentao, and Gabriella) in collaboration with Geldmaat, the leading ATM corporation in the Netherlands. The application addresses accessibility challenges faced by visually impaired users when using ATMs and provides an educational platform to encourage cash usage while ensuring inclusive banking services.

## 🎯 Purpose

Based on research findings that revealed declining cash usage in the Netherlands (only 20% of POS payments in 2020), this project specifically focuses on:

- **Enhancing accessibility** for visually impaired users
- **Providing educational resources** about ATM usage
- **Simulating ATM experiences** to reduce anxiety and improve confidence
- **Promoting inclusive banking** through better user experience design

## ✨ Key Features

### 🔧 Accessibility Features
- **Multi-language Support**: Dutch, English, and Chinese translations
- **Color Mode Toggle**: Alternative color schemes for better contrast
- **Font Size Adjustment**: Customizable text size for better readability
- **Text-to-Speech**: Audio narration for screen content
- **Large Icons**: Enhanced visibility and easier navigation
- **Screen Reader Compatible**: Optimized for assistive technologies

### 🏧 ATM Simulator
- Interactive ATM simulation covering various transactions:
  - Cash withdrawal
  - Balance inquiry
  - Deposits
  - Receipt printing
- Step-by-step guidance through ATM processes
- Educational tool for first-time users

### 📱 Website Sections
- **Home**: Main landing page with accessibility options
- **Simulator**: Interactive ATM training environment
- **Locations**: ATM finder and location services
- **How to Use**: Educational content and tutorials
- **About Us**: Project information and team details
- **Contact**: Support and feedback channels

## 🏗️ Technical Architecture

### Backend
- **Framework**: Flask (Python)
- **Template Engine**: Jinja2
- **Static Files**: CSS, JavaScript, Images

### Frontend
- **Styling**: Bootstrap 5.2.3 + Custom CSS
- **JavaScript**: Vanilla JS for accessibility features
- **Responsive Design**: Mobile-first approach

### File Structure
```
Directory/
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── static/               # Static assets
│   ├── *.css            # Stylesheets for each page
│   ├── Js/              # JavaScript modules
│   └── images/          # Icons and graphics
└── templates/           # HTML templates
    ├── index.html       # Home page
    ├── Simulator.html   # Main simulator
    ├── Sim_*.html      # Simulator steps
    └── *.html          # Other pages
```

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone [repository-url]
   cd Directory
   ```

2. **Create virtual environment**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   python app.py
   ```

5. **Access the application**
   Open your browser and navigate to `http://localhost:5000`

## 📊 Research Foundation

This project is based on extensive research including:

### Theoretical Framework
- **Technology Acceptance Model (TAM)**: Understanding user adoption factors
- **Community Empowerment Theory**: Building user capacity and confidence
- **Behavioral Change Techniques**: Encouraging cash usage adoption

### User Research
- Focus groups with visually impaired individuals
- Website accessibility evaluations
- Stakeholder analysis including banks, government, and user groups
- Survey data on website usability and confidence metrics

### Key Findings
- 28% of Dutch citizens expect reduced cash usage in next 5 years
- 6% express concern about ATM accessibility
- Visually impaired users face significant barriers with current ATM interfaces
- Language barriers and poor contrast are major accessibility issues

## 🎨 Design Principles

### Accessibility-First Design
- **WCAG Guidelines**: Following Web Content Accessibility Guidelines
- **High Contrast**: Improved color schemes for visual clarity
- **Large Touch Targets**: Easier interaction for users with motor impairments
- **Clear Navigation**: Simplified information architecture
- **Alternative Text**: Comprehensive alt text for images and icons

### User Experience
- **Reduced Cognitive Load**: Simplified interfaces and clear instructions
- **Progressive Disclosure**: Step-by-step guidance through complex processes
- **Error Prevention**: Clear feedback and validation
- **Customization**: User-controlled accessibility settings

## 📈 Impact & Outcomes

### Measured Improvements
- Enhanced website permeability and understandability
- Increased user confidence in ATM usage
- Better accessibility scores across evaluation metrics
- Positive feedback from visually impaired focus group participants

### Behavioral Change Results
- Improved perceived accessibility of ATM services
- Increased willingness to use cash transactions
- Enhanced user self-efficacy with banking technology
- Greater confidence in independent ATM usage

## 🔮 Future Enhancements

- **Voice Navigation**: Complete voice-guided interface
- **Haptic Feedback**: Tactile responses for mobile devices
- **AI Assistance**: Intelligent help system
- **Advanced Personalization**: User profile-based customization
- **Real ATM Integration**: Connection with actual Geldmaat ATM network
- **Analytics Dashboard**: Usage tracking and improvement insights

## 🤝 Contributing

This project was developed as part of a research collaboration with Geldmaat. For contributions or improvements:

1. Fork the repository
2. Create a feature branch
3. Implement accessibility-focused improvements
4. Test with screen readers and accessibility tools
5. Submit a pull request with detailed accessibility impact notes

## 📄 License

This project is developed for educational and research purposes in collaboration with Geldmaat.

## 👥 Team

**Team 'Pending...'**
- Diogo Baptista
- Elnara
- Roy  
- Wentao
- Gabriella

**Partner Organization**
- Geldmaat (Netherlands ATM Network)

## 📞 Support

For questions about accessibility features or technical support, please use the Contact section of the application or refer to the research documentation in `Final Report - Geldmaat.pdf`.

---

*This project demonstrates how behavioral change theories and inclusive design can create more accessible financial services, contributing to a more equitable digital banking ecosystem.*
