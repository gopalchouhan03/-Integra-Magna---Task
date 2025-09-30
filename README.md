# -Integra-Magna---Task

# Integra Magna - Technical Assignment 

##  My Approach
- **Navbar**:  
  I created a navigation bar using semantic `<nav>` with a logo on the left and navigation links + signup/login options on the right. The layout is managed using **CSS Grid** instead of flexbox. I added a divider (`|`) and a hover effect on links for better interactivity.  

- **Hero Section**:  
  The hero section is divided into two parts:  
  - **Left Side**: Contains the main title (“Unlock The Digital Renaissance”), a description, and three NFT cards (Bear, Lion, Cats) with images, artist names, and prices. I used **CSS Grid** to align the cards and `clamp()` for responsive typography.  
  - **Right Side**: Includes a start button, a floating rock image, a hand sculpture, and a barcode card. These elements add visual depth and were positioned with CSS Grid for responsiveness.  

- **Footer**:  
  The footer contains navigation links separated by **star icons**. I used grid/inline styling to ensure spacing and alignment. The footer is designed to adapt across devices using media queries.  

---

##  What I Struggled With
- Getting the **grid alignment** right across mobile, tablet, and desktop breakpoints.  
- Positioning elements in the hero right section (floating rock and hand sculpture) so they look natural across screen sizes.  
- Ensuring the **footer’s star dividers** aligned properly with text without breaking responsiveness.  

---

##  Known Issues
- Navbar may overlap if too many links are added on very small screens.  
- On very narrow mobile devices (<320px), the NFT cards may stack in a way that feels crowded.  
- The footer’s spacing might look slightly inconsistent in some browsers due to inline image sizing.  

---

##  Future Improvements
- Add a **dark/light mode toggle** with smooth transitions.  
- Enhance hover animations (e.g., NFT cards scaling slightly with shadow).  
- Improve **accessibility** with ARIA roles and keyboard navigation.  

---

## Technologies Used
- **HTML5** for structure  
- **CSS3** with CSS Grid and Media Queries for layout and responsiveness  
- **Clamp units** for fluid typography  
- **Custom images/resources** provided for NFT cards and footer icons  

---

##  How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/gopalchouhan03/-Integra-Magna---Task.git
