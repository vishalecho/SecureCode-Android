![# SecureCode-Android](src/images/android.jps)

> ***Security Fundamental and Application Security Weaknesses (Mobile)***

### Security Fundamentals

> ***Application Security Concepts***

* Least Privileges
* Secure By Default
* Defence in Depth
* Robust Error Checking
* Trust No Input
* Open Design
* Fail Securely
* Reuse Of Existing Security Controls In A Framework Or Language
* Logging
* Data Protection

> ***Secure Development Lifecycle***

> ***Secure Architecture***

### Application Security Weaknesses
> ***Mobile***

- Sensitive Data Protection

	* Insecure Data Storage

		- Plaintext Storage Of Credentials
		- Storage On SDCard / External Storage
		- Storage Of Binary Cookies
		- Storage In Plist Or XML Files
		- Storage In Log Files
		- Storage In SQLite Database

- Insecure Development Practices

	* Insufficient Transport Layer Protection 
		- Weak Cipher Suites
		- Trusting Self-Signed Or Untrusted Certificates
		- Weak Certificate Validation
		- Communication Over Cleartext Protocol
		- Improper Certificate Pinning Configuration

	* Broken Cryptography 
		- Use Of Hardcoded Keys
		- use Of Encoding
		- Use Of Insecure/Deprecated Algorithms
		- use Of Short Encryption Keys
		- Insecure Storage Of Encryption Keys
		- Insecure Generation Of Encryption  Keys
		- Reuse Of Initialization Vector
		- Improper Use Of Cryptography Algorithm

	* Client Side Injection
		- SQL Injection
		- Local File Inclusion
		- JavaScript Injection
		- XML Injection
		- DOM-Based Cross-Site Scripting
		- Untrusted third party sites

	* Lack of Binary Protection 
		- No Code Obfuscation
		- No Protection From Debuggers
		- No Protection From Runtime Injection
		- No Protection From Piracy
		- Lack of Adequate Security Controls

	* Improper Platform Usage
		- Tapjacking
		- Webview Settings
		- Incorrect Activity Configuration
		- Insecure File/Directory Permissions
		- Insecure Use Of Pasteboard
		- Misuse Of URL Schemes
		- Misuse Of Intents
		- Misuse Of Broadcast Receivers
		- Misuse Of Keychain

	* Client Code Quality
		- Overflow Vulnerabilities
		- Format String Vulnerabilities
		- Improper Memory Management

	* Code Tampering 
		- Backups Enabled 
		- Tampering Detection

	* Reverse Engineering 
		- Code Information Leakage
		- Emulation Detection

	* Extraneous Functionality
		- Autofill Password
		- Leftover Comments
		- Debugging Features Enabled

- Data Handling

	* Unintended Data Leakage
	
		- Request/Response Caching 
		- Keyboard Caching 
		- Copy/Paste Buffer Caching(Pasteboard)
		- Application Backgrounding Screenshots
		- Logging Sensitive Information
		- HTML5 Data Storage
		- Browser Cookies Objects
		- Analytics Data Sent To 3rd Parties

- Authentication and Access Control

	* Insecure Authentication
		- Storing Credentials With 'Remember Me' Functionality
		- Use Of Spoofable Parameters For Authentication
		- Uses Of Weak Passwords
		- Client Side Authentication For Authenticating To Server
		- Hardcoded API Keys
		- Weak Lockout Mechanism
		- Misuse Of Fingerprint
		- Password Enumeration
		- Username Enumeration

	* Insecure Authorization
		- Broken Access Control
		- Insecure Direct Object Reference
		- Using Inputs From Untrusted Sources

	* Improper Session Handling
		- Improper Timeout Of Session ID
		- Weak Session Token Generation Algorithm
		- Client Side Session Token Generation
		- Same Session ID With Change In Privilege
		- Improper Flags In Cookie Headers
