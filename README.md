# To-Do-List-Pro
# To-Do List App Specification

## Project Overview
- **Project name**: To-Do-List-Pro
- **Type**: Single-page web app (HTML/CSS/JS)
- **Core functionality**: Simple to-do list with add, complete, and delete tasks
- **Target users**: Anyone needing a quick, visually appealing task manager

## UI/UX Specification

### Layout Structure
- Centered card container (max-width: 480px)
- Header with app title
- Input section with text field + add button
- Task list with scrollable area
- Each task: checkbox + text + delete button

### Visual Design

**Color Palette**
- Background: #FFF9C4 (light sunny yellow)
- Card background: #FFFFFF
- Primary accent: #FF6B6B (coral red)
- Secondary accent: #4ECDC4 (teal)
- Completed task: #A8E6CF (mint green)
- Text primary: #2D3436
- Text muted: #636E72

**Typography**
- Font: 'Nunito', sans-serif (Google Fonts)
- Title: 32px, bold, #FF6B6B
- Input: 16px
- Task text: 16px
- Delete button: 18px

**Spacing**
- Card padding: 24px
- Task item padding: 12px 16px
- Gap between tasks: 8px

**Visual Effects**
- Card: 16px border-radius, soft shadow (0 8px 32px rgba(0,0,0,0.1))
- Buttons: rounded, smooth hover transitions (0.2s)
- Task completion: strikethrough + background color change
- Input focus: teal border glow

### Components

**Header**
- App title "Bright Tasks" with emoji ✨

**Input Section**
- Text input with placeholder "Add a new task..."
- Rounded "Add" button with + icon

**Task Item**
- Rounded rectangle
- Custom checkbox (teal when checked)
- Task text (strikethrough when complete)
- Delete button (×) appears on hover

**Empty State**
- Friendly message when no tasks

## Functionality Specification

1. Add task: Enter text → click Add or press Enter
2. Complete task: Click checkbox to toggle
3. Delete task: Click × button
4. Tasks persist in localStorage
5. Prevent empty task submission

## Acceptance Criteria
- [ ] App loads with bright yellow background
- [ ] Can add new tasks
- [ ] Can mark tasks complete (strikethrough + color change)
- [ ] Can delete tasks
- [ ] Tasks survive page refresh (localStorage)
- [ ] Empty input not allowed
- [ ] Responsive on mobile
