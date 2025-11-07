
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

### **Responsiveness**


### **Accessibility**

---

## ⚙️ Deployment



Example:  
`https://github.com/irinaancuta1785/beyond-the-cover`

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

