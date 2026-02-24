# VeggieLoh Website

Welcome to the VeggieLoh website! This project is a web application designed to provide users with fresh vegetable delivery services. Below you will find information on how to set up and run the project, as well as an overview of its structure.

## Project Structure

```
veggieloh-website
├── index.html               # Main entry point of the website
├── privacypolicy.html       # Privacy policy page
├── contact.html             # Contact information and form
├── termscondition.html      # Terms and conditions page
├── css
│   └── style.css            # Styles for the website
├── js
│   └── main.js              # JavaScript for interactivity
├── lib
│   ├── lightbox             # Lightbox library for image/video display
│   └── owlcarousel          # Owl Carousel library for sliders
├── img                      # Directory for images
├── staticwebapp.config.json  # Configuration for Azure Static Web Apps
├── package.json             # npm configuration file
└── README.md                # Project documentation
```

## Getting Started

To get started with the VeggieLoh website, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd veggieloh-website
   ```

2. **Install Dependencies**
   If you have Node.js installed, you can install the necessary dependencies using npm:
   ```bash
   npm install
   ```

3. **Run the Application**
   You can run the application locally using a simple HTTP server. If you have Python installed, you can use:
   ```bash
   python -m http.server
   ```
   Then, open your browser and navigate to `http://localhost:8000`.

## Deployment

To deploy the VeggieLoh website to Azure Static Web Apps, follow these steps:

1. **Create a Static Web App in Azure**
   - Go to the Azure portal and create a new Static Web App.
   - Link your GitHub repository or upload your project files.

2. **Configure the Deployment**
   - Ensure that the `staticwebapp.config.json` file is correctly set up for routing and authentication.

3. **Deploy**
   - Push your changes to the main branch of your repository, and Azure will automatically build and deploy your application.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any inquiries or feedback, please reach out to us at:
- Email: support@veggieloh.com
- Phone: +91 965 087 4535

Thank you for using VeggieLoh! Enjoy fresh produce delivered to your doorstep!