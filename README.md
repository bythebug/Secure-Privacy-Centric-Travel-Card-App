# Secure Privacy-Centric Travel Card App

This project is a transit payment app focused on user privacy. It allows contactless payments for public transportation while keeping your personal information secure.

## Features

- **Secure Payments:** Uses RSA encryption to protect your payment details during contactless transactions.
- **User Authentication:** Integrates OAuth for safe and simple user login.
- **Efficient Backend:** The server is built with Flask and uses asynchronous calls and caching to respond quickly.
- **Cross-Platform Mobile App:** Developed with React Native, the app works on both iOS and Android devices.
- **Cloud Integration:** Utilizes Firebase for reliable data storage and management.
- **Privacy Compliance:** Fully adheres to GDPR and PIPEDA regulations to ensure user data protection.

## Technologies Used

- **Frontend:** React Native
- **Backend:** Flask
- **Cloud Services:** Firebase
- **Security:** RSA Encryption, OAuth

## Getting Started

To set up the project on your local machine:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/bythebug/Secure-Privacy-Centric-Travel-Card-App.git
   ```


2. **Backend Setup:**

   - Navigate to the `backend` folder:

     ```bash
     cd Secure-Privacy-Centric-Travel-Card-App/backend
     ```

   - Create a virtual environment:

     ```bash
     python3 -m venv venv
     ```

   - Activate the virtual environment:

     - On macOS/Linux:

       ```bash
       source venv/bin/activate
       ```

     - On Windows:

       ```bash
       venv\Scripts\activate
       ```

   - Install the required packages:

     ```bash
     pip install -r requirements.txt
     ```

   - Start the Flask server:

     ```bash
     flask run
     ```

3. **Frontend Setup:**

   - Navigate to the `frontend` folder:

     ```bash
     cd ../frontend
     ```

   - Install the dependencies:

     ```bash
     npm install
     ```

   - Run the React Native app:

     ```bash
     npm start
     ```

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your changes to your fork.
5. Submit a pull request detailing your changes.

## License

This project is licensed under the [MIT License](LICENSE).

---

*Note: This README is based on the project description available at the time. For the latest information and updates, please refer to the project's [GitHub repository](https://github.com/bythebug/Secure-Privacy-Centric-Travel-Card-App).* 
