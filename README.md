# Diner Invitation

An interactive dinner invitation with a beautiful envelope animation.

## Features

- 3D envelope flip animation
- Interactive card with flip functionality
- Background music player
- Calendar integration (download .ics file)
- Download invitation images
- Responsive design (desktop and mobile)

## Getting Started

### Development

To run the project locally:

```bash
# Using Python 3 (recommended)
python3 -m http.server 8080

# Or use npm if you have Node.js installed
npm run dev
```

Then open your browser to `http://localhost:8080`

### Assets

The project uses the following assets:
- **Fonts**: Snell Roundhand, STIX Two Text
- **Images**: stamp, wax seal, invitation front/back
- **Music**: Background music for the invitation
- **Logo**: Event logo

## Customization

To customize the invitation for your event:

1. Update the names in `index.html` (search for "Khedija" and "M'hamed")
2. Update event dates and locations
3. Replace images in `src/assets/images/`
4. Replace background music in `src/assets/music/`
5. Update the calendar events in the JavaScript section

## Structure

```
Diner-invitation/
├── index.html              # Main HTML file with embedded CSS and JS
├── src/
│   └── assets/
│       ├── fonts/          # Custom fonts
│       ├── images/         # Images (stamp, seal, invitations)
│       ├── logos/          # Event logo
│       └── music/          # Background music
├── package.json
└── README.md
```

## Browser Support

The invitation works best on modern browsers with support for:
- CSS 3D transforms
- HTML5 audio
- MediaSession API (for iOS music controls)

## License

ISC
