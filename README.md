# Hugo Blog Development with Ubuntu DevContainer
This repository contains a Hugo-based blog framework with an Ubuntu devcontainer setup for easy development. You can use this environment to contribute, build, and run a Hugo-powered blog. See [Hugo Framework](https://gohugo.io/).

## Prerequisites
[Docker](https://docs.docker.com/engine/install/) installed on your system.

## Getting Started

### Setting Up the Development Environment
1. Clone this repository:
```
git clone https://github.com/yourusername/your-repo.git
```

2. Open the repository in Visual Studio Code or your preferred editor that supports devcontainers.

3. VS Code will detect the devcontainer configuration and prompt to reopen the project in the devcontainer. Click "Reopen in Container."

4. Once the devcontainer is built, you'll have an Ubuntu environment set up with Hugo installed.

## Building and Running the Hugo Blog
1. To build the Hugo blog, run the following command in the terminal:
```
hugo
```

2. To start the Hugo development server and view the blog locally, use:

```
hugo server -D
```
This will generate a local server address (usually __http://localhost:1313__) where you can preview your blog.

### Adding Posts
1. To add a new post, use Hugo's command-line tool:
```
hugo new posts/your-post-title.md
```
Replace __your-post-title__ with the desired title for your blog post.

2. Once the post file is created, open it in your editor and start writing using Markdown syntax. Save the file when finished.

3. Rebuild the blog by running '__hugo__' and check the changes by running '__hugo server -D__'.
