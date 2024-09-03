# Email Sending Project

This project is a simple web application for sending emails, built using Java EE and deployed on GlassFish 4. It serves as a learning exercise to understand how to integrate email functionality into a web application.

## Features

- **Send Emails**: Users can send emails by providing the recipient's email address, subject, and message.
- **Input Validation**: Basic validation to ensure that the required fields are filled before sending an email.

## Technologies Used

- **Java EE**: Used for the backend to handle email sending.
- **GlassFish 4**: The application is deployed on the GlassFish 4 server.
- **JDK 8**: The project is built and runs on Java Development Kit 8.

## Getting Started

### Prerequisites

- **Java Development Kit (JDK) 8**
- **GlassFish 4** (Java EE server)
- **Git** (for version control)
- **SMTP Server**: An SMTP server (e.g., Gmail SMTP) for sending emails.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DisuraAberathna/Java-EE7_Email-Sending.git
   ```
   
2. **Navigate to the project directory:**
   ```bash
   cd Java-EE7_Email-Sending
   ```

3. **Configure SMTP Settings:**
   - Update the SMTP server settings in the project's configuration file to match your SMTP server credentials (e.g., `smtp.gmail.com` for Gmail).

4. **Deploy the project to GlassFish 4:**
   - Copy the project directory to the GlassFish `domains/domain1/applications` folder.
   - Alternatively, you can deploy it via the GlassFish admin console by packaging the project as a WAR file.

5. **Run the server:**
   - Start GlassFish 4 and access the application in your browser.

### Usage

- **Sending Emails:**
  - Go to the "Send Email" page.
  - Enter the recipient's email address, subject, and message.
  - Click "Send" to send the email.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Java EE documentation and community
- SMTP server providers (e.g., Gmail) for email services
