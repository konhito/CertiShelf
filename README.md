<h3 align="center">
  <img src = "https://i.giphy.com/cFdHXXm5GhJsc.webp" width="200px" alt="gif" />
<br><br>
<b>CertiShelf</b></h3>

<div align="center" >

![NextJs](https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![GitHub repo size](https://img.shields.io/github/repo-size/konhito/CertiShelf)

  </div>

<div align="center" >
CertiShelf is a secure and easy-to-use platform designed to help individuals and organizations host, manage, and showcase their certificates online. With a user-friendly interface and robust security features, CertiShelf simplifies certificate management while ensuring authenticity and accessibility.
</div>

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Secure Storage**: Safely store certificates with end-to-end encryption.
- **Easy Management**: Organize and categorize certificates with a simple dashboard.
- **Showcase Profiles**: Create public or private profiles to display your achievements.
- **Verification System**: Ensure certificate authenticity with built-in validation tools.
- **Multi-User Support**: Ideal for individuals, educational institutions, and organizations.
- **Responsive Design**: Access CertiShelf seamlessly on desktop and mobile devices.

## Image

<div align="center" >
 <img src = "public/869ad615-7e99-45c6-9671-003b0b3e2533.jpg" width="400px" 
 
</div>

## Installation

To set up CertiShelf locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/konhito/CertiShelf.git
   cd certishelf
   ```

2. **Install dependencies**:
   Ensure you have [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) installed, then run:

   ```bash
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env` file in the root directory and add the following:

   ```
   PORT=3000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   ```

4. **Start the application**:
   ```bash
   npm start
   ```
   The app will be available at `http://localhost:3000`.

## Usage

1. **Sign Up**: Create an account to start managing your certificates.
2. **Upload Certificates**: Use the dashboard to upload and categorize your certificates.
3. **Share Profiles**: Generate shareable links to showcase your certificates publicly or privately.
4. **Verify Certificates**: Use the verification tool to confirm the authenticity of any certificate hosted on CertiShelf.

For detailed documentation, visit [docs/certishelf.md](docs/certishelf.md).

## Contributing

We welcome contributions to CertiShelf! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

Please read our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For support or inquiries, reach out to us at:

- Email: konhito02@gmail.com
- Follow us on [Twitter/X](https://x.com/codewithaddy) for updates.
