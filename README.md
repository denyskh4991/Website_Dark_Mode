# Portfolio Website With Dark Mode

<p>The **Portfolio Website With Dark Mode** is a sleek, responsive portfolio page designed to showcase an individual's work. It uses HTML, CSS, and JavaScript to provide an interactive and aesthetically pleasing user experience, with a built-in dark mode toggle.</p>
<h2>Key Features</h2>
<h3>Navigation Bar</h3>
<p>The page features a navigation bar with links to different sections, including "Home," "About," "Portfolio," "Services," and "Hire Me." A logo and dark mode toggle button (moon/sun icon) are also part of the navigation.</p>
<h3>Hero Section</h3>
<p>The hero section introduces the user with a bold headline, an introductory paragraph, and a "Download CV" button. It also displays a graphical element with layered images, creating a modern, professional look.</p>
<h4>Visual Presentation</h4>
<p>The hero section features a background pattern and a profile image with hover animations. The text is styled with a clean, professional layout, and a special highlight is applied to the user's name for emphasis.</p>
<h3>Social Media Integration</h3>
<p>Social media icons, including LinkedIn, Behance, and Dribbble, are prominently featured, allowing users to connect via these platforms. Hover effects are applied to each icon, enhancing user engagement.</p>
<h3>Dark Mode Toggle</h3>
<p>A key feature is the dark mode toggle button, which changes the theme from light to dark. When activated, the primary and secondary colors are inverted, providing a night-friendly interface. The button icon switches between a sun and moon depending on the active theme.</p>
<h2>Technical Overview</h2>
<h3>HTML Structure</h3>
<p>The HTML structure includes a navigation bar, hero section, and social media links. The page is designed to be simple yet effective, making use of semantic elements like `nav`, `ul`, and `div` for organization.</p>
<h3>CSS Styling</h3>
<p>The CSS leverages custom properties (CSS variables) for easy theme switching. Layouts are created using flexbox, ensuring that elements are responsive across devices. Hover animations are applied to images and social icons for interactivity.</p>
<h4>Theme Customization</h4>
<p>The dark mode feature is controlled using a class toggle (`dark-theme`), and the transition between themes is smooth and immediate. Colors, fonts, and background images adjust dynamically to the theme selection.</p>
<h3>JavaScript Functionality</h3>
<p>JavaScript is used to handle the dark mode functionality. By toggling a class on the `body` element, the page switches between dark and light themes, while also updating the icon to reflect the current mode.</p>

    let icon = document.getElementById("icon");
    
    icon.onclick = function() {
        document.body.classList.toggle("dark-theme");
        if (document.body.classList.contains("dark-theme")) {
            icon.src = "images/sun.png";
        } else {
            icon.src = "images/moon.png";
        }
    };

<h2>Conclusion</h2>
<p>The **Portfolio Website With Dark Mode** offers a visually appealing and functional design to showcase personal projects. With a responsive layout, dark mode toggle, and social media integration, it creates a professional digital presence that is suitable for any web portfolio.</p>
