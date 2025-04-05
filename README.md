
Built by https://www.blackbox.ai

---

```markdown
# Shoolini Cupid

## Project Overview
Shoolini Cupid is a web application designed to connect students from Shoolini University. The platform allows users to log in with their university email, set up their profiles, and engage in a dating-like experience to meet fellow students. The application features support for profile setup, swiping on potential matches, and direct messaging.

## Installation
To run the Shoolini Cupid application on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/shoolini-cupid.git
   ```
2. Navigate to the project directory:
   ```bash
   cd shoolini-cupid
   ```
3. Open the `index.html` file in your web browser to start the application:
   ```bash
   open index.html
   # or for Windows
   start index.html
   ```

## Usage
- Open `index.html` in a web browser to view the splash screen.
- After three seconds, the page redirects to the login screen (`login.html`).
- Enter your Shoolini University email to log in.
- Follow the prompts to set up your profile.
- Engage with potential matches using the swipe interface (`swipe.html`).
- Access chat functionality through the chat interface (`chat.html`).

## Features
- **User Authentication:** Login using Shoolini university emails.
- **Profile Setup:** Users can upload photos and fill out personal information.
- **Swipe Functionality:** Users can swipe right to like or left to pass on profiles.
- **Chat System:** Direct messaging interface for communicating with matches.
- **Admin Panel:** An admin view for managing users.

## Dependencies
This project utilizes several libraries, included in the HTML files:

- [Tailwind CSS](https://tailwindcss.com/) for UI styling.
- [Font Awesome](https://fontawesome.com/) for icons.
- [Hammer.js](https://hammerjs.github.io/) for gesture recognition in the swiping interface.

## Project Structure
The project structure consists of multiple HTML files, each serving a different purpose in the application:

```
shoolini-cupid/
│
├── index.html        # Splash screen
├── login.html        # User login page
├── setup.html        # Profile setup page
├── swipe.html        # Swiping interface for matches
├── chat.html         # Chat interface for messages
├── explore.html      # Explore other users
├── settings.html     # User settings page
├── admin.html        # Admin panel for managing users
└── other_assets/      # Additional assets (if any)
```

Each page is styled using Tailwind CSS and incorporates responsive design principles.
```