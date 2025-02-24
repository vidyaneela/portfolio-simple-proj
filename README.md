# Portfolio Website

## AIM 

The aim of this project is to create a personal portfolio website that highlights my skills, interests, and projects. The website includes two main pages: a **Home page** and a **Contact page**. The Home page showcases my projects and provides a brief description of my role and interests, while the Contact page allows visitors to get in touch with me.

## IMPLEMENTATION

### Home Page
- Displays:
  - My name ("Vidya Neela M")
  - My role as a **Web Developer**
  - A link to the **Contact page**
  - A brief description of myself and my interests
  - A list of projects showcasing my work in **web development** and **machine learning**.

### Contact Page
- Contains a form with fields for:
  - **Name**
  - **Email**
  - **Message**
- The form is intended for visitors to send messages or inquiries to me directly.

### Tech Stack
- **HTML**: For structuring the content of the web pages.
- **CSS**: For styling the web pages, making them visually appealing and responsive.

### Features
- **Navigation**: Easy navigation between the Home and Contact pages.
- **Social Media Links**: Direct links to my social media profiles (Instagram, LinkedIn) in the footer of both pages.
- **Responsive Design**: The layout is simple and adjusts well on different screen sizes.

### Setup Instructions
1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/portfolio.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd portfolio
    ```
3. **Open the HTML files** in your browser (`index.html` for the Home page, `contact form.html` for the Contact page).

### Files Structure
## Home Page:
<!DOCTYPE html>
<html>

<head>
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Young+Serif&display=swap" rel="stylesheet">
</head>

<body>
    <div class="container">
        <div class="section-one">
            <h1 class="section-one__name">VIDYA NEELA M</h1>
            <p class="section-one__role">Web Developer</p>
            <a class="section-one__contact" href="contact form.html">Contact me</a>
        </div>
        <div class="section-two">
            <h1 class="section-two__title">ABOUT ME</h1>
            <p class="section-two__desc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi officiis, quasi
                earum architecto reiciendis,
                itaque asperiores accusantium maxime ipsam consequatur, dicta quisquam voluptates nisi nobis! Ipsa,
                praesentium
                unde voluptates iure eveniet ipsum cumque. Soluta vitae quos repellat unde ut perspiciatis obcaecati
                officia
                ea!
                Consequuntur eaque unde quam atque quo sint magni omnis voluptatum quis deleniti doloribus enim facere a
                maxime
                eius repellendus, saepe perferendis aliquam culpa veritatis illo neque sit! Molestias earum odio
                provident
                ipsam
                culpa magnam sint sed numquam et nisi, delectus distinctio fugit reiciendis recusandae voluptatem
                temporibus.
                Nobis amet fuga quas explicabo, similique incidunt doloremque, voluptas modi ea nesciunt quidem
                obcaecati
                repellat, cupiditate voluptate quis accusamus</p>
        </div>
        <div class="section-three">
            <h2 class="section-three__int">INTEREST</h2>
            <ul class="section-three__desc">
                <li>Web Developer</li>
                <li>Python</li>
            </ul>
        </div>
        <div class="section-four">
            <h2 class="section-four__proj">PROJECTS</h2>
            <ul class="section-four__desc">
                <li>
                    <h2>solar power prediction using machine learning</h2>
                    <p>predicted solar power generation by using linear regression and other
                        machine learning algorihtms
                    </p>
                </li>
                <li>
                    <h2>Predicting bloodgroup using machine learning</h2>
                    <p>predicted bloodgroup by using labeled dataset of various fingerprints
                        using deep learning model
                    </p>
                </li>
            </ul>
        </div>
        <div class="section-five">
            <h4 class="section-five__title">Social media
                <a href="https://www.instagram.com/theagneljohn/?hl=en" target="_blank">Intagram</a>
                <a href="https://www.linkedin.com/in/vidya-neela-m-280112236/" target="_blank">linkedin</a>
            </h4>
            <p class="section-five__desc">© Vidya Neela M</p>
        </div>
    </div>
</body>

</html>

## Contact Page:
<!DOCTYPE html>
<html>

<head>
    <title>Contact form</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Young+Serif&display=swap" rel="stylesheet">
</head>

<body>
    <div class="container">
        <div class="section-one">
            <h1 class="section-one__name">VIDYA NEELA M</h1>
            <p class="section-one__role">Web Developer</p>
            <a class="section-one__contact" href="index.html">Home</a>
        </div>
        <div class="contact-form">
            <form>
                <table>
                    <tr>
                        <td>Name: </td>
                        <td><input type="text" placeholder="Enter Your Name" class="contact-form__input"></td>
                    </tr>
                    <tr>
                        <td>Email: </td>
                        <td><input type="email" placeholder="Enter Your email" class="contact-form__input"></td>
                    </tr>
                    <tr>
                        <td>Message: </td>
                        <td><textarea placeholder="Your Message" name="Message" rows="4" cols="25" class="contact-form__textarea"></textarea></td>
                    </tr>
                    <tr>
                        <td colspan="2" align="center"><input type="Submit" class="contact-form__submit"></td>
                    </tr>
                </table>
            </form>
        </div>
        <div class="section-five">
            <h4 class="section-five__title">Social media
                <a href="https://www.instagram.com/theagneljohn/?hl=en" target="_blank">Intagram</a>
                <a href="https://www.linkedin.com/in/vidya-neela-m-280112236/" target="_blank">linkedin</a>
            </h4>
            <p class="section-five__desc">© Vidya Neela M</p>
        </div>
    </div>
</body>

</html>

## CSS :
*{
    padding:0;
    margin:0;

}
body{
    font-family:"Young Serif", serif;
}
.container{
    padding:50px;               

}
.section-one{
    background-color: black;
    color:white;
    padding:50px;
}
.section-one__name{
    font-size: 50px;

}
.section-one__role{
    font-size: 30px;
}
.section-one__contact{
    background-color: orange;
    text-decoration: none;
    color: white;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 20px;
    padding-right: 20px;
    display: inline-block;
    margin-top: 10px;
}
.section-two,.section-three,.section-four,.section-five{
    margin-top: 20px;
}
.section-two__desc,.section-three__desc,.section-four__desc,.section-five__desc{
    margin-top: 10px;
}
.section-five{
    background-color: black;
    color:white;
    padding:20px;
}
.section-five__title a{
    color: aquamarine;
}
.section-three{
    background-color: blueviolet;
    color: black;
    padding-top: 10px;
    padding-bottom: 50px;
    padding-left: 20px;
    padding-right: 20px;
    display: inline-block;
    margin-top: 10px;
    border-radius: 10px;
    vertical-align: top;
}
.section-four{
    background-color: orangered;
    color: black;
    padding: 20px;
    display: inline-block;
    margin-top: 10px;
    border-radius: 10px;
    vertical-align: top;
}
.contact-form{
    margin-top: 20px;
}
.contact-form__input,.contact-form__textarea,.contact-form__submit{
    margin-top: 10px;
}
.contact-form__input{
    padding:10px;
    border:none;
    border-bottom:solid black 1px;
}
.contact-form__textarea{
    padding:10px;
    border:none;
    border:solid black 1px;
}
.contact-form__submit{
    background-color: orangered;
    color: black;
    padding: 10px;
    display: inline-block;
    margin-top: 10px;
}

## Motivation
The motivation behind this project is to create an online portfolio that represents my skills and projects as a Web Developer. This website serves as a digital introduction for potential clients, employers, and collaborators to understand my expertise and contact me easily.

## Contributing
Feel free to fork this repository, make improvements, and submit pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
