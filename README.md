Build a fully responsive website named **Chamada Poker** that is approximately 98% similar in structure, information architecture, page types, navigation flow, and content organization to meritpoker.com.

The design layout, page hierarchy, and feature set should closely follow meritpoker.com, while the branding, colors, and identity should be inspired by Chamada Hotels.

The system must include:
1) A Public Website
2) A Secure Admin Dashboard
3) A User Management & CMS Backend

--------------------------------------------------
PUBLIC WEBSITE STRUCTURE (MERITPOKER-STYLE)
--------------------------------------------------

The public website should closely mirror meritpoker.com and include the following main sections and pages:

HOME PAGE
- Hero section with featured tournaments or announcements
- Highlighted upcoming tournaments
- Latest news preview
- **Dedicated homepage video section** for promotions, highlights, or announcements
- Quick access sections for:
  - Live Cash Games
  - Tournaments
  - Gallery
  - News
- Clean, premium, casino-style layout similar to meritpoker.com

TOURNAMENTS
- Upcoming tournaments
- Ongoing tournaments
- Past tournaments & results
- Tournament detail pages including:
  - Schedule
  - Date & time
  - Location
  - Buy-in
  - Prize pool
  - Structure details
  - Registration or ticket information
  - Images and banners

LIVE CASH GAMES
- Dedicated **Live Cash Games** section (as seen on meritpoker.com)
- Pages displaying:
  - Available cash game types
  - Stakes / limits
  - Game formats (Hold’em, Omaha, etc.)
  - Live status or schedules
- Informational focus (not online gameplay)

NEWS
- Poker news and announcements
- Event updates
- Promotional articles
- News detail pages with images and publish dates

LEADERBOARDS & RESULTS
- Player rankings
- Tournament results
- Historical performance displays

GALLERY
- Photo and media gallery
- Event photos and promotional media
- Organized by category or event
- Image and video support

ABOUT US
- Brand story and description
- **Team Members section** including:
  - Name
  - Role / position
  - Bio
  - Profile photo
  - Social links (optional)

POKER RULES
- Cash game rules
- Tournament rules

CONTACT
- Contact form
- General inquiries

PRIVACY POLICY
- Static informational page

--------------------------------------------------
MULTI-LANGUAGE REQUIREMENTS
--------------------------------------------------
- Primary language: English
- Secondary languages: Turkish and Russian
- Language switcher available on the website
- All content must be translatable and manageable per language
- SEO-friendly multilingual URLs (e.g. /en, /tr, /ru)
- Default language fallback to English

--------------------------------------------------
ADMIN DASHBOARD REQUIREMENTS
--------------------------------------------------
The admin dashboard must provide full control over the entire website.

ADMIN AUTHENTICATION
- Secure login
- Role-based access control

ADMIN FEATURES
- Dashboard overview showing:
  - Upcoming tournaments
  - Live cash game info
  - Recent news, videos, and gallery updates
  - Site statistics
  - Recent admin actions

CONTENT MANAGEMENT
- Create, edit, delete tournaments
- Manage live cash games (game type, stakes, schedules, descriptions)
- Publish and schedule homepage videos
- Upload and manage images and videos
- Manage gallery content (images & videos)
- Publish, unpublish, and schedule news articles
- Manage leaderboards and results
- Manage team members (name, role, bio, photo)
- Manage static pages (About, Rules, Privacy Policy)
- Moderate contact form submissions

SITE SETTINGS
- Logo upload
- Color configuration
- SEO metadata
- Social media links
- Language settings

--------------------------------------------------
UI / UX & BRANDING
--------------------------------------------------
- Overall layout, navigation structure, and page flow must closely resemble meritpoker.com
- Typography, spacing, section placement, and hierarchy should follow meritpoker.com
- Branding and colors inspired by Chamada Hotels:
  - Dark Charcoal / Black: #111111
  - White: #FFFFFF
  - Gold: #C59A4C
  - Deep Red: #B22222
  - Dark Gray: #4A4A4A
  - Light Gray: #F6F6F6
- Use gold and deep red accents sparingly for CTAs and highlights
- Maintain a luxury, professional, casino-resort aesthetic

--------------------------------------------------
BACKEND & TECHNICAL REQUIREMENTS
--------------------------------------------------
- Frontend: React or Next.js
- Backend: Node.js + Express, Next.js API routes, or Laravel
- Database: PostgreSQL or MySQL with tables for:
  - Users
  - Admin roles
  - Tournaments
  - Live cash games
  - News
  - Videos
  - Gallery
  - Team members
  - Leaderboards & results
  - Static pages
  - Translations
- REST API for frontend-backend communication
- Authentication & authorization (JWT or sessions)
- Image and video upload/storage (cloud or server-based)
- Admin action logging
- Security best practices:
  - Input validation
  - XSS protection
  - SQL injection prevention

--------------------------------------------------
OPTIONAL ENHANCEMENTS
--------------------------------------------------
- Advanced SEO with hreflang support
- Automated newsletter emails per language
- Video thumbnails and previews
- Performance optimization and caching
