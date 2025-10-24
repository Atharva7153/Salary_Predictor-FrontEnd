# Salary Predictor

A modern, user-friendly web application that predicts salaries based on years of experience, age, and number of certifications. The application features a clean, responsive design and provides real-time salary predictions using a machine learning model.



## Features

- 📊 Real-time salary predictions
- 🎯 User-friendly interface
- 📱 Responsive design for all devices
- ✨ Modern animations and transitions
- 🚀 Fast and reliable predictions
- ⚡ Instant feedback and error handling

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- RESTful API Integration
- Responsive Design
- Custom Animations

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- Internet connection (for API calls)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/salary-predictor.git
```

2. Navigate to the project directory:
```bash
cd salary-predictor
```

3. Open `index.html` in your web browser or use a local development server.

## Usage

1. Enter your years of experience (can include decimals)
2. Input your age (between 18-100)
3. Specify the number of certifications you hold
4. Click the "Predict Salary" button
5. View your predicted salary result

## API Integration

The application connects to a backend service at:
```
https://salary-predictor-backend-0en4.onrender.com/predict
```

The API accepts POST requests with the following parameters:
- `experience`: Number of years of experience
- `age`: Age of the person
- `certifications`: Number of certifications held

## Project Structure

```
frontend/
│
├── index.html          # Main HTML file
├── style.css          # Stylesheet file
└── README.md          # Documentation
```

## Customization

You can customize the appearance by modifying the CSS variables in `style.css`:

```css
:root {
    --primary-color: #4a90e2;
    --hover-color: #357abd;
    --error-color: #e74c3c;
    --text-color: #333;
    --light-gray: #f5f6fa;
    --border-color: #dcdde1;
}
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.


## Acknowledgments

- Thanks to all contributors
- Inspired by modern web design practices
- Built with ❤️ for the developer community