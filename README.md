<!DOCTYPE html>
<html lang="em">
    <head>
        <title>Fashion Showcase</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <header>
            <h1>Encano Fashion Products Showcase</h1>
        </header>
        <main>
            <section id="shrub-clothes">
                <h2>
                    Shrub Clothes
                </h2>
                <img src="IMG-20240901-WA0029.jpg" alt="Shrub Clothes">
                <img src="IMG-20240830-WA0005.jpg" alt="Shrub Clothes">
                <right><video width="400" height="400" controls>
                    <source src="" type="video/mp4">
                     This browser doesn't support video tag.
                </video></right>
                <p>
                    Explore our exclusive collection of shrub clothes.
                </p>
            </section>
            <section id="shoes">
                <h2>
                    Shoes
                </h2>
                <img src="IMG-20240830-WA0014.jpg" alt="Shoes">
                <img src="IMG-20240830-WA0012.jpg" alt="Shoes">
                <p>
                    Step into style with our latest shoes.
                </p>
            </section>
            <section id="Contact">
                <h2>
                    Contact Us
                </h2>
                <p>
                    if you have any inquiries, feel free to contact us at
                </p>
                <a href="Tel:+233536513565">+233536513565</a>
            </section>
            <section id="footer">
                <p>
                    &copy; 2024 Fashion Products Showcase. All right reserved.
                </p>

            </section>
        </main>
    </body>
</html>
/* styles.css */

/* Global Styles */

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
  background-color: #f9f9f9;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

main {
  max-width: 1200px;
  margin: 40px auto;
  display: flex;
  flex-direction: column;
  align-items: center;
}

section {
  background-color: #fff;
  padding: 20px;
  margin-bottom: 20px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

h1, h2 {
  color: #333;
  margin-bottom: 10px;
}

img {
  max-width: 100%;
  height: auto;
  margin-bottom: 10px;
}

a {
  color: #337ab7;
  text-decoration: none;
}

a:hover {
  color: #23527c;
}

#footer {
  text-align: center;
  padding: 10px;
  background-color: #333;
  color: #fff;
  margin-top: 20px;
}
