# TradePro - Construction Project Management System

## Overview

TradePro is a comprehensive construction project management system designed for contractors, project managers, and construction teams. The platform provides mobile-first interfaces for field work with a powerful desktop back-office system for project oversight.

## Live Demo

**Mobile App:** https://f666cdx5tg-sudo.github.io/tradepro/tradepro-mobile-v3-11-contract-balance-auto%20(2).html

## Features

### Mobile App (iPhone 14 Optimized)

#### Core Modules
- **Dashboard** - Real-time project overview with weather, location, and quick stats
- **Projects** - Complete project list with search, filter, and status tracking
- **Project Details** - Comprehensive project information with contract balance tracking
- **Tasks** - Task management with assignments, priorities, and progress tracking
- **Crew** - Team member management with contact information
- **Materials** - Material tracking, quantities, and cost management
- **Change Orders** - Change order creation and approval workflow
- **Invoices** - Invoice generation and payment tracking
- **Client Portal** - Client communication and document sharing
- **Daily Log** - Daily activity logging with photo uploads
- **Messages** - Team communication system
- **Schedule** - Calendar view with task scheduling
- **Camera/Uploads** - Photo documentation with geolocation
- **Settings** - User preferences and app configuration

#### Key Capabilities
- ✅ Persistent state management using localStorage
- ✅ Offline-capable with local data storage
- ✅ Real-time weather integration
- ✅ Geolocation services
- ✅ Photo upload and documentation
- ✅ Contract balance calculations
- ✅ Budget tracking and reporting
- ✅ Multi-project support
- ✅ Dark theme UI optimized for field use

### Desktop Back-Office (Coming Soon)
- Advanced reporting and analytics
- Multi-project dashboard
- Document management
- Financial overview
- Team performance metrics

## Technology Stack

- **Frontend:** Pure HTML5, CSS3, JavaScript (ES6+)
- **Storage:** localStorage for persistent data
- **UI Framework:** Custom responsive framework
- **Icons:** Font Awesome 6.4.0
- **Design:** Mobile-first, progressive web app architecture

## Installation

### Quick Start

1. Clone the repository:
```bash
git clone https://github.com/f666cdx5tg-sudo/tradepro.git
cd tradepro
```

2. Open the mobile app:
```bash
open tradepro-mobile-v3-11-contract-balance-auto\ \(2\).html
```

Or simply visit the live demo URL in your browser.

### Mobile Installation

**iOS (Safari):**
1. Open the app URL in Safari
2. Tap the Share button
3. Select "Add to Home Screen"
4. Name it "TradePro" and tap "Add"

**Android (Chrome):**
1. Open the app URL in Chrome
2. Tap the menu (⋮)
3. Select "Add to Home screen"
4. Confirm the installation

## Usage

### First Time Setup

1. **Access the Dashboard** - The app opens to the main dashboard showing:
   - Current location and weather
   - Active projects count
   - Pending tasks
   - Today's schedule

2. **Create a Project** - Navigate to Projects and tap "New Project":
   - Enter project name, client, and address
   - Set budget and timeline
   - Add project notes
   - Click "Create Project"

3. **Add Tasks** - From the project detail view:
   - Tap "Tasks" tab
   - Click "Add Task"
   - Assign to crew members
   - Set priority and due date

4. **Track Materials** - Monitor material usage:
   - Navigate to Materials
   - Add items with quantities and costs
   - Track delivery status
   - Monitor budget impact

5. **Daily Logging** - Document daily activities:
   - Open Daily Log
   - Record work performed
   - Upload photos
   - Note any issues or delays

### Data Persistence

All data is automatically saved to your device's localStorage:
- Projects and their details
- Tasks and assignments
- Crew information
- Materials tracking
- Daily logs and photos
- Messages and communications

**Note:** Clear browser data will reset the app. Export important data regularly.

## Project Structure

```
tradepro/
├── README.md
├── tradepro-mobile-v3-11-contract-balance-auto (2).html    # Main mobile app
├── docs/                                                    # Documentation
├── assets/                                                  # Images and resources
└── backoffice/                                             # Desktop system (planned)
```

## Roadmap

### Version 3.2 (Next Release)
- [ ] TestFlight distribution for iOS
- [ ] Push notifications for task updates
- [ ] Offline sync improvements
- [ ] PDF report generation
- [ ] Time tracking module

### Version 4.0 (Future)
- [ ] Desktop back-office system
- [ ] Cloud sync and backup
- [ ] Multi-user collaboration
- [ ] API for third-party integrations
- [ ] Advanced analytics dashboard
- [ ] Accounting system integration

## Browser Support

- ✅ iOS Safari 14+
- ✅ Chrome 90+ (Mobile & Desktop)
- ✅ Firefox 88+ (Mobile & Desktop)
- ✅ Edge 90+
- ⚠️ Internet Explorer: Not supported

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For issues, questions, or suggestions:
- Open an issue on GitHub
- Check existing documentation
- Review closed issues for solutions

## Acknowledgments

- Built for construction professionals
- Designed with field usability in mind
- Inspired by real-world contractor needs

## Version History

- **v3.1** (Current) - Contract balance tracking, auto-calculations, enhanced UI
- **v3.0** - Complete mobile redesign, localStorage implementation
- **v2.0** - Multi-project support, task management
- **v1.0** - Initial release with basic project tracking

---

**Made with ❤️ for construction teams**
