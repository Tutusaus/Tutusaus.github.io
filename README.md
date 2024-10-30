# My Personal Website

Welcome to the repository for my personal website, hosted on **GitHub Pages**. This website serves as my online portfolio, showcasing my projects, academic work, and professional background. You can visit the live website directly or access it through the repository.

## Accessing the Website

You can visit the live website here: [**tutusaus.github.io**](https://tutusaus.github.io/)

Alternatively, follow these steps to access the website from the repository:

1. Navigate to the repository’s main page: [**Tutusaus/Tutusaus.github.io**](https://github.com/Tutusaus/Tutusaus.github.io).
2. Click on the **Deployments** tab located near the top of the repository page.
3. Under the **Environments** section, click on the link to the **GitHub Pages deployment**.
4. This will direct you to the live website.

## About the Website

The source code for my personal website is a fork of the [al-folio](https://github.com/alshedivat/al-folio) repository.

This website is built using **GitHub Pages** and features:

- A clean and responsive design.
- A showcase of my projects and academic achievements.
- Information about my professional background and interests.

Feel free to explore the website and reach out if you have any questions or feedback!

## Reopening and Editing the Jekyll Project Locally with Docker

To restart, edit, and view changes on your Jekyll project locally using Docker (before pushing it to GitHub) just follow this next instructions.

---

### 1. Start the Docker Container

To restart the Jekyll container and serve the site again:
1. Open a terminal in your project folder (where the `docker-compose.yml` file is located).
2. Run the following command:

   ```bash
   docker-compose up
   ```

   This will start the container and serve your Jekyll site with the options you configured previously. Once started, your site should be accessible at [http://localhost:4000](http://localhost:4000).

   - **Optional:** To run the container in the background (so your terminal is free for other tasks), add the `-d` flag:

     ```bash
     docker-compose up -d
     ```

### 2. Edit Files and View Changes

With the container running:
- Edit your project files as needed in your code editor (like VSCode).
- Once you save changes, Jekyll will detect the updates and reload the site automatically in the browser, thanks to `--livereload` and `--force_polling`.

### 3. Stop the Container

When you’re done working, stop the container by pressing `Ctrl+C` in the terminal (if it’s not detached) or by running:

   ```bash
   docker-compose down
   ```

---

### Summary

- Use `docker-compose up` to start the site and view it on [http://localhost:4000](http://localhost:4000).
- Edit files to see changes with live reloading.
- Stop the container with `docker-compose down` when finished.

**Note that you need to have docker and docker-compose installed and running in your system when using this commands. Ruby is also recommended.**