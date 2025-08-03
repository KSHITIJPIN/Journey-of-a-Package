The Interactive Journey of a Packet: An OSI Model Story
An interactive, single-page web application that tells the story of a data packet's journey through the 7 layers of the OSI model. Designed to be a fun, engaging, and educational tool for students and anyone curious about networking fundamentals.
✨ Features
This project transforms the theoretical OSI model into a tangible, explorable experience.
* Interactive Storyline: A vertical scrolling journey that follows "Pip the Packet" from the Application Layer all the way down to the Physical Layer and back.
* Layer-by-Layer Visualizations: Each of the 7 layers features a unique interactive element to demonstrate its core function:
   * Layer 6 (Presentation): Toggle message encryption/decryption.
   * Layer 5 (Session): Visually open and close a communication session.
   * Layer 4 (Transport): Break a large message into smaller, numbered packets.
   * Layer 3 (Network): Add a simulated IP header to a packet.
   * Layer 2 (Data Link): Add a simulated MAC header to a packet.
   * Layer 1 (Physical): Convert digital data into an analog signal using a dynamic chart.
* 🤖 AI-Powered Explanations: Integrated with the Gemini API to provide on-demand, simplified explanations for each layer ("Explain Like I'm 5").
* 🤖 AI Analogy Generator: A creative tool that uses the Gemini API to generate a full 7-layer OSI analogy based on any topic the user provides.
* 📚 Practical Learning Resources: A curated list of essential tools and websites (like Wireshark, Cisco Packet Tracer, etc.) to help students gain hands-on networking experience.
* Responsive Design: A clean and modern UI that works seamlessly on desktops, tablets, and mobile devices.
* Smooth Navigation: A sticky side-navigation bar tracks scroll progress and allows for quick navigation between sections.
🛠️ Technologies Used
This project is built with modern, lightweight web technologies and is contained within a single HTML file for simplicity and portability.
* HTML5
* Tailwind CSS: For all styling and layout.
* JavaScript (Vanilla JS): For all core application logic and interactivity.
* Chart.js: For the dynamic data visualization on the Physical Layer.
* Google Gemini API: To power the AI explanation and analogy generation features.
🚀 Getting Started
Running this project locally is simple.
Prerequisites
All you need is a modern web browser.
Installation & Setup
1. Clone the repository:
git clone https://github.com/KSHITIJPIN/Journey-of-a-Package

2. Navigate to the project directory:
cd Journey-of-a-Package

3. Open the HTML file:
Simply open the index.html file (or the name you've given it) directly in your web browser (e.g., Chrome, Firefox, Edge).
Gemini API Key Setup
The AI-powered features require a Google Gemini API key. The application includes a graceful fallback with mock data if a key is not provided, but for the full experience, you'll need to add one.
   1. Get an API key: Visit Google AI Studio to create your free API key.
   2. Add the key to the code: Open the HTML file and find the <script> tag at the bottom. Inside the script, locate the following line:
const apiKey = ""; 

   3. Paste your key: Place your API key inside the double quotes:
const apiKey = "YOUR_API_KEY_HERE"; 

   4. Save the file and refresh your browser. The AI features should now be fully functional.
🤝 Contributing
Contributions are welcome! If you have ideas for new features, improvements, or bug fixes, please feel free to:
      1. Fork the repository.
      2. Create a new branch (git checkout -b feature/AmazingFeature).
      3. Commit your changes (git commit -m 'Add some AmazingFeature').
      4. Push to the branch (git push origin feature/AmazingFeature).
      5. Open a Pull Request.