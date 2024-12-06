# Ex.07 Restaurant Website
# Date:
06/12/2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
"""
<html>

<head>
    <title>
        Restaurant Website
    </title>
    <script src="https://cdn.tailwindcss.com">
    </script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet" />
    <link rel="stylesheet" href="res.css"/>

</head>

<body class="bg-gray-100">
    <!-- Navbar -->
    <nav class="bg-white shadow-lg">
        <div class="max-w-6xl mx-auto px-4">
            <div class="flex justify-between">
                <div class="flex space-x-7">
                    <div>
                        <a class="flex items-center py-4 px-2" href="#">
                            <img alt="Restaurant logo" class="h-8 w-8 mr-2" height="50" src="https://storage.googledsdsadsaapis.com/a1aa/image/eqGJFmD3iB37MSbhW1k6hHAxBFLDznVtO24ovoetosPYMVtTA.jpg" width="50" />
                            <span class="font-semibold text-gray-500 text-lg">
                                Master's Chef
                            </span>
                        </a>
                    </div>
                    <div class="hidden md:flex items-center space-x-1">
                        <a class="py-4 px-2 text-green-500 border-b-4 border-green-500 font-semibold" href="#">
                            Home
                        </a>
                        <a class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300" href="#menu">
                            Menu
                        </a>
                        <a class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300" href="#about">
                            About
                        </a>
                        <a class="py-4 px-2 text-gray-500 font-semibold hover:text-green-500 transition duration-300" href="#contact">
                            Contact
                        </a>
                    </div>
                </div>
                <div class="md:hidden flex items-center">
                    <button class="outline-none mobile-menu-button">
                        <i class="fas fa-bars">
                        </i>
                    </button>
                </div>
            </div>
        </div>
    </nav>
    <!-- Mobile Menu -->
    <div class="hidden mobile-menu">
        <ul class="">
            <li>
                <a class="block text-sm px-2 py-4 text-white bg-green-500 font-semibold" href="#">
                    Home
                </a>
            </li>
            <li>
                <a class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300" href="#menu">
                    Menu
                </a>
            </li>
            <li>
                <a class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300" href="#about">
                    About
                </a>
            </li>
            <li>
                <a class="block text-sm px-2 py-4 hover:bg-green-500 transition duration-300" href="#contact">
                    Contact
                </a>
            </li>
        </ul>
    </div>
    <!-- Hero Section -->
    <div class="bg-cover bg-center h-screen" style="background-image: url('https://images.unsplash.com/photo-151493365dsadsadsa1103-005eec06c04b?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');">
        <div class="flex items-center justify-center h-full bg-gray-900 bg-opacity-50">
            <div class="text-center">
                <h1 class="text-white text-5xl font-bold">
                    Welcome to Our Restaurant
                </h1>
                <p class="text-white text-xl mt-4">
                    Delicious food, cozy atmosphere
                </p>
                <a class="mt-6 inline-block bg-green-500 text-white py-2 px-4 rounded-full text-lg" href="#menu">
                    View Menu
                </a>
            </div>
        </div>
    </div>
    <!-- Menu Section -->
    <section class="py-20 bg-white" id="menu">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-4xl font-bold text-center text-gray-800">
                Our Menu
            </h2>
            <div class="mt-10 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <img alt="Image of a delicious dish" class="w-full h-40 object-cover rounded-t-lg" height="200" src="https://images.unspdsadsadsalash.com/photo-1464093515883-ec948246accb?q=80&w=2059&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" width="300" />
                    <h3 class="text-xl font-semibold mt-4">
                        Lobster Ravioli and Scampi cream
                    </h3>
                    <p class="text-gray-600 mt-2">
                        Description of the dish goes here. It is a delicious and popular item.
                    </p>
                    <p class="text-green-500 font-bold mt-2">
                        $12.99
                    </p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <img alt="Image of a delicious dish" class="w-full h-40 object-cover rounded-t-lg" height="200" src="https://imagedsadsasas.unsplash.com/photo-1498531872221-ce6d6216be71?q=80&w=1931&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" width="300" />
                    <h3 class="text-xl font-semibold mt-4">
                        Gourmet prawn
                    </h3>
                    <p class="text-gray-600 mt-2">
                        Description of the dish goes here. It is a delicious and popular item.
                    </p>
                    <p class="text-green-500 font-bold mt-2">
                        $15.99
                    </p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <img alt="Image of a delicious dish" class="w-full h-40 object-cover rounded-t-lg" height="200" src="https://cdn.pixabssadsadsaay.com/photo/2015/05/02/01/02/chicken-bokeumtang-749365_960_720.jpg" width="300" />
                    <h3 class="text-xl font-semibold mt-4">
                        Dak Bokkeumtang
                    </h3>
                    <p class="text-gray-600 mt-2">
                        Description of the dish goes here. It is a delicious and popular item.
                    </p>
                    <p class="text-green-500 font-bold mt-2">
                        $9.99
                    </p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
            
                    <h3 class="text-xl font-semibold mt-4">
                        Bruschetta with Smoked salmon
                    </h3>
                    <p class="text-gray-600 mt-2">
                        Description of the dish goes here. It is a delicious and popular item.
                    </p>
                    <p class="text-green-500 font-bold mt-2">
                        $11.99
                    </p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">

                        Black Squid Ink Pasta
                    </h3>
                    <p class="text-gray-600 mt-2">
                        Description of the dish goes here. It is a delicious and popular item.
                    </p>
                    <p class="text-green-500 font-bold mt-2">
                        $13.99
                    </p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <img alt="Image of a delicious dish" class="w-full h-40 object-cover rounded-t-lg" height="200" src="https:/sjjjjhhjksksk/images.unsplash.com/photo-1583623025817-d180a2221d0aq=80&w=2071&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" width="300" />
                    <h3 class="text-xl font-semibold mt-4">

                        Sushi plate with chopsticks and soya souce.
                    </h3>
                    <p class="text-gray-600 mt-2">
                        Description of the dish goes here. It is a delicious and popular item.
                    </p>
                    <p class="text-green-500 font-bold mt-2">
                        $14.99
                    </p>
                </div>
            </div>
        </div>
    </section>
    <!-- About Section -->
    <section class="py-20 bg-gray-100" id="about">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-4xl font-bold text-center text-gray-800">
                About Us
            </h2>
            <div class="mt-10 flex flex-col md:flex-row items-center">
                <div class="md:w-1/2">
                    <img alt="Image of the restaurant interior" class="w-full h-auto rounded-lg shadow-lg" height="300" src="https://storage.googleapis.com/a1aa/image/N1sTxIDwMrKlChChhjjhjUFTMlUUY336xae9RBRyF0Bikym2aNmq2JA.jpg" width="500" />
                </div>
                <div class="md:w-1/2 md:ml-10 mt-6 md:mt-0">
                    <p class="text-gray-600 text-lg">
                        Our restaurant has been serving delicious food to the community for over 20 years. We pride ourselves on using the freshest ingredients and providing a cozy atmosphere for our guests. Whether you're here for a quick bite or a special occasion, we strive to make every visit memorable.
                    </p>
                    <p class="text-gray-600 text-lg mt-4">
                        Our menu features a variety of dishes, from classic favorites to innovative new creations. We also offer a selection of fine wines and craft beers to complement your meal. Come and experience the best dining experience in town!
                    </p>
                </div>
            </div>
        </div>
    </section>
    <!-- Contact Section -->
    <section class="py-20 bg-white" id="contact">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-4xl font-bold text-center text-gray-800">
                Contact Us
            </h2>
            <div class="mt-10 flex flex-col md:flex-row items-center">
                <div class="md:w-1/2">
                    <form action="#" class="bg-gray-100 p-6 rounded-lg shadow-lg" method="POST">
                        <div class="mb-4">
                            <label class="block text-gray-700 font-bold mb-2" for="name">
                                Name
                            </label>
                            <input class="w-full px-3 py-2 border border-gray-300 rounded-lg" id="name" name="name" required="" type="text" />
                        </div>
                        <div class="mb-4">
                            <label class="block text-gray-700 font-bold mb-2" for="email">
                                Email
                            </label>
                            <input class="w-full px-3 py-2 border border-gray-300 rounded-lg" id="email" name="email" required="" type="email" />
                        </div>
                        <div class="mb-4">
                            <label class="block text-gray-700 font-bold mb-2" for="message">
                                Message
                            </label>
                            <textarea class="w-full px-3 py-2 border border-gray-300 rounded-lg" id="message" name="message" required="" rows="4"></textarea>
                        </div>
                        <button class="bg-green-500 text-white py-2 px-4 rounded-full" type="submit">
                            Send Message
                        </button>
                    </form>
                </div>
                <div class="md:w-1/2 md:ml-10 mt-6 md:mt-0">
                    <h3 class="text-2xl font-semibold text-gray-800">
                        Get in Touch
                    </h3>
                    <p class="text-gray-600 text-lg mt-4">
                        We'd love to hear from you! Whether you have a question about our menu, want to make a reservation, or just want to say hello, feel free to reach out to us.
                    </p>
                    <p class="text-gray-600 text-lg mt-4">
                        <i class="fas fa-phone-alt">
                        </i>
                        044 27162510
                    </p>
                    <p class="text-gray-600 text-lg mt-4">
                        <i class="fas fa-envelope">
                        </i>
                        info@24005998.com
                    </p>
                    <p class="text-gray-600 text-lg mt-4">
                        <i class="fas fa-map-marker-alt">
                        </i>
                        123 Main Street, Thiruverkadu, Chennai.
                    </p>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer -->
    <footer class="bg-gray-800 py-6">
        <div class="max-w-6xl mx-auto px-4">
            <div class="flex justify-between items-center">
                <p class="text-white">
                    © 2024 Restaurant Name. All rights reserved.
                </p>
                <div class="flex space-x-4">
                    <a class="text-white" href="#">
                        <i class="fab fa-facebook-f">
                        </i>
                    </a>
                    <a class="text-white" href="#">
                        <i class="fab fa-twitter">
                        </i>
                    </a>
                    <a class="text-white" href="#">
                        <i class="fab fa-instagram">
                        </i>
                    </a>
                </div>
            </div>
        </div>
    </footer>
    <script>
        const btn = document.querySelector("button.mobile-menu-button");
        const menu = document.querySelector(".mobile-menu");

        btn.addEventListener("click", () => {
            menu.classList.toggle("hidden");
        });
    </script>
</body>

</html>

# OUTPUT:

![Screenshot 2024-12-06 192300](https://github.com/user-attachments/assets/1cfd0825-e65d-41e6-a378-30c8bd9b669b)

![Screenshot 2024-12-06 192320](https://github.com/user-attachments/assets/461065d3-486e-47a2-848c-e79b142e7fa8)

![Screenshot 2024-12-06 192350](https://github.com/user-attachments/assets/519399e6-ba31-478b-8bd5-0814e4fd9714)

![Screenshot 2024-12-06 192408](https://github.com/user-attachments/assets/b01a0ac6-9c88-4063-b430-b67081db1490)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
