Welcome to GBlog! This is a simple and elegant blog platform built using Hugo, a fast and flexible static site generator. This project is a result of a code-along with Lama Dev
## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)


## Features

- Responsive design
- Easy content management with Markdown
- Fast and secure static site generation
- Light and dark mode toggle
- SEO-friendly

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Hugo](https://gohugo.io/getting-started/installing/) (minimum version 0.125.7)
- [Git](https://git-scm.com/)

### Installation

1. **Clone the repository**

    ```sh
    git clone https://github.com/your-username/gb-blog.git
    cd gb-blog
    ```

2. **Install Hugo**

    Follow the [official Hugo installation guide](https://gohugo.io/getting-started/installing/) for your operating system.

3. **Run the Hugo server**

    ```sh
    hugo server
    ```

    Open your browser and navigate to `http://localhost:1313` to see your blog in action.

## Usage

### Adding a New Post

1. **Create a new post**

    ```sh
    hugo new posts/my-new-post.md
    ```

2. **Edit the new post**

    Open the newly created markdown file in your preferred text editor and add your content. Each post supports metadata fields like title, date, categories, etc.

3. **Build the site**

    ```sh
    hugo
    ```

4. **Deploy your site**

    Hugo can generate static files for easy deployment to any web hosting service. Check the [Hugo deployment guide](https://gohugo.io/hosting-and-deployment/) for more details.

### Customizing the Theme

1. **Modify CSS**

    Edit the `styles/style.css` file to customize the look and feel of your blog.

2. **Edit HTML templates**

    The HTML templates are located in the `layouts` directory. Modify these files to change the structure of your pages.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

