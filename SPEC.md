# Peace Website - School Project Specification

## Project Overview
- **Project Name**: Peace - Learn About Peace
- **Type**: Multi-page educational static website
- **Core Functionality**: Interactive learning website about peace with quiz, definitions, and comprehensive content
- **Target Users**: Students, teachers, presentation audience

## UI/UX Specification

### Pages
1. **index.html** - Home with hero, buttons, animations
2. **definition.html** - Definition of peace
3. **spread-peace.html** - How to live with peace
4. **quiz.html** - 10 questions
5. **answers.html** - Quiz answers
6. **learn-more.html** - Comprehensive content

### Visual Design

**Color Palette:**
- Primary: `#64B5F6` (Light Blue)
- Secondary: `#81D4FA` (Sky Blue)
- Accent: `#FFB74D` (Warm Orange)
- Background: Linear gradient `#E3F2FD` to `#BBDEFB`
- White: `#FFFFFF`
- Text: `#1A237E` (Deep Indigo)
- Text Secondary: `#5C6BC0`

**Typography:**
- Headings: 'Playfair Display', serif
- Body: 'Nunito', sans-serif
- Hero Size: 3.5rem (desktop), 2rem (mobile)

### Components

**Buttons:**
- Rounded (border-radius: 50px)
- Gradient background
- Hover: scale(1.1) + glow + shadow
- Click: bounce animation

**Hero Section:**
- Full screen (100vh)
- Animated gradient background
- Floating shapes/particles
- GSAP entrance animations
- Fade + slide + zoom effects

**Content Sections:**
- Cards with images and icons
- Headings + short explanations
- Smooth hover effects

**Quiz:**
- 10 multiple choice questions
- Interactive options with hover effects
- Answer reveal page

### Animations (GSAP + CSS)
- Fade-in on scroll
- Slide animations
- Floating elements
- Hover scale/glow
- Click bounce
- Floating background shapes

## Acceptance Criteria

- [ ] All 6 pages load without errors
- [ ] GSAP animations work smoothly
- [ ] Buttons have hover + click animations
- [ ] Quiz has 10 questions
- [ ] All pages link correctly
- [ ] Responsive design works
- [ ] Ready for presentation