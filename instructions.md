# instruction.md

## Fenrir Arena - Online Gaming Platform

**Company:** Fenrir Gaming Technologies
**Platform:** arena.fenrir.io

---

# 1. Project Overview

Fenrir Arena is an online gaming website that provides users with a unified platform to discover, play, and compete in browser-based games. The platform enables players to create profiles, track achievements, compete on leaderboards, and challenge friends in real-time multiplayer matches. The scope of work encompasses designing and developing a landing page, game library, leaderboard system, multiplayer lobby, achievement system, admin dashboard, and organizing the delivery package.

---

# 2. Design & Brand Guidelines

## 2.1 Design Identity

- **Project / Short Name**: Fenrir Arena
- **Tagline**: "Play. Compete. Conquer."
- **Brand**: Fenrir Gaming Technologies
- **Platform**: arena.fenrir.io
- **Focus Areas**: Landing Page, Game Library, Leaderboard, Multiplayer, Achievements, Admin Dashboard

## 2.2 Color Palette

The project must strictly utilize the following color palette across all screens and documentation:

- **Primary**: Midnight Blue (#0F172A)
- **Secondary**: Neon Cyan (#06F7D4)
- **Accent**: Electric Orange (#FF6B35)
- **Background**: Dark Charcoal (#1E293B)
- **Surface**: Slate Gray (#334155)
- **Text Primary**: Pure White (#FFFFFF)
- **Text Secondary**: Light Gray (#94A3B8)

## 2.3 Style & Typography Rules

- The overall style must be modern, immersive, and gaming-oriented.
- Do not use overly cartoonish or childish design elements unless specified for casual game sections.
- Primary body font must be Inter or a similar modern sans-serif typeface at 14px base size.
- Heading font must be Orbitron or a similar futuristic display font for titles (weights 700, 900).
- Secondary headings may use the same body font at weights 600 and 700.
- Card components must use rounded corners with a 12px border radius.
- Buttons must use slightly rounded shapes with 8px border radius and 16px horizontal padding.
- Icons must be from a consistent line-icon set (e.g., Lucide, Phosphor).
- Gaming elements may use subtle glow effects and gradient overlays.
- Dark theme is the primary design mode; light theme is optional.

---

# 3. Technical Specifications

## 3.1 Screen Dimensions & Layout

- All screen mockups must be designed at 1440 x 900 pixels for desktop viewport.
- Responsive breakpoints must be defined for tablet (768px) and mobile (375px).
- Navigation bar height must be fixed at 64px on desktop.
- Main content area must have 32px internal padding on all sides.
- Card spacing must use a consistent 20px gap between adjacent cards.
- Game grid must support a minimum 4-column layout on desktop.

## 3.2 File Formats

- **All Screen Mockups**: PNG format (1440 x 900 px / RGB)
- **Component Specification**: DOCX format (Standard Word Format)
- **Delivery Package**: ZIP format (Uncompressed Archive)

---

# 4. Home/Landing Page Instructions

## 4.1 Scope of Landing Page

The landing page must serve as the entry point for the platform, showing:

- Featured game hero carousel with animated transitions
- Trending games section based on player activity
- Game categories for easy discovery
- Platform statistics to build credibility
- Call-to-action for new user registration

## 4.2 Landing Page Requirements

Each landing page layout must include:

- A top navigation bar with logo, navigation links (Home, Games, Leaderboard, Community), search icon, and user profile / sign-in button
- A hero section with a large background image or gradient, featured game title, description, and a "Play Now" button
- A trending games row showing 4-6 game cards with thumbnail images, titles, and average ratings
- A categories section displaying game genres (Action, Puzzle, Strategy, Sports, Arcade) as icon-based cards
- A statistics bar showing total registered players, available games, daily active users, and tournaments held
- A call-to-action section encouraging sign-up with a prominent "Join Free" button
- A footer with company information, quick links, support contact, and social media icons

---

# 5. Game Library Instructions

## 5.1 Library Scope

The game library must display all available games in a browsable, filterable grid:

- Grid of game thumbnail cards with hover effects
- Search bar with real-time filtering
- Category and sorting filters
- Individual game detail view
- Rating and review display

## 5.2 Library Requirements

- Game cards must display at a fixed minimum width of 280px with responsive columns.
- Each game card must show a thumbnail image, game title, category badge, average rating (star icons), and a "Play" button.
- The search bar must support keyword search with a minimum 2-character trigger for suggestions.
- Filter chips must allow selection of game categories; multiple filters may be applied simultaneously.
- Sort dropdown must include options: Newest, Most Popular, Top Rated, and A-Z.
- The game detail page must include a larger banner image, full description, instructions section, rating interface, and a comments/review section.
- A "Back to Library" link must be present on the game detail page.

---

# 6. Leaderboard System Instructions

## 6.1 Leaderboard Scope

The leaderboard system must display player rankings across the platform:

- Global leaderboard sorted by experience points or score
- Friends-only leaderboard toggle
- Per-game leaderboard for individual game scores
- Time-period filters (Weekly, Monthly, All-Time)

## 6.2 Leaderboard Requirements

- Each leaderboard row must display rank number, player avatar, username, level badge, score/XP, and games played count.
- The top 3 players must be highlighted with gold, silver, and bronze styling respectively.
- The current logged-in user's row must be visually highlighted even if outside the top ranks.
- A toggle switch must allow switching between Global and Friends leaderboards.
- Time-period tabs (Week, Month, All-Time) must filter scores by the selected duration.
- A "View Profile" button must be available on each player row.
- The leaderboard must paginate with 20 players per page and a "Load More" button.

---

# 7. Multiplayer Lobby Instructions

## 7.1 Lobby Scope

The multiplayer lobby must provide a social gaming hub:

- Friends list with online status indicators
- Friend request management
- Matchmaking queue for automatic opponent finding
- Challenge system for direct friend invitations
- In-lobby chat functionality

## 7.2 Lobby Requirements

- The friends list must display each friend's avatar, username, current game (if playing), and an online/offline/idle status indicator with colored dots.
- An "Add Friend" button must open a search dialog to find users by username.
- Incoming friend requests must appear with Accept and Decline buttons.
- The matchmaking section must show the selected game, estimated wait time, and a "Find Match" button with a cancel option.
- The challenge section must allow selecting an online friend and sending a game invitation with a 30-second expiry.
- A minimal chat panel must be available for messaging online friends with message history.
- Notifications must appear for friend requests, match found, and challenge invitations.

---

# 8. Achievement & Rewards System Instructions

## 8.1 Achievement Scope

The achievement system must track and display player accomplishments:

- Achievement badges organized by category
- Experience points and level progression
- Trophy cabinet for rare achievements
- Daily login rewards
- Achievement unlock notifications

## 8.2 Achievement Requirements

- Achievements must be displayed in a grid of badge icons with locked (greyed out) and unlocked (full color) states.
- Each achievement must show its name, description, and unlock progress percentage.
- The experience bar must display current XP, XP needed for next level, and the current level number prominently.
- A trophy cabinet section must highlight the 3 rarest achievements earned by the player.
- A daily rewards calendar must show 7 days with earned and pending reward indicators.
- When an achievement is unlocked, a toast notification must slide in from the top-right with the achievement name, icon, and XP reward.
- A "View All Achievements" page must list every achievement with filtering by category and unlock status.

---

# 9. Admin Dashboard Instructions

## 9.1 Admin Scope

The admin dashboard must provide platform management tools:

- Game inventory management (CRUD operations)
- User moderation panel
- Platform analytics dashboard
- Content management for banners and announcements
- Report and flag management

## 9.2 Admin Requirements

- The admin dashboard must be accessible only through a dedicated admin login with role-based access.
- The game management panel must list all games in a table with columns: thumbnail, title, category, status (published/draft), plays count, rating, and action buttons (edit, delete).
- A "Add New Game" form must include fields: title, description, category, thumbnail upload, game file upload, instructions, and difficulty level.
- The user moderation panel must display users in a searchable table with columns: avatar, username, email, registration date, status, reports count, and actions (warn, ban, delete).
- The analytics section must show charts for user growth (line chart), game popularity (bar chart), daily active users, and platform revenue if applicable.
- The content management section must allow creating and scheduling banner announcements for the landing page.
- The reports panel must list flagged content or user reports with status tracking (pending, reviewed, dismissed).

---

# 10. Quality Assurance (QA)

## 10.1 QA Checklist

Every design delivery must pass the following check gates:

- All screens are delivered at 1440 x 900 pixel resolution.
- The color palette uses Midnight Blue #0F172A, Neon Cyan #06F7D4, Electric Orange #FF6B35, Dark Charcoal #1E293B, and Slate Gray #334155.
- The landing page contains a nav bar, hero section, trending games, categories, stats bar, CTA, and footer.
- The game library contains a searchable grid, filter/sort options, and individual game detail pages.
- The leaderboard shows player rankings with top-3 highlights and time-period filters.
- The multiplayer lobby includes friends list, matchmaking, challenge system, and chat.
- The achievement system displays badges, XP bar, trophies, and daily rewards.
- The admin dashboard includes game management, user moderation, and analytics.
- All fonts use Inter and Orbitron as specified.
- File names strictly follow the defined file naming convention.

## 10.2 Error Severity Levels

- **Critical**: Missing screen mockup, incomplete PRD documentation, or deviation from naming conventions.
- **Major**: Incorrect screen resolution, missing UI component, or wrong color palette usage.
- **Minor**: Slight alignment errors in layouts or typography inconsistencies.

---

# 11. File Naming Convention

All files must follow the naming structure below:

```plaintext
FenrirArena_[Category]_[Format]_v[N].[ext]
```

## Examples

```plaintext
FenrirArena_Home_PNG_v1.png
FenrirArena_GameLibrary_PNG_v1.png
FenrirArena_Leaderboard_PNG_v1.png
FenrirArena_ComponentSpec_DOCX_v1.docx
FenrirArena_FinalDelivery_v1.zip
```

---

# 12. Folder Structure

All project deliverables must be organized in the following folder structure:

```plaintext
FenrirArena/
├── 01_Screen_Mockups/
├── 02_UI_Components/
├── 03_Documentation/
├── 04_Assets/
└── 05_Final_Delivery/
```

---

# 13. Final Deliverables Checklist

- **All Screen Mockups**: PNG format in `01_Screen_Mockups/` (Home, Game Library, Leaderboard, Multiplayer Lobby, Achievements, Admin Dashboard)
- **UI Component Specs**: DOCX format in `02_UI_Components/`
- **Product Requirements Document**: DOCX format in `03_Documentation/`
- **Final Delivery Package**: ZIP format in `05_Final_Delivery/`

---

# 14. Scope Boundaries

The following tasks and items are explicitly out of scope for this project:

- Backend API development, server infrastructure, and database architecture.
- Native mobile application development for iOS or Android platforms.
- Actual game development or game engine integration.
- Payment gateway integration and subscription billing systems.
- Real-time WebSocket or WebRTC implementation for multiplayer functionality.
- Content creation for game assets, artwork, or sound effects.

---

# 15. Company Reference

Fenrir Gaming Technologies is a game technology company based in Bengaluru, Karnataka, India. Website: arena.fenrir.io | Email: dev@fenrir.io.

---

# 16. Summary

This project requires a complete UI/UX design and front-end development package for Fenrir Arena, an online gaming platform. The design must emphasize an immersive, modern gaming aesthetic with dark theme orientation, glow effects, and competitive gaming elements across all screens, components, and technical specification documents.
