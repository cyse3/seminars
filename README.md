# UK Security & Privacy Seminars (UK-SPS)

![Logo](https://raw.githubusercontent.com/uk-sps-fm/seminars/refs/heads/main/static/logo_sq-16-150x150.png)
Welcome to the **UK Security & Privacy Seminars** website repository! This project is powered by [Hugo](https://gohugo.io/), a fast and flexible static site generator, and is designed to showcase upcoming talks, presenters, and past events.

---

## 🚀 Features

- **Dynamic Content**: Add, update, and manage talks and presenters easily.
- **Customizable Design**: Built with Bootstrap for responsive and modern design.
- **Future-Proof**: Supports future events and auto-sorting based on dates.
- **Rich Content Support**: Add MathJax equations, images, and markdown effortlessly.

---

## 📂 Project Structure

```plaintext
├── archetypes/        # Templates for new content types (e.g., talks, presenters)
├── assets/            # Compiled assets like CSS and JavaScript
├── content/           # Site content
│   ├── talks/         # Markdown files for talks
│   └── presenters/    # Markdown files for presenters
├── static/            # Static files like images and downloads
├── layouts/           # Custom layouts and partials for rendering pages
├── themes/            # Theme files (e.g., PaperMod)
├── config.toml        # Site configuration
```

---

## 🛠️ Installation and Setup (Local Development)

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/uk-sps-fm/seminars.git
   cd seminars
   ```

2. **Install Hugo**:
   Follow the [official guide](https://gohugo.io/getting-started/installing/) to install Hugo.

3. **Run the Development Server**:
   ```bash
   hugo server
   ```

4. **View the Website**:
   Open [http://localhost:1313](http://localhost:1313) in your browser.

5. **Build the Website**:
   Generate the static files for deployment:
   ```bash
   hugo
   ```

---

## 📝 Content Management

### Add a New Talk
1. Create a new file under `content/talks/`:
   ```bash
   hugo new talks/<talk-name>.md
   ```
2. Fill in the metadata and content for the talk.
3. **See the structure from existing talks if you're unsure**

### Add a New Presenter
1. Create a new file under `content/presenters/`:
   ```bash
   hugo new presenters/<presenter-name>.md
   ```
2. Add details like name, affiliation.
3. *(optional)* Place a picture in the same directory, like `presenter/<presenter-name>.jpg` (only `.jpg` name extension is allowed)
4. **See the structure from existing presenters if you're unsure**

---

## 📦 Deployment

This site is hosted on GitHub Pages. Changes pushed to the `main` branch will trigger an automatic deployment.
**So be mindful**

To manually build the site:
```bash
hugo -D
```

---

## 📚 Resources

- [Hugo Documentation](https://gohugo.io/documentation/)
- [Bootstrap](https://getbootstrap.com/)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🌟 Acknowledgements

Thanks to the Hugo and Bootstrap communities for their amazing tools and themes!
