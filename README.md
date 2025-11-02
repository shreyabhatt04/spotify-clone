# 🎵 Spotify Web Player Clone

A responsive and visually rich clone of the Spotify Web Player interface built using HTML and CSS. This project replicates the layout and design of Spotify’s desktop web player, including sidebar navigation, music cards, and a fixed music player footer.

## 🚀 Features

- Sidebar navigation with Home, Search, and Library options
- Dynamic card sections: Recently Played, Trending Near You, Featured Charts
- Sticky top navigation bar with install and profile options
- Fixed bottom music player with album info, playback controls, and volume slider
- Responsive design with media queries for smaller screens

## 🧰 Technologies Used

| Technology | Purpose |
|-----------|---------|
| HTML5     | Structure and layout |
| CSS3      | Styling and responsiveness |
| Font Awesome | Icons for navigation and controls |
| Google Fonts | Typography (Montserrat, Poppins, Roboto) |

## 📁 Project Structure
spotify-web-player/ ├── index.html ├── css_project.css ├── assets/ │   ├── logo.png │   ├── library_icon.png │   ├── card1img.jpeg │   ├── card2img.jpeg │   ├── card3img.jpeg │   ├── card4img.jpeg │   ├── card5img.jpeg │   ├── card6img.jpeg │   ├── backward_icon.png │   ├── forward_icon.png │   ├── player_icon1.png │   ├── player_icon2.png │   ├── player_icon3.png │   ├── player_icon4.png │   ├── player_icon5.png

## 📦 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/spotify-web-player.git

2. Navigate to the project folder:
cd spotify-web-player

3. Open index.html in your browser:
- You can use Live Server (VS Code extension) or simply double-click the file.

🎨 Customization- To change fonts, update the Google Fonts link in <head> and modify font-family in css_project.css.
- To replace music cards, update the image paths and text inside .cards-container sections.
- To add interactivity (e.g., play/pause), integrate JavaScript or frameworks like React.

📱 Responsive Design- The layout adapts to screen widths below 1000px by hiding certain elements using the .hide class.
- You can extend responsiveness using additional media queries in css_project.css.

📌 Notes- This is a front-end-only static project. No backend or music streaming functionality is included.
- All images and icons are locally stored in the assets/ folder for offline use.

📄 License
- This project is for educational and personal use only. It is not affiliated with or endorsed by Spotify.
