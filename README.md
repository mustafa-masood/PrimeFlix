# **PrimeFlix - React Tailwind Movie App**

_A movie discovery app powered by React and TailwindCSS._

## **Table of Contents**

1. [About](#about)
2. [Features](#features)
3. [Screenshots](#screenshots)
4. [Technologies Used](#technologies-used)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Deployment](#deployment)
8. [Contributing](#contributing)
9. [License](#license)

## **About**

PrimeFlix is a movie discovery web app that allows users to search for movies, view details, and explore the latest trending films. Built with **React**, **Tailwind CSS**, and integrated with the **Movie Database API (TMDB)** for real-time movie data.

### **Demo**

You can check out the live demo of the app on [GitHub Pages](https://mustafa-masood.github.io/PrimeFlix/)!

---

## **Features**

- **Search Movies:** Look for your favorite movies by title.
- **Movie Details:** Get detailed information about each movie, including release dates, ratings, and more.
- **Trending Section:** View trending movies in real time.
- **Responsive Design:** Optimized for mobile and desktop devices.

---

## **Screenshots**

Below are some visuals of the PrimeFlix app:

### **Home Page**

![Image](https://github.com/user-attachments/assets/a52ffc42-b68e-4947-97fb-ba7b4eacd6ed)


---

## **Technologies Used**

This project is built with the following technologies:

- **React**: A JavaScript library for building user interfaces.
- **TailwindCSS**: A utility-first CSS framework to style the app quickly.
- **Vite**: A modern, fast build tool for faster development.
- **Movie Database API (TMDB)**: Provides movie data including popular, top-rated, and trending movies.
- **gh-pages**: To deploy the app on GitHub Pages.

---

## **Installation**

To get started with PrimeFlix locally, follow these steps:

### **1. Clone the repository**
bash
git clone https://github.com/mustafa-masood/PrimeFlix.git
cd PrimeFlix
### **2. Install dependencies**
bash
npm install
### **3. Create a `.env` file**

You will need to add your TMDB API key. Create a `.env` file in the root of the project and add the following:

VITE_API_KEY=your_tmdb_api_key
You can get your API key by creating an account on [TMDB](https://www.themoviedb.org/).

### **4. Start the development server**
bash
npm run dev
This will start the app in development mode. Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

---

## **Usage**

Once you have the app running locally, you can:

- Search for movies by title using the search bar.
- View movie details, including cast, release date, and plot summary.
- Explore trending movies in real-time.

---

## **Deployment**

To deploy the app on GitHub Pages, follow these steps:

1. **Build the project**
bash
npm run build
2. **Deploy the app**
bash
npm run deploy
This will deploy the app to GitHub Pages and make it accessible at `https://mustafa-masood.github.io/PrimeFlix/`.

---

## **Contributing**

Contributions are always welcome! Please follow these steps if you'd like to contribute to the project:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -am 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a new Pull Request.

---

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### **Additional Notes**

- **Replace the placeholder image URLs**: Replace the image URLs above with your actual image paths or URLs.
- **GitHub Pages URL**: Replace `mustafa-masood` in the GitHub Pages URL (`https://mustafa-masood.github.io/PrimeFlix/`) with your actual GitHub username.
- **Customization**: You can modify the project to suit your specific requirements. Feel free to add more features and styles as needed.


### Key things to update:
1. **Screenshots**: The screenshots section now has placeholders. Be sure to replace the image URLs with actual paths to your images.
2. **GitHub Pages URL**: The link for your GitHub Pages deployment is using your GitHub username (mustafa-masood). If you deploy on your GitHub page, make sure to change the username if needed.
3. **API Key**: Don’t forget to add the .env file with your **TMDB API key**.
