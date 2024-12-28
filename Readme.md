# Medical Diagnosis Assistant 🏥

## Project Overview

Welcome to the Medical Diagnosis Assistant, an advanced healthcare application that combines machine learning with medical knowledge to provide preliminary health assessments. This project was developed to assist users in understanding potential health conditions based on their symptoms, while providing comprehensive health recommendations.

Live Demo: [Medical Diagnosis Assistant](https://medical-diagnosis-assistant.streamlit.app/)

![Medical Diagnosis Interface](project_screenshot.png)

## Key Features and Capabilities

### Core Functionality
- **Symptom Analysis**: Process over 130 different symptoms for accurate diagnosis
- **Disease Prediction**: Identify potential conditions from a database of 40+ diseases
- **Real-time Processing**: Instant analysis and results using trained ML models
- **Comprehensive Health Insights**: Detailed information about identified conditions

### Health Recommendations
1. **Medical Information**
   - Detailed disease descriptions
   - Common symptoms and progression
   - Condition severity indicators

2. **Treatment Guidance**
   - Recommended precautions
   - Suggested medications
   - Professional consultation advice

3. **Lifestyle Recommendations**
   - Customized exercise plans
   - Dietary guidelines
   - Preventive measures

4. **User Experience**
   - Intuitive symptom selection
   - Clear result presentation
   - Mobile-responsive design
   - Accessible health information

## Technical Implementation

### Machine Learning Model
- **Algorithm**: Support Vector Machine (SVM) with linear kernel
- **Training Data**: 4,920 records with 132 symptoms and 41 diseases
- **Accuracy**: 95%+ on test dataset
- **Feature Engineering**: One-hot encoding for symptom representation

### Technology Stack
```
Backend:
- Python 3.12
- scikit-learn 1.3.2
- NumPy 1.26.2
- Pandas 2.1.3

Frontend:
- Streamlit 1.29.0
- Plotly 5.18.0
- HTML/CSS

Data Storage:
- CSV databases
- Pickle files for model persistence
```

## Detailed Setup Guide

### Prerequisites
1. Python 3.12 or higher
2. Git
3. 4GB RAM minimum
4. Internet connection for initial setup

### Installation Steps

1. **Clone the Repository**
```bash
git clone https://github.com/sundaepromix/Medical-Diagnosis-Assistamt.git
cd Medical-Diagnosis-Assistamt
```

2. **Set Up Python Environment**
```bash
# Create virtual environment
python -m venv venv

# Activate environment
# For Windows
venv\Scripts\activate
# For Unix/MacOS
source venv/bin/activate
```

3. **Install Dependencies**
```bash
pip install -r requirements.txt
```

4. **Verify File Structure**
```
Medical-Diagnosis-Assistant/
├── app.py                 # Main application file
├── requirements.txt       # Project dependencies
├── README.md             # Documentation
├── Models/
│   └── svc.pkl           # Trained ML model
└── Dataset/
    ├── symtoms_df.csv    # Symptom descriptions
    ├── precautions_df.csv # Precautionary measures
    ├── workout_df.csv     # Exercise recommendations
    ├── description.csv    # Disease descriptions
    ├── medications.csv    # Medication information
    └── diets.csv         # Dietary recommendations
```

5. **Launch Application**
```bash
streamlit run app.py
```

### Configuration Options
- Port configuration in app.py
- Model parameters in Models/
- Dataset modifications in Dataset/

## Using the Application

### Step-by-Step Guide
1. **Symptom Selection**
   - Access the sidebar menu
   - Choose relevant symptoms from the dropdown
   - Select multiple symptoms as needed

2. **Getting Diagnosis**
   - Click "Get Diagnosis" button
   - Wait for analysis completion
   - Review comprehensive results

3. **Interpreting Results**
   - Check primary diagnosis
   - Review disease description
   - Note recommended precautions
   - Consider suggested medications
   - Follow exercise recommendations
   - Implement dietary advice

### Best Practices
- Select specific, noticeable symptoms
- Include all relevant symptoms
- Review all recommendations carefully
- Follow up with healthcare providers

## Troubleshooting

Common Issues and Solutions:
1. **Model Loading Error**
   - Verify Models/svc.pkl exists
   - Check file permissions
   - Ensure correct Python version

2. **Dataset Loading Issues**
   - Confirm Dataset/ folder structure
   - Verify CSV file formats
   - Check file encoding (UTF-8)

3. **Memory Problems**
   - Close unnecessary applications
   - Verify system requirements
   - Check available RAM

## Future Development

### Planned Features
- Multi-language support
- Symptom severity scaling
- Interactive medical visualizations
- Patient history tracking
- Integration with health devices

### Areas for Improvement
- Enhanced model accuracy
- Additional diseases coverage
- More detailed treatment plans
- UI/UX enhancements
- Mobile app development

## Contributing

I welcome contributions! Here's how you can help:

1. **Code Contributions**
   - Fork the repository
   - Create feature branch
   - Submit pull request
   - Follow coding standards

2. **Documentation**
   - Improve README
   - Add code comments
   - Create user guides
   - Write technical docs

3. **Testing**
   - Report bugs
   - Suggest improvements
   - Test new features
   - Provide feedback

## Medical Disclaimer

⚠️ **Important Notice**: This application is designed for educational and informational purposes only. It does not provide medical advice, professional diagnosis, or treatment recommendations. Always consult qualified healthcare professionals for medical concerns.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact and Support

- **Project Maintainer**: [Your Name]
- **Email**: [Your Email]
- **GitHub**: [sundaepromix](https://github.com/sundaepromix)
- **Issues**: [Create an issue](https://github.com/sundaepromix/Medical-Diagnosis-Assistamt/issues)

---

Made with dedication to improving healthcare accessibility 🌟
