# Kalyan Ram Portfolio

This is a portfolio website for showcasing the personal and professional achievements of **Sola Kalyan Ram**. It includes information about skills, education, projects, certificates, and hobbies.

## Features

- **Responsive Design**: Adapts to different screen sizes for improved user experience.
- **Sectional Navigation**: Users can navigate between sections like Summary, Skills, Education, Projects, Certificates, and Hobbies.
- **Interactive Certificate Modal**: Users can view certificate details in a modal popup.
- **Clean and Simple UI**: Focused design for better readability and presentation.

## File Structure

```plaintext
├── index.html       # Main HTML file for the portfolio
├── Profile.jpg      # Profile photo (update the path accordingly)
├── certificates/    # Directory containing certificate images
│   ├── ML.png       # Machine Learning certificate
│   ├── CCNA.png     # Cisco Certification
│   ├── BD.png       # Big Data Analytics
│   ├── AWS.jpg      # AWS Course certificate
│   └── RF.png       # Rebel Food Participation certificate
```

## How to Use

1. Clone or download this repository.
2. Ensure the following directory structure:
    - Place `index.html` in the root directory.
    - Place the profile image as `Profile.jpg` in the root directory.
    - Place certificate images inside a folder named `certificates`.
3. Open `index.html` in any modern web browser to view the portfolio.

## Customization

### Changing Profile Photo
- Replace `Profile.jpg` with your own profile photo in the root directory.
- Ensure the file path in the `<img>` tag of the `<header>` section matches the file location.

### Adding/Removing Certificates
- Add new certificate images in the `certificates` folder.
- Update the `<li>` elements in the `Certificates` section of the HTML file with the appropriate details:

```html
<li onclick="showCertificateDetails('Certificate Name', 'certificates/certificate_image.png')">Certificate Name</li>
```

### Modifying Colors and Styles
- Edit the `style` section in the `<head>` of the HTML file to change colors, fonts, or layout.


## License
This project is free to use and modify for personal purposes.

---

### Contact
For any questions or suggestions, feel free to reach out:
- **Email**: kalyanramsola@gmail.com
- **GitHub**: [Kalyanram2236](https://github.com/Kalyanram2236)
- **LinkedIn**: [Sola Kalyan Ram](https://linkedin.com/in/Sola%20Kalyan%20Ram/)
