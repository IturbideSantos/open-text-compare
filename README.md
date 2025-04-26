# Open Text Compare

A simple, beautiful web-based tool to compare text files by line or word, with highlighting, diff navigation, and export functionalities.
This web application processes all data locally in your browser. No text is uploaded or stored on any server, making it more secure and private by design.

## Why was it built?
This app was born out of a need for a private, lightweight, and easy-to-use alternative to server-based diff tools. Many existing solutions require file uploads or online accounts. This one works entirely inside your browser.
No installation. No sign-up. No data leaves your device.

## Features

- Compare by line
- Highlight added/removed/modified lines
- Highlight modified words within a line
- Export results (CSV, TXT, Email, Copy)
- Navigate between changes
- Language support
- Open source and user-friendly
- All functionalities run within the browser

## Future Features

- ignore trailing white spaces
- ignore space/tab differences
- contacts (X, instagram, email)
- create tests
- improve colors and create a separate file to hold the different color themes
- fix the languages: transpose all texts within the file to the translations.js
- make texts of README, ABOUT and PRIVACY reusable. Maybe a tool to generate about and privacy pages automatically from the readme?
	- implement a markdown parser to hold the about and privacy pages
- accept files
- create a button to show results in two columns
- fix showing spaces and tabs
- Add "How to use" page

## License

This project is licensed under the **GNU GPLv3**.  
See the [LICENSE](./LICENSE) file for details.

## Privacy and security
This application is designed with privacy in mind.

- All data is processed locally: Your text never leaves your browser. There are no servers involved, and nothing is uploaded or stored externally.
- No tracking, no analytics, no cookies: The app does not collect any personal data, usage logs, or use third-party trackers.
- Fully client-side: Everything runs entirely in your browser using HTML, CSS, and JavaScript. There are no backend services or databases.
- Because of this architecture, the application is inherently more secure against data breaches. You are in full control of your data at all times.

**⚠️ Note: Like all browser-based tools, the security of this application depends on the security of your device and browser. Always ensure your browser is up to date and you are visiting the official page.**

You can read more in our Privacy & Security section.

## GDPR-Friendly

This app does not collect, store, or transmit any personal data. All content is handled locally in your browser, ensuring full user privacy in accordance with GDPR principles.

## Open Source Transparency

This project is fully open source and licensed under the GNU GPLv3.  
Anyone is welcome to inspect, contribute to, or modify the code.

You can trust exactly what this app does — because you can see it for yourself.

## Support the Project 💚

If this project helps you, consider donating:

- [☕ Donate with PayPal](https://www.paypal.com/donate?hosted_button_id=W7QPHFL9FQ62S)

## Contributing

Pull requests are welcome. For major changes, please open an issue first.
All pull requests must pass through rigorous testing before approval.

- Built with HTML, CSS, and JavaScript
- Licensed under GNU GPLv3

## Contact

- Email: open.text.compare@gmail.com

## Disclaimer: Accuracy & Reliability
This tool has been developed with care and thoroughly tested in a variety of scenarios. However, no software can guarantee perfect accuracy in all cases.
While this comparison tool works well for most use cases, you should always manually review the results, especially when working with sensitive, legal, or critical information.
No warranty or guarantee is provided, and the author(s) of this project are not liable for any losses, damages, or misinterpretations that may result from the use of this tool.

Use responsibly — and thank you for trusting this project!

## Test
In order to test it locally, I recommend using a CORS disabled version of your browser. Here's an example on how to open the chrome:
- Windows
`bash
start chrome --disable-web-security --user-data-dir="C:\chrome_dev"
`

- Mac
`bash
open -na "Google Chrome" --args --disable-web-security --user-data-dir="/tmp/chrome_dev"
`

- Linux
`bash
google-chrome --disable-web-security --user-data-dir="/tmp/chrome_dev"
`	