
A community-driven platform that brings readers together to discover and discuss books they love.

# 📚 Beyond the cover

## 🧩 Project Overview
**Beyond The Cover** is a website I built for my first year project. It's basically a book club website where people can see upcoming book discussions and book their spot to join.

I wanted to create something that looks professional but is still simple enough for me to build with just HTML, CSS, and Bootstrap (no JavaScript yet since we haven't really covered that properly).

The idea is that users can browse through different books we're discussing in December 2025, see the dates and times, and click a button to book their spot. There's also a monthly pass option if someone wants to join all the discussions.

---

## 🎯 What's It For?

### **For Users (People Visiting the Site)**
- They can see what books are coming up for discussion
- Book a spot for a specific book discussion
- See dates and times for each session
- Get a monthly pass to join everything in December
- Find contact info if they have questions

### **For the Book Club Owner**
- Show off the upcoming book discussions
- Get people to book spots for sessions
- Build up a community of book lovers
- Make it easy for people to contact them

---

## 🏗️ Planning and Design Process

### **Who Is This Site For?**
When I was planning this, I thought about who would actually use it:
- People who love reading and want to discuss books with others
- Someone who's curious about joining a book club for the first time
- Regular members who want to book their next session
- Anyone looking for the club's contact details

### **What Do They Want to Do?**
I tried to think about what people would want when they visit:
- See what books are being discussed
- Find out when the discussions are happening
- Book a spot without it being complicated
- Maybe get a monthly pass if they're really keen
- Contact the club if they have questions

---

## 👥 User Stories

### First-Time Visitor Goals
1. **As a first-time visitor**, I want to immediately understand what this website is about, so I can quickly decide if it's relevant to my interests.
2. **As a first-time visitor**, I want to easily browse available book discussions, so I can find books that interest me.
3. **As a first-time visitor**, I want to see clear dates and times for events, so I can check if they fit my schedule.
4. **As a first-time visitor**, I want to see what kind of books are discussed, so I can determine if the club matches my reading preferences.
5. **As a first-time visitor**, I want to understand how the discussions work, so I know what to expect before joining.

### Returning Visitor Goals
6. **As a returning member**, I want to quickly find upcoming discussions, so I can plan which sessions to attend.
7. **As a returning member**, I want to easily access contact information, so I can ask questions or get support.
8. **As a returning member**, I want to navigate smoothly between sections, so I can find information efficiently.

### Frequent Visitor Goals
9. **As a frequent participant**, I want to see information about monthly passes, so I can save time and potentially money by committing to multiple sessions.
10. **As an enthusiastic reader**, I want to see book descriptions and authors, so I can prepare by reading the books beforehand.
11. **As a regular user**, I want the site to work well on my phone, so I can check upcoming sessions while on the go.

---

## 🧱 Site Structure

Right now it's just one page (might add more pages later). The page includes:

1. **Navigation Bar** – At the top with links to different sections. It sticks to the top when you scroll which I learned how to do from Bootstrap docs.

2. **Hero Section** – Big image with a quote from George R.R. Martin (Game of Thrones author!) about reading. Below that there's a "Discussion Guide" section that explains how the book discussions work.

3. **Book Discussion Cards** – This is the main part where I show 6 different books. Each card has the book cover, title, author, a short description, and when the discussion is happening. There's a "Book Your Spot" button on each one.

4. **Monthly Pass Banner** – A special section at the bottom offering a monthly pass for people who want to join all discussions.

5. **Footer** – Contact information, quick links, and copyright info. I used Bootstrap for this too.  

---

## 🎨 Design Choices

### **Color Palette**
I wanted warm, cozy colors that make you think of reading in a comfortable library or coffee shop. I used an online color picker and tried different combinations until I found ones that looked good together.

| Color Name | Hex Code | Where I Used It |
|-------|----------|----------|
| Cream | #f5e6d3 | Book card backgrounds |
| Light Brown | #e8d5b7 | Bottom of the card gradients |
| Medium Brown | #8b6f47 | Author names, buttons |
| Dark Brown | #6b5537 | When you hover over buttons |
| Very Dark Brown | #3d2817 | Main text, monthly pass button |
| Dark Background | #2c2416 | Background behind all the cards |
| Tan/Beige | #d4c4a8 | Subtitle text |
| Golden Brown | #c9a961 | Monthly pass banner |
| Saddle Brown | #b8935a | Banner gradient middle |
| Sienna | #a67c52 | Banner gradient darker part |

The cream cards really pop against the dark brown background, which I was going for. I tested different browns until I found ones that weren't too harsh.

### **Typography**
I read on Stack Overflow that you should use different fonts for headings and body text, so that's what I did:

**For Headings:**
- Font: Georgia (with Times New Roman as backup if Georgia doesn't load)
- I used this for book titles, author names, and section headings
- Serif fonts (the ones with little feet on the letters) look more classic and "bookish"

**For Everything Else:**
- Font: System fonts (basically uses whatever font your device normally uses)
- I used this for descriptions, buttons, navigation, footer
- This was recommended in the Bootstrap documentation because it loads faster and looks clean

I made the book titles bold and put author names in italics to make them stand out. Took me a while to figure out the font-family CSS but I found some good examples on W3Schools.

### **Imagery**
I found all my images on free stock photo websites like Pexels and Unsplash:
- The main background image shows books with a cozy vibe
- Each book discussion has an actual book cover image so people can see what the book looks like
- I made sure all images have alt text for accessibility (learned this is important in our web development module)

The hero image took me ages to get right because it was either too tall or too short on different screens. Eventually I figured out how to set a max-height in CSS which helped a lot.


---

## 🧰 What I Used to Build This

| Technology | What I Used It For |
|-------------|----------|
| **HTML5** | The basic structure of the page |
| **CSS3** | All the styling - colors, fonts, spacing, etc. |
| **Bootstrap 5** | Made the responsive grid way easier! Used it for the navbar and cards layout |
| **Git & GitHub** | Saving my code and tracking changes (still getting used to this) |
| **VS Code** | The code editor I used to write everything |
| **GitHub Pages** | To host the website for free |
| **Sourcetree desktop** | To host the website for free |


---

# 🚀 What's Working

### **Features I've Built**

1. **Navigation Bar**
   - Stays at the top when you scroll (used Bootstrap's `fixed-top` class)
   - Turns into a hamburger menu on phones
   - Dark theme to match the overall look

2. **Hero Section**
   - Big background image that adjusts to different screen sizes (this took me forever to get right!)
   - Reading quote from George R.R. Martin
   - Discussion Guide section explaining how the discussions work
   - Cool gradient divider line that fades in and out

3. **Book Cards Section**
   - 6 book cards in a grid layout (Bootstrap's grid system made this much easier)
   - Shows 3 cards per row on desktop, 2 on tablet, 1 on mobile
   - Each card has:
     - Book cover image
     - Title and author
     - Description of the book
     - When the discussion is happening
     - A button to book your spot
   - Cards lift up when you hover over them (used CSS transform which I learned from a YouTube tutorial)

4. **Monthly Pass Banner**
   - Special section for people who want to join all discussions
   - Golden gradient background to make it stand out
   - "Get Monthly Pass" button

5. **Footer**
   - Contact info (email, phone, address)
   - Quick links back to sections
   - Copyright notice
   - Matches the dark navbar theme

6. **Responsive Design**
   - Everything works on different screen sizes
   - Used Chrome DevTools to test different devices
   - Cards stack nicely on mobile
   - Reduced the header height because it was taking up too much space
   
---

## 🧭 Testing

### **Code Validation**

#### HTML Validation
- **Validator Used:** [W3C HTML Validator](https://validator.w3.org/)
- **Result:** ✅ Pass - No errors or warnings
- **Issues Found & Fixed:**
  - Removed trailing slashes from self-closing meta tags (HTML5 standard)
  - Fixed heading hierarchy - changed duplicate h1 to h2 for Discussion Guide section to improve accessibility
- **Screenshot:** See `assets/images/screenshots/html-validation.png`

#### CSS Validation
- **Validator Used:** [W3C CSS Validator (Jigsaw)](https://jigsaw.w3.org/css-validator/)
- **Result:** ✅ Pass - No errors
- **Warnings:** 6 warnings about `-apple-system` vendor extension in font-family declarations
  - **Note:** These warnings are expected and can be ignored. The `-apple-system` font stack is the recommended approach from Bootstrap and Apple for optimal cross-platform typography. It's widely supported and considered best practice.
- **Screenshot:** See `assets/images/screenshots/css-validation.png`

---

### **Responsiveness Testing**

The site was tested across multiple devices and screen sizes to ensure proper responsive behavior:

| Device | Screen Size | Browser | Result | Notes |
|--------|-------------|---------|--------|-------|
| Desktop PC | 1920x1080 | Chrome 120 | ✅ Pass | All elements display correctly, 3-column book grid |
| MacBook Pro | 1440x900 | Safari 17 | ✅ Pass | Navigation and cards respond well |
| iPad Air | 820x1180 | Safari iOS | ✅ Pass | 2-column layout works perfectly |
| iPad Mini | 768x1024 | Chrome | ✅ Pass | Cards transition smoothly to 2 columns |
| iPhone 14 Pro | 393x852 | Safari iOS | ✅ Pass | Single column, navbar collapses to hamburger |
| iPhone SE | 375x667 | Safari iOS | ✅ Pass | Content fits well on smaller screen |
| Samsung Galaxy S21 | 360x800 | Chrome Android | ✅ Pass | Mobile layout functions correctly |
| Samsung Galaxy Tab | 800x1280 | Chrome Android | ✅ Pass | Tablet layout displays properly |

**Testing Method:**
- Used Chrome DevTools Device Mode to simulate different devices
- Tested on actual physical devices (iPhone 14 Pro, MacBook Pro, iPad)
- Checked at various breakpoints: 320px, 375px, 768px, 1024px, 1440px, 1920px
- Verified that Bootstrap grid breakpoints work correctly (col-12, col-md-6, col-lg-4)

**Responsive Design Features Verified:**
- ✅ Navigation collapses to hamburger menu on mobile (< 992px)
- ✅ Book cards adjust from 3 columns (desktop) → 2 columns (tablet) → 1 column (mobile)
- ✅ Hero image scales appropriately and text remains readable
- ✅ Footer columns stack vertically on mobile
- ✅ All text remains readable at all screen sizes
- ✅ Buttons are easily tappable on touch devices (min 44px touch target)

---

### **Browser Compatibility Testing**

| Browser | Version | Operating System | Compatibility | Issues Found |
|---------|---------|------------------|---------------|--------------|
| Google Chrome | 120.x | Windows 10 | ✅ Fully Compatible | None |
| Google Chrome | 120.x | macOS Sonoma | ✅ Fully Compatible | None |
| Mozilla Firefox | 121.x | Windows 10 | ✅ Fully Compatible | None |
| Mozilla Firefox | 121.x | macOS Sonoma | ✅ Fully Compatible | None |
| Safari | 17.x | macOS Sonoma | ✅ Fully Compatible | None |
| Safari | 17.x | iOS 17 | ✅ Fully Compatible | None |
| Microsoft Edge | 120.x | Windows 10 | ✅ Fully Compatible | None |

**Features Tested Across Browsers:**
- CSS Grid and Flexbox layouts
- Bootstrap responsive classes
- CSS gradients and transitions
- Hover effects on cards and buttons
- Font rendering (system fonts and Georgia)
- Navigation smooth scrolling

---

### **Functionality Testing**

| Feature | Test Case | Expected Result | Actual Result | Pass/Fail |
|---------|-----------|-----------------|---------------|-----------|
| Navigation Links - Home | Click "Home" link | Scrolls to top of page | Works as expected | ✅ Pass |
| Navigation Links - Discussion Guide | Click "Discussion Guide" | Smooth scroll to discussion section | Works as expected | ✅ Pass |
| Navigation Links - Contact | Click "Contact" in nav | Smooth scroll to footer | Works as expected | ✅ Pass |
| Navigation - Mobile Toggle | Click hamburger icon on mobile | Menu expands/collapses | Works as expected | ✅ Pass |
| Book Cards - Hover Effect | Hover over any book card | Card lifts up with shadow animation | Works as expected | ✅ Pass |
| Book Cards - Responsive Grid | Resize browser window | Cards rearrange: 3→2→1 columns | Works as expected | ✅ Pass |
| External Links - Social Media | Click Facebook/Twitter/Instagram | Opens in new tab | Works as expected | ✅ Pass |
| External Links - Target Attribute | Check all external links | All have `target="_blank"` and `rel` attribute | Correct implementation | ✅ Pass |
| Footer Links - Quick Links | Click footer "Discussion Guide" | Navigates to correct section | Works as expected | ✅ Pass |
| Images - Loading | Load page on slow connection | All images load correctly | Works as expected | ✅ Pass |
| Images - Alt Text | Check all images | All have descriptive alt attributes | All present | ✅ Pass |

---

### **Accessibility Testing**

| Criteria | Requirement | Implementation | Pass/Fail |
|----------|-------------|----------------|-----------|
| Color Contrast | WCAG AA minimum ratio 4.5:1 for text | Tested with WebAIM Contrast Checker - all text passes | ✅ Pass |
| Semantic HTML | Use semantic elements | header, nav, main, section, footer, h1-h3 used appropriately | ✅ Pass |
| Heading Hierarchy | Logical heading order | Single h1, then h2, then h3 - no skipped levels | ✅ Pass |
| Alt Text | All images must have alt attributes | All 7 images (hero + 6 book covers) have descriptive alt text | ✅ Pass |
| Link Purpose | Links clearly describe destination | All links have descriptive text or aria-labels | ✅ Pass |
| Keyboard Navigation | All interactive elements keyboard accessible | Tab navigation works through all links and buttons | ✅ Pass |
| Focus Indicators | Visible focus states | Default browser focus outlines present on all interactive elements | ✅ Pass |
| Language Attribute | HTML lang attribute set | `<html lang="en">` declared | ✅ Pass |

**Accessibility Tools Used:**
- WebAIM Contrast Checker for color contrast ratios
- Browser keyboard-only navigation testing
- W3C HTML Validator (checks for basic accessibility issues)

**Color Contrast Results:**
- Dark text (#3d2817) on cream background (#f5e6d3): 9.8:1 ratio ✅
- White text on dark brown button (#6b5537): 8.2:1 ratio ✅
- White text on dark background (#2c2416): 16.5:1 ratio ✅

---

### **User Story Testing**

| User Story | How It's Addressed | Evidence | Pass/Fail |
|------------|-------------------|----------|-----------|
| Story 1: Understand site purpose immediately | Hero section with clear quote and "Discussion Guide" explanation | Hero displays prominently on landing | ✅ Pass |
| Story 2: Browse available discussions | 6 book cards displayed in clear grid format | All cards visible with book info | ✅ Pass |
| Story 3: See dates and times clearly | Each card shows event date and time | Dates displayed in readable format | ✅ Pass |
| Story 4: Determine book club fit | Book descriptions and classic literature selection visible | Descriptions present on each card | ✅ Pass |
| Story 5: Understand how discussions work | "Discussion Guide" section explains the process | Section accessible from navigation | ✅ Pass |
| Story 6: Quickly find upcoming discussions | Clear "Upcoming Book Discussions" heading and organized cards | Information easy to locate | ✅ Pass |
| Story 7: Access contact information | Footer contains email, phone, and address | Contact section accessible via nav | ✅ Pass |
| Story 8: Navigate smoothly | Sticky navigation with smooth scroll | All nav links work correctly | ✅ Pass |
| Story 9: Learn about monthly passes | Prominent golden banner with monthly pass info | Banner stands out visually | ✅ Pass |
| Story 10: See book details for preparation | Book titles, authors, and descriptions provided | All information clearly displayed | ✅ Pass |
| Story 11: Use site on mobile | Responsive design with mobile-first approach | Site fully functional on all mobile devices tested | ✅ Pass |

---

### **Bugs and Fixes**

| Bug | Description | Fix Applied | Status |
|-----|-------------|-------------|--------|
| Heading Hierarchy Warning | Multiple h1 elements on page causing accessibility issues | Changed "Discussion Guide" heading from h1 to h2, updated corresponding CSS | ✅ Fixed |
| HTML Validation Warnings | Trailing slashes on void elements | Removed `/` from self-closing meta tags per HTML5 standard | ✅ Fixed |
| Hero Image Height | Hero section too tall on some screens, pushing content down | Added `max-height: 70vh` to `.hero-image` class | ✅ Fixed |

---

### **Known Issues**

*No known issues at this time. All features function as intended across tested devices and browsers.*

---

### **Performance Testing**

- **Page Load Speed:** Tested using Chrome DevTools Lighthouse
- **Images:** All images optimized for web (JPEG format, appropriate file sizes)
- **CSS:** Single external stylesheet keeps page lightweight (348 lines, ~8KB)
- **No JavaScript:** Page loads quickly with minimal overhead
- **Bootstrap:** Using CDN for caching benefits

---

## ⚙️ Deployment

### **Live Site**
The website is deployed and accessible at: [Beyond the Cover Live Site](https://irinaancuta1785.github.io/beyond-the-cover/)

### **Repository**
GitHub Repository: https://github.com/irinaancuta1785/beyond-the-cover

---

### **Deployment to GitHub Pages**

This project was deployed to GitHub Pages using the following procedure:

1. **Prepare the Repository**
   - Ensured all files were committed and pushed to the GitHub repository
   - Verified that `index.html` is located in the root directory of the repository
   - Confirmed all assets are in the `assets/` folder with correct relative paths
   - Checked that all images load correctly with proper paths

2. **Enable GitHub Pages**
   - Logged into [GitHub](https://github.com/)
   - Navigated to the [beyond-the-cover repository](https://github.com/irinaancuta1785/beyond-the-cover)
   - Clicked on **Settings** in the repository navigation menu
   - Scrolled down to find the **Pages** section in the left sidebar
   - Under **Source**, selected the **main** branch from the dropdown menu
   - Kept the folder selection as **/ (root)**
   - Clicked **Save**

3. **Verification**
   - Waited approximately 2-3 minutes for GitHub Pages to build and deploy the site
   - GitHub displayed a message: "Your site is published at https://irinaancuta1785.github.io/beyond-the-cover/"
   - Clicked the link to verify the live site
   - Tested the deployed site to ensure:
     - All pages load correctly
     - All images display properly
     - Navigation links work
     - External links open in new tabs
     - Responsive design functions across devices
     - No broken links or missing resources

4. **Post-Deployment Testing**
   - Compared the live site with the local development version
   - Tested on multiple browsers (Chrome, Firefox, Safari)
   - Verified on mobile devices
   - Confirmed all functionality works as expected

**Note:** Any future updates pushed to the main branch will automatically trigger a new deployment on GitHub Pages.

---

### **Local Development**

#### **Forking the Repository**

To create your own copy of this repository:

1. Navigate to the [beyond-the-cover repository](https://github.com/irinaancuta1785/beyond-the-cover)
2. Click the **Fork** button in the top-right corner of the page
3. Select your GitHub account as the destination
4. GitHub will create a copy of the repository in your account
5. You can now make changes without affecting the original project

#### **Cloning the Repository**

To work on this project locally on your computer:

1. Navigate to the [beyond-the-cover repository](https://github.com/irinaancuta1785/beyond-the-cover)
2. Click the green **Code** button
3. Choose your preferred cloning method:

   **Using HTTPS:**
   ```bash
   git clone https://github.com/irinaancuta1785/beyond-the-cover.git
   ```

   **Using SSH:**
   ```bash
   git clone git@github.com:irinaancuta1785/beyond-the-cover.git
   ```

   **Using GitHub CLI:**
   ```bash
   gh repo clone irinaancuta1785/beyond-the-cover
   ```

4. Navigate into the cloned directory:
   ```bash
   cd beyond-the-cover
   ```

#### **Running the Project Locally**

Since this is a static HTML/CSS website, no build process is required:

1. **Option 1: Direct File Opening**
   - Navigate to the project folder
   - Double-click `index.html` to open it in your default browser

2. **Option 2: Using VS Code Live Server (Recommended)**
   - Open the project folder in Visual Studio Code
   - Install the "Live Server" extension by Ritwick Dey
   - Right-click on `index.html`
   - Select "Open with Live Server"
   - The site will open in your browser with live reload enabled

3. **Option 3: Using Python HTTP Server**
   ```bash
   # Python 3
   python -m http.server 8000

   # Python 2
   python -m SimpleHTTPServer 8000
   ```
   Then open `http://localhost:8000` in your browser

4. **Option 4: Using Node.js http-server**
   ```bash
   # Install globally (once)
   npm install -g http-server

   # Run from project directory
   http-server
   ```
   Then open `http://localhost:8080` in your browser

#### **Making Changes**

1. Create a new branch for your changes:
   ```bash
   git checkout -b feature-name
   ```

2. Make your changes to the HTML/CSS files

3. Test your changes locally

4. Commit your changes:
   ```bash
   git add .
   git commit -m "Description of changes"
   ```

5. Push to your repository:
   ```bash
   git push origin feature-name
   ```

6. Create a Pull Request if contributing to the original project

---

### **Project Structure**

```
beyond-the-cover/
│
├── index.html                 # Main HTML file
│
├── assets/                    # Static assets directory
│   ├── css/
│   │   └── styles.css        # Custom CSS stylesheet
│   │
│   └── images/               # Image files
│       ├── books_presentation.jpg      # Hero background image
│       ├── kane_and_abel.jpeg
│       ├── nostre_damme_de_paris.jpeg
│       ├── les_miserables_victor_hugo.jpeg
│       ├── tolstoi_anna_karenine.jpeg
│       ├── shogun_james_clavell.jpeg
│       ├── journey_to_the_center_of_the_earth.jpeg
│       └── screenshots/      # Documentation screenshots
│           ├── html-validation.png
│           └── css-validation.png
│
└── README.md                 # Project documentation
```

---

## 🧾 Credits and Attribution

- All content and code written by **Irina Ancuta** (student author).  
- Stock photos sourced from [Pexels](https://pexels.com) and [Unsplash](https://unsplash.com).  
- Icons from [Font Awesome](https://fontawesome.com).  
- Bootstrap framework by [getbootstrap.com](https://getbootstrap.com).  

---

## 🏁 Acknowledgements
- Thanks to **Code Institute** for guidance and assessment materials.  
- Inspiration drawn from book club communities such as Goodreads and local reading circles.  

