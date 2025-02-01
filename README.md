🍽️ Recipe Website - Nishi Dhaba

A simple Recipe Website built using HTML & CSS that showcases different recipes, their ingredients, preparation steps, and images, with an interactive "Click here to buy" feature.

📌 Features

Navigation Bar – Includes "Home," "Contact Us," and "About Us."

Recipe Sections – Each recipe includes:

Name

Ingredients

Step-by-step cooking instructions

Image with an overlay ("Click here to buy")

Fully Responsive – Optimized for different screen sizes.

Footer Section – Displays copyright information.

📂 File Structure

recipe-website/
├── index.html       # Main HTML file
├── style.css        # CSS file for styling
├── images/
│   ├── rasugulla.jpg  # Image for Rasugulla
│   ├── barfi.jpg      # Image for Barfi
├── README.md        # Documentation

🎨 CSS Styling Overview (style.css)

📌 Global Styles

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

📌 Container & Background

.container{
    height: 100vh;
    width:100vw;
    overflow-x: hidden;
    background-color: #e2e5e8;
    background-image: linear-gradient(98deg, #e2e5e8 0%, #ffffff 100%);
}

📌 Navigation Bar

.navcontainer{
    width:100vw;
    min-height: 80px;
    background-color: #3200e9;
    background-image: linear-gradient(160deg, #3200e9 0%, #8085d0 100%);
    display:flex;
    justify-content: center;
    align-items: center;
}

📌 Footer

.footerbox{
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    min-height:40px;
    background-color: #3200e9;
    background-image: linear-gradient(160deg, #3200e9 0%, #8085d0 100%);
}

📌 Image Overlay Effect

.rightbox .overlay{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(36, 34, 34, 0.713);
    border-radius: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0;
    transition: all 0.3s linear 0s;
}

.rightbox:hover .overlay{
    opacity: 1;
}

🚀 How to Run the Project

Clone or Download the Repository

git clone https://github.com/yourusername/recipe-website.git
cd recipe-website

Open in a Browser

Locate the index.html file.

Open it in Google Chrome, Firefox, or any browser.

Customize the Content

Open index.html in a text editor (VS Code, Sublime Text, Notepad++).

Modify recipes, ingredients, and images as needed.

Edit Styles (Optional)

Open style.css to modify the website’s look and feel.

🌎 Live Demo (Optional)

If hosted on GitHub Pages, Netlify, or Vercel, provide the link here:
🔗 Live Demo: https://yourusername.github.io/recipe-website

📜 License

This project is open-source under the MIT License. You are free to modify and use it for personal or commercial purposes.

👩‍💻 Author

Nishi Garg Passionate software engineer & food enthusiast.📧 
Email: nishigarg@2225@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/nishigarg25/💻 
GitHub: nishigarg1525

💡 Contributing

If you'd like to contribute:

Fork the repository.

Make improvements.

Submit a Pull Request. 🚀

