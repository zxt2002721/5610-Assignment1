# SudokuMaster - The Ultimate Number Puzzle Game

A modern, responsive web application mock for playing Sudoku puzzles with multiple difficulty levels and an intuitive user interface.

## 👥 Collaborators
- **Junkai Chen**
- **Xiaotian Zhang**

## 📂 Repository
**GitHub Repository:** [https://github.com/zxt2002721/5610-Assignment1](https://github.com/zxt2002721/5610-Assignment1)

## 🎥 Demo Video
**Assignment Walkthrough Video:** [https://drive.google.com/file/d/1L3CqoQ0kFWcSuXqPWmyqj9_leNbyLz5R/view?usp=drive_link](https://drive.google.com/file/d/1L3CqoQ0kFWcSuXqPWmyqj9_leNbyLz5R/view?usp=drive_link)

## 📋 Project Overview

SudokuMaster is a static HTML/CSS mock website for a Sudoku game featuring:
- **Multiple Difficulty Levels**: Easy 6×6 grids for beginners and challenging 9×9 grids for experts
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, intuitive interface with smooth CSS animations and transitions
- **Static Game Display**: Mock game pages showing Sudoku in progress
- **User Management Pages**: Registration and login page layouts
- **Leaderboards**: Mock high scores display
- **Comprehensive Rules**: Detailed game instructions and solving strategies

## 🏗️ Project Structure

```
CS5610_HW1/
├── index.html              # Landing page with hero section
├── css/
│   └── common.css          # Shared styles and responsive design
├── login/
│   └── index.html          # User login page
├── register/
│   └── index.html          # User registration page
├── selection/
│   └── index.html          # Game selection page
├── easy-game/
│   └── index.html          # 6×6 Sudoku game
├── hard-game/
│   └── index.html          # 9×9 Sudoku game
├── rules/
│   └── index.html          # Game rules and instructions
├── highscore/
│   └── index.html          # Leaderboard and statistics
└── images/                 # Image assets
```

## ✨ Key Features

### 🎮 Game Display
- **Two Difficulty Levels**: 6×6 (Easy) and 9×9 (Hard) Sudoku grids
- **Static Game Boards**: Pre-filled Sudoku grids showing games in progress
- **Number Inputs**: Input fields accepting numbers 1-9 (6×6 grid accepts 1-6)
- **Timer Display**: Static timer showing example time (e.g., "12:34")
- **Progress Display**: Visual progress bar showing mock completion percentage
- **Game Controls**: Mock buttons for hint, pause, and reset functionality

### 🎨 Design & User Experience
- **Modern Gradient Design**: Purple-blue color scheme with professional aesthetics
- **Responsive Layout**: Mobile-first design that works on all screen sizes
- **Smooth Animations**: CSS transitions and hover effects throughout
- **Accessibility Features**: ARIA labels and semantic HTML structure
- **Visual Feedback**: Color-coded difficulty badges and hover states

### 👤 User Management
- **Registration Page**: Signup form with username, password, and confirm password fields
- **Login Page**: Login form with username and password fields (password input type used)
- **Form Layout**: Well-structured forms with submit buttons (no validation logic)
- **Social Login Display**: Mock Google and Facebook login buttons

### 📊 Statistics & Leaderboards
- **Mock Leaderboard**: Static list of usernames with fake scores and completion stats
- **Performance Display**: Mock solve times and completion rates
- **Achievement Display**: Static badges and milestone indicators
- **Filtering Display**: Mock filter buttons for time period and difficulty

## 💭 Assignment Reflection

### 1. What was the most challenging part of this assignment? How did you find HTML and CSS? How much time did you spend overall?

The most challenging aspect was creating a cohesive, responsive design system that works seamlessly across all pages while maintaining visual consistency using only HTML and CSS. HTML felt intuitive and straightforward - the semantic structure made sense for organizing content. CSS, however, presented more complexity, especially when implementing responsive grid layouts for the Sudoku boards and ensuring cross-browser compatibility. The CSS Grid and Flexbox properties required careful planning to achieve the desired layouts without breaking on different screen sizes. Creating the Sudoku grid with proper sub-grid borders using only CSS was particularly challenging. Overall, we spent approximately 25-30 hours on this project, with the majority of time dedicated to CSS styling and responsive design refinements.

### 2. What decisions did you make when designing for mobile-friendliness?

We implemented a mobile-first approach with several key decisions: (1) Used CSS Grid and Flexbox for flexible layouts that automatically adapt to screen sizes, (2) Implemented a collapsible hamburger menu design for navigation on smaller screens using CSS only, (3) Adjusted font sizes and spacing using media queries for optimal readability, (4) Made the Sudoku grids touch-friendly with larger input areas on mobile devices, (5) Reorganized complex layouts into single-column stacks on mobile, and (6) Used relative units (rem, %, vw/vh) instead of fixed pixels for better scalability. The layout was designed to be thumb-friendly, and we ensured all clickable elements meet the minimum 44px touch target size recommended by accessibility guidelines.

### 3. What factors did you consider when designing the website? What are you particularly proud of?

We focused on creating a professional gaming aesthetic with strong visual hierarchy. Key considerations included: (1) Color psychology - using calming blues and purples to promote focus and concentration, (2) Visual hierarchy - clear typography and spacing to guide user attention, (3) Consistency - unified design language across all pages, (4) Performance - optimized CSS with no external dependencies beyond fonts, and (5) Accessibility - proper semantic HTML and clear structure. We're particularly proud of the gradient-based visual design system, the comprehensive layout of the game statistics page, and the smooth CSS transitions throughout the interface. The Sudoku grid styling with proper sub-grid borders using CSS Grid was especially challenging to implement correctly, and achieving a clean responsive design without any JavaScript was a rewarding accomplishment.

### 4. If you had more time/resources, what new features would you add?

With additional time and the ability to use JavaScript in future assignments, we would implement: (1) Functional timer that counts up during gameplay, (2) Interactive game logic that validates moves and prevents invalid entries, (3) Puzzle generation algorithms for unlimited content, (4) Save game state functionality, (5) Working hint system that provides solving suggestions, (6) Difficulty selection that generates appropriate puzzles, (7) Backend integration with user accounts and persistent game saves, (8) Real leaderboard with actual user scores, (9) Daily challenges and achievements system, (10) Advanced analytics for tracking solving patterns, and (11) Additional visual themes and customization options.

### 5. How many hours did you spend on this assignment in total?

We spent approximately 28 hours total on this assignment, distributed as follows: Planning and wireframing (3 hours), HTML structure development (6 hours), CSS styling and responsive design (15 hours), testing and debugging across different screen sizes (3 hours), and final polish and documentation (1 hour). The CSS portion took the longest as we iterated on the design multiple times to achieve the desired visual quality and ensure cross-device compatibility without using any JavaScript or CSS frameworks.

### 6. (Optional) What assumptions did you make about the assignment?

We assumed that creating a polished, portfolio-quality static mock was preferred over a minimal wireframe. While the assignment specified creating wireframes/mocks, we focused on producing a visually complete design that demonstrates strong HTML and CSS fundamentals. We also assumed that modern CSS features (CSS Grid, Flexbox, custom properties) were acceptable to use, and that importing fonts from Google Fonts was within the guidelines. All interactive functionality was implemented as static displays - the timer shows a fixed time, forms have no validation logic, and game boards are pre-filled examples rather than playable puzzles.

### 7. (Optional) External Resources and Credits

**Fonts:** Google Fonts - Poppins family for clean, modern typography  
**Design Inspiration:** Modern gaming interfaces and puzzle game aesthetics from sites like NYTimes Sudoku  
**CSS Techniques:** CSS-Tricks and MDN Web Docs for advanced Grid and Flexbox layout methods  
**Color Palette:** Custom gradient combinations inspired by modern web design trends  
**Responsive Design Patterns:** Mobile-first methodology following industry best practices  

**Important Note:** This project contains NO JavaScript whatsoever. All animations and transitions are pure CSS. The timer displays static text, forms have no validation logic, and all game boards show pre-filled static examples. Input fields accept numbers 1-9 (or 1-6 for easy mode) through HTML input type restrictions only, with no dynamic validation.

All code was written from scratch without external frameworks or libraries, using only vanilla HTML and CSS to demonstrate fundamental web development skills as required by the assignment.
