# Project 0: Template Analysis (Part 1)
**Template Name:** Visible
**Bootstrap Version:** 5.3.8

---

## Section 1: The &lt;head&gt;
* **External CSS:** 
    - Bootstrap 5
    - Bootstrap Icons
    - AOS (Animate on Scroll)
    - Swiper
    - GLightbox
    - Google Fonts (Roboto, Mukta, Abel)
* **Custom CSS:** `p0/assets/css/main.css`

## Section 2: Site Inventory (Top Half)

### 1. The Navigation/Menu
* **Line Numbers:** 
    - Lines 41-80
* **Top-Level Classes:** 
    - `header`
    - `d-flex`
    - `align-items-center`
    - `position-relative` 
* **Research:** What do these top-level classes do to the menu's layout?
    - `header`: controls the overall appearance of the nav bar
    - `d-flex`: makes the header a flexbox container so the logo and nav sit side by side
    - `align-items-center`: vertically centers the logo and nav
    - `position-relative`: allows the absolutely positioned child elements to be anchored to the header

### 2. The Logo/Branding
* **Line Numbers:** 
    - Lines 44-48
* **Top-Level Classes:** 
    - `logo`: handles the sizing and spacing
    - `d-flex`: makes the logo image and text sit side by side
    - `align-items-center`: vertically centers the logo image and text
* **Research:** How is the logo positioned or styled?
    - The logo is positioned in the upper left corner of the page next to the text

### 3. Hero
* **Line Numbers:** 
    - Lines 85-141
* **Top-Level Classes:** 
    - `hero`: controls the large background, min-height, and layout of the landing area
    - `section`: applies consistent top and bottom padding across all sections
* **Research:** What defines the height, background, or alignment here?
    - The height, background, and alignment are defined in the `.hero` class in the main.css

### 4. About
* **Line Numbers:** 
    - Lines 144-215
* **Top-Level Classes:** 
    - `about`: handles the layout and spacing of the about section
    - `section`: applies consistent top and bottom padding across all sections
    - `light-background`: applies a soft off-white background
* **Research:** How does the template handle the container or spacing here?
    - The About section uses Bootstrap's standard `.container` class and there is a `.container` div for both the section title and content. The outter spacing has 60px of room on the top and bottom, and the inside of the section uses a `col-lg-6` grid and `gy-5` gap. 

## Section 3: Site Inventory (Bottom Half)

### Portfolio
* **Line Numbers:** Lines 855-988
* **Top-Level Classes:** 
    - `portfolio`
    - `section`
* **Research:** What do these classes do to this section's layout?
    - `portfolio`: controls the sidebar layout and image grid
    - `section`: handles the padding

### Contact
* **Line Numbers:** Lines 1412-1526
* **Top-Level Classes:** 
    - `contact`
    - `section`
* **Research:** How does the template handle the layout here?
    - The contact section has a custom max-width and a two-column split that uses CSS Grid instead of Bootstrap. On mobile it stacks into a single column, and on desktop it splits into a 38/62 uneven split. 

### The Footer
* **Line Numbers:** Lines 1530-1592
* **Top-Level Classes:** 
    - `footer`
* **Research:** How is this section styled compared to the rest of the site?
    - The footer section differs from the rest of the site because it doesn't use the `section` class. It has it's own top and bottom padding.
    
## Section 4: The Scripts
* **Vendor JS Files:**: Lines 1601-1608
    - Bootstrap: Line 1601
    - AOS (Animate on Scroll): Line 1603
    - Swiper: Line 1607
* **Main JS File:** Line 1611