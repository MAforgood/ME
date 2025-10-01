# Personal Website

This is a personal portfolio website for MohammadAli Khosroabadi, a Data Engineer. It is a single-page application built with HTML, CSS, and JavaScript, featuring a modern, dark theme and an interactive 3D background.

## Deployment

This website is a static site and can be deployed to any static site hosting service. Here are instructions for a few common platforms:

### GitHub Pages

1.  **Create a new repository on GitHub.**
2.  **Push the code to the repository.**
3.  **Go to the repository's settings.**
4.  **In the "Pages" section, select the `main` branch as the source and click "Save".**
5.  Your website will be live at `https://<your-username>.github.io/<repository-name>/`.

### Netlify

1.  **Sign up for a Netlify account.**
2.  **Click "New site from Git".**
3.  **Connect your Git provider (e.g., GitHub) and select the repository.**
4.  **Netlify will automatically detect the build settings (since it's a static site, no build command is needed).**
5.  **Click "Deploy site".**

### Vercel

1.  **Sign up for a Vercel account.**
2.  **Click "New Project".**
3.  **Import the Git repository.**
4.  **Vercel will automatically detect that it's a static site.**
5.  **Click "Deploy".**

## Local Development

To run the website locally, you can use a simple HTTP server. If you have Python installed, you can run the following command in the project's root directory:

```bash
python -m http.server
```

Then, open your browser and go to `http://localhost:8000`.