
# UI/UX Hackathon - Quarter 2 (GIAIC)

This project was created as part of the **UI/UX Hackathon** in **Quarter 2**, organized by **GIAIC**. The project is built using **Next.js** and aims to provide an interactive and responsive **UI/UX** experience.

---

## Project Purpose

The main goal of this project is to create an intuitive and user-friendly interface using modern web technologies. It focuses on demonstrating the potential of **Next.js** for creating scalable, dynamic websites while ensuring a smooth and visually appealing user experience. The project was developed to showcase skills in both **UI/UX design** and **frontend development**.

---

## Features

- **Responsive Design**: The website adapts seamlessly to different screen sizes (desktops, tablets, and mobile devices).
- **Interactive UI**: The design is user-centric with a focus on usability and interaction.
- **Performance Optimizations**: Built using **Next.js** for fast page loading and SEO optimizations.

---

## Key Components Implemented

### 1. **Next.js Framework**  
The core framework used for building the application.  
- **Server-Side Rendering (SSR)**: Improves SEO and speeds up page loads.
- **Static Site Generation (SSG)**: For static pages to enhance performance.

### 2. **Pages**  
The website is composed of several pages:
- **Home**: Displays the main interface of the app.
- **Shop**: Lists available products/services.
- **Blog**: A blog section for posts or updates.
- **Contact**: A contact form for users to reach out.

### 3. **Responsive UI**  
The site is fully responsive and optimized for different screen sizes using **CSS Grid** and **Flexbox**.  
- **Media Queries**: Ensure the layout adapts smoothly across various devices.

### 4. **UI Components**  
Custom UI components such as:
- Buttons
- Cards
- Navigation bars  
Styled using **Material UI** and **CSS** for consistency.

### 5. **SEO Optimization**  
- Page metadata and optimized content for better search engine indexing.

---

## Steps to Run the Project Locally

To run the project locally, follow these steps:

### 1. Clone the Repository
Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/yourprojectname.git
```

### 2. Install Dependencies
Navigate into the project directory and install the dependencies:

```bash
cd yourprojectname
npm install
```

### 3. Set up Environment Variables (if any)
If the project requires any environment variables (e.g., API keys, secrets), create a `.env.local` file and add them. Example:

```bash
NEXT_PUBLIC_API_KEY=yourapikey
```

### 4. Run the Development Server
Start the development server:

```bash
npm run dev
```

The app will now be running locally at [http://localhost:3000](http://localhost:3000).

---

## Project Structure

Here’s an overview of the project structure:

```
/pages                # All the page components (Home, Shop, Blog, Contact)
/components           # Reusable UI components (buttons, cards, etc.)
/public               # Static assets (images, icons, fonts)
/styles               # Global styles (CSS files)
/next.config.js       # Next.js configuration file
/package.json         # Project dependencies and scripts
```

---

## Technologies Used

- **Next.js**: For building the React application with server-side rendering (SSR).
- **React**: For creating dynamic components and managing UI state.
- **CSS/SCSS**: For styling the application.
- **Material UI**: For reusable components like buttons, grids, etc.
- **Vercel**: For deploying and hosting the application.

---

## Challenges Faced

- **Responsive Design**: Ensuring the design adapts well across different screen sizes.
- **SEO Optimization**: Ensuring the app is SEO-friendly while maintaining performance.
- **Dynamic Routing**: Implementing routing for dynamic content like blog posts and product listings.

---

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and make a pull request. Please ensure to follow coding standards and provide clear commit messages.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
