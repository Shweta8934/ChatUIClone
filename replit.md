# Telegram Style Chatbot

## Overview

This is a frontend-only web application that implements a Telegram-style chatbot interface. The project creates a responsive, mobile-friendly chat UI with modern design elements including gradients, shadows, and smooth animations. It features a clean chat container with header, message area, and input controls, styled to mimic popular messaging applications like Telegram.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Single Page Application**: Built with vanilla HTML, CSS, and JavaScript (implied from structure)
- **Responsive Design**: Mobile-first approach with flexible layouts using CSS Flexbox
- **Component-based Styling**: Modular CSS with separate styles for chat container, header, messages, and input areas
- **Modern UI Framework**: Uses CSS Grid and Flexbox for layout management

### Design System
- **Color Scheme**: Telegram-inspired blue gradient theme (#0088cc, #006bb3) with white backgrounds
- **Typography**: System fonts stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto)
- **Visual Effects**: Box shadows, border radius, and gradient backgrounds for modern appearance
- **Icons**: Font Awesome 6.4.0 integration for UI elements

### Chat Interface Components
- **Chat Container**: Fixed-height container (90vh, max 700px) with overflow management
- **Header Section**: Gradient background with avatar placeholder and title
- **Message Area**: Scrollable content area with distinct styling for user vs bot messages
- **Input Controls**: Bottom-fixed input area with text field and send functionality

### Styling Architecture
- **CSS Reset**: Universal box-sizing and margin/padding reset
- **Gradient Backgrounds**: Linear gradients for visual depth and modern appearance
- **Responsive Breakpoints**: Flexible width constraints (max-width: 500px for chat, 600px variant exists)
- **Message Differentiation**: Color-coded messages (green for user #dcf8c6, gray for bot #f1f0f0)

## External Dependencies

### Third-party Libraries
- **Font Awesome 6.4.0**: Icon library loaded via CDN for UI elements and chat interface icons
- **Google Fonts**: System font fallbacks suggest potential web font integration

### Browser APIs
- **Viewport Meta Tag**: Ensures proper mobile responsiveness
- **CSS3 Features**: Relies on modern browser support for gradients, flexbox, and box-shadow effects

### Development Dependencies
- **No Build Process**: Pure HTML/CSS/JS implementation requiring no compilation or bundling
- **CDN Resources**: External dependencies loaded directly from CDNs for simplicity