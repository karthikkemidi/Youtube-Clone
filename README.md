# YouTube Clone 🎥

A pixel-perfect recreation of YouTube's homepage interface built with vanilla HTML and CSS. This project demonstrates proficiency in modern CSS layout techniques including Flexbox, CSS Grid, and responsive design principles.

![YouTube Clone](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## 🎯 Project Overview

This project is a front-end clone of YouTube's user interface, focusing on:
- Accurate UI/UX replication
- Clean, semantic HTML structure
- Advanced CSS layout techniques
- Responsive design patterns

## ✨ Features Implemented

### Header Section
- Fixed navigation header with three-section layout (left, middle, right)
- YouTube logo and hamburger menu
- Functional search bar with search and voice search buttons
- Interactive tooltips on hover
- User profile section with notification badge
- Upload and apps icons

### Sidebar Navigation
- Fixed sidebar with navigation links
- Icons for Home, Explore, Subscriptions, Originals, YouTube Music, and Library
- Clean vertical layout using Flexbox

### Video Grid
- Responsive CSS Grid layout for video thumbnails
- 6 video cards with:
  - Video thumbnails with duration overlay
  - Channel profile pictures
  - Video titles, author names, and statistics
  - Proper spacing and alignment

### UI Components
- Hover effects and transitions
- Position-based tooltips
- Notification counters
- Custom styling matching YouTube's design language

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced styling and layouts
  - CSS Grid for responsive video grid
  - Flexbox for header and sidebar layouts
  - Position properties (fixed, absolute, relative)
  - Custom properties and transitions
- **Google Fonts**: Roboto font family (400, 500, 700 weights)

## 📁 Project Structure

```
Youtube-Clone/
├── youtube.html           
├── flexbox.html          
├── grid.html             
├── position.html         
├── styles/
│   ├── general.css       
│   ├── header.css        
│   ├── sidebar.css       
│   └── video.css        
├── thumbnails/           
├── channel-pictures/     
├── icons/                
└── intro-to-html/        
```

## 🎓 Learning Outcomes

This project helped develop skills in:

1. **CSS Grid**: Creating responsive, multi-column layouts
2. **Flexbox**: Building flexible navigation and component layouts
3. **CSS Positioning**: Implementing fixed headers, absolute tooltips, and overlays
4. **Component Architecture**: Organizing styles into modular CSS files
5. **UI/UX Attention to Detail**: Replicating a professional interface accurately
6. **Semantic HTML**: Writing clean, accessible markup

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, or Edge)
- Basic understanding of HTML and CSS

### Installation

1. Clone the repository:
```bash
git clone https://github.com/karthikkemidi/Youtube-Clone.git
```

2. Navigate to the project directory:
```bash
cd Youtube-Clone
```

3. Open `youtube.html` in your browser:
```bash
# On macOS
open youtube.html

# On Linux
xdg-open youtube.html

# On Windows
start youtube.html
```

Or simply double-click the `youtube.html` file to open it in your default browser.


## 🎯 Key CSS Techniques

### CSS Grid Implementation
```css
.video-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 16px;
}
```

### Flexbox for Header
```css
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: fixed;
}
```

### Tooltip Positioning
```css
.tooltip {
  position: absolute;
  /* Positioned relative to parent container */
}
```



## 📝 Future Enhancements

- [ ] Add JavaScript for interactive search functionality
- [ ] Implement video filtering and sorting
- [ ] Add dark mode toggle
- [ ] Make fully responsive for mobile devices
- [ ] Add video player page
- [ ] Implement comment section
- [ ] Add user authentication UI

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 👨‍💻 Author

**Karthik Kemidi**
- GitHub: [@karthikkemidi](https://github.com/karthikkemidi)
- LinkedIn: [Connect with me](https://www.linkedin.com/in/karthik-kemidi-b4924a25a/)

## 📄 License

This project is for educational purposes. YouTube and its logo are trademarks of Google LLC.

## 🙏 Acknowledgments

- YouTube for the original design inspiration
- Google Fonts for the Roboto font family
- SuperSimpleDev for educational content and guidance

---

⭐ Star this repository if you found it helpful!
