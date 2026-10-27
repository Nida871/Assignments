## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).
/src/
## Module 6 - Task 28: Overflow Fix

**Problem:** Long text was overflowing outside the container and breaking the layout.

**Solution:** I fixed it using CSS properties:
- `overflow-wrap: break-word;` - breaks long words to stay inside
- `box-sizing: border-box;` - includes padding and border in width
- `max-width: 100%;` - prevents container from going outside
- `overflow: hidden;` - hides any extra overflow

**Before:** Text was going outside red box
**After:** Text stays inside green box

File: `src/overflow-fix.html`
## Task 29: Hero Section
- Created a 400px height hero section
- Used background image + gradient, background-size: cover
- Used padding 100px for centering content
- File: src/hero.html
## Task 30: Profile Card (Final)
- Used all Box Model properties: width, padding, margin, border, border-radius
- Added box-shadow, box-sizing, image with circular border
- File: src/profile.html
- Module 6 Complete!
## Task 31: Responsive Menu Bar
- Used display:flex, justify-content: space-between
- Responsive with flex-direction: column on mobile
- File: src/flex-menu.html
## Task 32: Centered Login Form
- Used display:flex + justify-content:center + align-items:center + height:100vh for perfect centering
- File: src/flex-login.html
## Task 33: Product Listing with flex-wrap
- Used display:flex, flex-wrap:wrap, gap, justify-content:center
- 6 cards automatically wrap on smaller screens
- File: src/flex-products.html
## Task 34: Navbar + Hero with Flexbox
- Navbar + Hero both using Flexbox
- Used flex:1 for equal columns, space-between, align-items:center
- Fully responsive with flex-direction: column
- File: src/flex-hero.html
## Task 35: Pricing Cards with Flexbox (Final)
- Used display:flex, justify-content:center, align-items:stretch
- Used flex-direction:column and flex-grow:1 for equal height cards
- Used transform:scale for featured card highlight
- File: src/flex-pricing.html
- Module 7 Complete!
## Task 36: Photo Gallery with CSS Grid
- Used display:grid, grid-template-columns: repeat(3, 1fr), gap
- Responsive: 3 cols -> 2 cols -> 1 col
- File: src/grid-gallery.html
## Task 37: Auto Responsive Product Grid
- Used repeat(auto-fit, minmax(200px, 1fr)) for automatic reflow
- No media query needed, grid handles itself
- File: src/grid-products.html
## Task 38: Dashboard with Named Grid Areas
- Used grid-template-areas, grid-area, grid-template-columns/rows
- Responsive: sidebar goes top on mobile
- File: src/grid-dashboard.htmla
## Task 39: Shop Layout - Header + Sidebar + Products using Grid
- Outer layout using named grid areas
- Inner products using repeat(auto-fit, minmax)
- Nested Grid concept
- File: src/grid-shop-layout.html
## Module 8: CSS Grid (Task 36-40) - COMPLETE

### Task 36: Photo Gallery
- display:grid, repeat(3, 1fr), gap
- File: src/grid-gallery.html

### Task 37: Auto Responsive Grid
- repeat(auto-fit, minmax(200px, 1fr))
- File: src/grid-products.html

### Task 38: Dashboard with Named Areas
- grid-template-areas, grid-area
- File: src/grid-dashboard.html

### Task 39: Shop Layout
- Header + Sidebar + Products, Nested Grid
- File: src/grid-shop-layout.html

### Task 40: Final Grid Project
- Combined all concepts: hero (2 cols), features (auto-fit), gallery (4 cols), named areas
- File: src/grid-final-project.html

# Module 8 Complete! 🎉
## Task 41: Breakpoints Added
- Added 3 breakpoints: 1024px (tablet), 768px (mobile), 480px (small mobile)
- Tested responsive layout on multiple screen sizes
- File: src/responsive-audit.html
## Module 9: Responsive Design (Task 41-45) - COMPLETE

### Task 41: Breakpoints
- Added 3 breakpoints 1024px, 768px, 480px
- File: src/responsive-audit.html

### Task 42: Audit & Fix
- Fixed overflow, image max-width, horizontal scroll
- File: src/responsive-audit.html (updated)

### Task 43: Landing Page Grid + Flexbox
- Grid for page layout, Flexbox for header/CTA
- File: src/landing-page.html

### Task 44: Desktop Base Styles
- HTML skeleton + desktop 3-col layout## Module 5 - CSS Fundamentals (Done by Nida Idrisi)

### Design Choices:
- **Colour Palette:** Primary blue (#4a6cf7) for trust and professionalism, light background (#f0f4ff) for readability.
- **Fonts:** Segoe UI for body (clean), Georgia for headings (elegant pairing).
- **CSS Variables:** Used :root variables for colours and fonts so we can change whole theme from one place.
- **Selectors Used:** Element (header), ID (#fullname), Class (.form-input), Attribute (input[type="email"]) - as required in Task 22.
- **Pages Styled:** registration.html and resume.html converted from plain HTML to styled pages.

Live Link: https://nida1704.github.io/BCA-Assignment
- File: src/landing-page.html

### Task 45: Fully Responsive Final
- Added 3 breakpoints, mobile nav hide, single column
- File: src/landing-page.html - FINAL SUBMIT

# Module 9 Complete! 🎉# Assignments
