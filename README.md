<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EncryptSafe Local - Password Manager</title>
</head>

<body>
    <h1>EncryptSafe Local - Password Manager</h1>
    <p><strong>EncryptSafe Local</strong> is a secure, local password manager with encryption and two-factor authentication using Google Authenticator. Built with <code>Python</code> and <code>Tkinter</code>, it provides a user-friendly GUI for managing encrypted passwords.</p>

    <h2>Features</h2>
    <ul>
        <li>Save and manage encrypted passwords locally.</li>
        <li>Supports AES encryption for securing passwords.</li>
        <li>Google Authenticator-based two-factor authentication (TOTP).</li>
        <li>Full-screen mode with a clean and minimalistic UI.</li>
        <li>Database management using SQLite.</li>
    </ul>

    <h2>Setup Instructions</h2>
    <h3>Prerequisites</h3>
    <p>Ensure you have Python installed (version 3.8 or higher).</p>

    <h3>Installation</h3>
    <p>Follow these steps to install and run the project:</p>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone https://github.com/Navsajan/Encryptsafe_local.git</code></pre>

        <li>Navigate to the project directory:</li>
        <pre><code>cd encryptsafe-local</code></pre>

        <li>Install the required Python packages:</li>
        <pre><code>pip install -r requirements.txt</code></pre>
    </ol>

    <h3>Required Libraries</h3>
    <p>Add the following libraries to your <code>requirements.txt</code> file:</p>
    <pre><code>
tkinter
Pillow
pyotp
qrcode
sqlite3
</code></pre>

    <h2>How to Run</h2>
    <pre><code>python main.py</code></pre>
    <p>Replace <code>main.py</code> with your main script filename.</p>

    <h2>Usage</h2>
    <ol>
        <li>Launch the application.</li>
        <li>Log in or create a new user account.</li>
        <li>Save passwords by entering the app name, password, and encryption key.</li>
        <li>View saved passwords after verifying with Google Authenticator.</li>
    </ol>

    <h2>Security</h2>
    <ul>
        <li>Passwords are encrypted using AES before storage.</li>
        <li>TOTP verification adds an extra layer of security.</li>
    </ul>

    <h2>Contributing</h2>
    <p>Contributions are welcome! Please fork the repository and submit a pull request with your changes.</p>

    <h2>License</h2>
    <p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

</body>

</html>
