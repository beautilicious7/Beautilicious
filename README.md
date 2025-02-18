
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beautilicious - Indian Beauty for Indian Shades</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e6d6f5;
        }
        header {
            background-color: #b19cd9;
            color: white;
            padding: 15px;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
        }
        nav {
            text-align: center;
            background-color: #c8a2c8;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        .container {
            padding: 20px;
            text-align: center;
        }
        .product {
            display: inline-block;
            background: white;
            padding: 15px;
            margin: 10px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
            width: 250px;
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <header>Beautilicious - Beauty for Every Indian Skin Tone</header>
    <nav>
        <a href="#home">Home</a>
        <a href="#shop">Shop</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container" id="home">
        <h2>Welcome to Beautilicious</h2>
        <p>Your one-stop destination for makeup designed for Indian skin tones.</p>
    </div>
    <div class="container" id="shop">
        <h2>Our Products</h2>
        <div class="product">
            <img src="images/primer.jpg" alt="Primer">
            <h3>Primer</h3>
            <p>Creates a smooth base for flawless makeup application.</p>
        </div>
        <div class="product">
            <img src="images/foundation.jpg" alt="Foundation">
            <h3>Foundation</h3>
            <p>Hydrating and long-lasting formula, perfect for Indian skin tones.</p>
        </div>
        <div class="product">
            <img src="images/concealer.jpg" alt="Concealer">
            <h3>Concealer</h3>
            <p>Brightens and covers imperfections seamlessly.</p>
        </div>
        <div class="product">
            <img src="images/compact.jpg" alt="Compact Powder">
            <h3>Compact Powder</h3>
            <p>Controls shine and sets makeup for a matte finish.</p>
        </div>
        <div class="product">
            <img src="images/blush.jpg" alt="Blush">
            <h3>Blush</h3>
            <p>Adds a natural flush with shades tailored for Indian skin.</p>
        </div>
        <div class="product">
            <img src="images/highlighter.jpg" alt="Highlighter">
            <h3>Highlighter</h3>
            <p>Gives a radiant glow, enhancing your natural features.</p>
        </div>
        <div class="product">
            <img src="images/eyeshadow.jpg" alt="Eyeshadow Palette">
            <h3>Eyeshadow Palette</h3>
            <p>A mix of mattes and shimmers, perfect for any occasion.</p>
        </div>
        <div class="product">
            <img src="images/eyeliner.jpg" alt="Eyeliner">
            <h3>Eyeliner</h3>
            <p>Smudge-proof and long-lasting for a defined look.</p>
        </div>
        <div class="product">
            <img src="images/mascara.jpg" alt="Mascara">
            <h3>Mascara</h3>
            <p>Volumizes and lengthens lashes for a dramatic effect.</p>
        </div>
        <div class="product">
            <img src="images/lipstick.jpg" alt="Lipstick">
            <h3>Lipstick</h3>
            <p>Highly pigmented shades designed for Indian skin tones.</p>
        </div>
        <div class="product">
            <img src="images/setting_spray.jpg" alt="Setting Spray">
            <h3>Setting Spray</h3>
            <p>Locks in makeup for all-day wear.</p>
        </div>
    </div>
    <div class="container" id="about">
        <h2>About Us</h2>
        <p>Beautilicious is a brand dedicated to offering inclusive, skin-loving, and long-lasting makeup for all Indian skin tones.</p>
    </div>
    <div class="container" id="contact">
        <h2>Contact Us</h2>
        <p>Email: support@beautilicious.com</p>
    </div>
</body>
</html>
<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# GitHub Pages

_Create a site or blog from your GitHub repositories with GitHub Pages._

</header>

<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked for empty pull request, changed to the correct theme `minima`.
-->

## Step 2: Configure your site

_You turned on GitHub Pages! :tada:_

We'll work in a branch, `my-pages`, that I created for you to get this site looking great. :sparkle:

Jekyll uses a file titled `_config.yml` to store settings for your site, your theme, and reusable content like your site title and GitHub handle. You can check out the `_config.yml` file on the **Code** tab of your repository.

We need to use a blog-ready theme. For this activity, we will use a theme named "minima".

### :keyboard: Activity: Configure your site

1. Browse to the `_config.yml` file in the `my-pages` branch.
1. In the upper right corner, open the file editor.
1. Add a `theme:` set to **minima** so it shows in the `_config.yml` file as below:
   ```yml
   theme: minima
   ```
1. (optional) You can modify the other configuration variables such as `title:`, `author:`, and `description:` to further customize your site.
1. Commit your changes.
1. (optional) Create a pull request to view all the changes you'll make throughout this course. Click the **Pull Requests** tab, click **New pull request**, set `base: main` and `compare:my-pages`.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
