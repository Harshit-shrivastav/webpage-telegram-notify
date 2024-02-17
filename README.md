# Webpage Telegram Notification

This is a simple website that allows admin to record visitors data. When a visitor fills out their name and email address and clicks the "Notify Me" button, their information is sent to a Telegram bot, which notifies the website owner about the new visitor.

## Features

- Visitor information collection:
- Notification via Telegram: Information about new visitors, including their name, email, IP address, and timestamp, is sent to a Telegram bot for notification.
- Error handling: If there are any issues with sending the notification, the user is alerted with an error message.

## Usage

To use this code:

1. Clone this repository to your local machine.
2. Replace SECRET_USER_ID and SECRET_BOT_TOKEN variables in line 21 and line 22 in the code.
3. Open the `index.html` file in a web browser.
4. Fill out the name and email fields.
5. Click the "Notify Me" button.
6. If successful, you will receive an alert saying "Notification sent successfully!".

## Variables 
- SECRET_USER_ID - Get it from the https://telegram.me/my_id_bot or similar bot
- SECRET_BOT_TOKEN - Get it from https://telegram.me/botfather
  Check line 21 and line 22 in the code
## Requirements

- Web browser with JavaScript enabled
- Internet connection to fetch IP address and send Telegram messages

## Technologies Used

- HTML
- CSS (not included in this example)
- JavaScript

## License

This project is licensed under the Apache License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project is inspired by the need for a simple notification system for website owners to track visitor.
