# Diego de Sousa Araújo - Portfolio Website

This repository contains my personal portfolio website built with [Hugo](https://github.com/gohugoio/hugo), a static site generator. The website uses the [PaperMod theme](https://github.com/adityatelange/hugo-PaperMod) with custom modifications to showcase my professional work, personal projects, publications, and certifications.

## About

This website serves as my professional portfolio, featuring:

- **Professional Work**: Real-world projects developed while working for companies and organizations, including full-stack applications, mobile apps, and web platforms
- **Personal Work / Study Cases**: Personal projects and learning experiments exploring new technologies and concepts
- **Publications**: Academic articles and research papers I've authored or co-authored
- **Certifications & Awards**: Professional certifications, programs, and achievements

## Website Structure

The website is organized into the following main sections:

### Professional Work (`/professional-work/`)
Showcases projects with real users, developed while working for companies:
- **Syslae**: Full-stack development experience including web platforms (React.js, Next.js), mobile applications (React Native), and microservices (Django, Laravel)
- **Ceasa+**: Sales spot rental system built with React.js, Express.js, and TypeScript
- **ACIPI**: Full-stack JavaScript website for the Science Academy of Piauí

### Personal Work / Study Cases (`/personal-work/`)
Features personal projects and learning experiments:
- **AssinaAí (Checkin Now!)**: Laboratory attendance system with React web panel and Flutter mobile app
- **Typing / Letter-Scramble Animation**: Vanilla JavaScript learning project exploring animation techniques

### Publications (`/publications/`)
Academic articles and research papers:
- React JS e ROS 2: Web interface for robotic system data visualization
- Micro Mouse Simulator: Benefits of using digital simulators for maze-solving algorithms

### Certifications (`/certifications/`)
Professional certifications, programs, and achievements:
- EF SET English Certificate (C1 Advanced)
- HCIA – 5G (Huawei)
- Cloud Computing Instructor (Huawei)
- CCNA1 (Cisco)
- Python Essentials
- Seeds For The Future (Huawei)
- Competitive Programming participation
- Embedded Systems work

## Installation

### On your local machine

+ Install [Hugo](https://gohugo.io/installation/). On a Mac, this can be done with [Homebrew](https://brew.sh): run `brew install hugo` in the terminal. On Linux, you can use your package manager or download from the Hugo releases page.
+ Clone this repository to your local machine:
  ```bash
  git clone https://github.com/Daliego/hugo-website.git
  cd hugo-website
  ```
+ Install Hugo extended version (required for this theme):
  ```bash
  # On macOS with Homebrew
  brew install hugo
  
  # Or download from https://github.com/gohugoio/hugo/releases
  ```

### On your GitHub account

+ The website is configured to deploy automatically via GitHub Actions to GitHub Pages.
+ Ensure GitHub Actions and GitHub Pages are enabled in your repository settings.
+ The workflow file is located at `.github/workflows/hugo.yml`.
+ Once enabled, GitHub will build and publish the website automatically on each push to the main branch.

## Usage

### Local development

Navigate to the website directory and run:

```bash
hugo server
```

The command builds the website on your machine and makes it available at http://localhost:1313, rebuilding automatically as you edit files. You can modify the content and develop your website entirely on your machine.

### Adding new content

#### Professional Work
Create a new folder in `content/professional-work/` with an `index.md` file:
```bash
mkdir -p content/professional-work/my-project
touch content/professional-work/my-project/index.md
```

#### Personal Work
Create a new folder in `content/personal-work/` with an `index.md` file:
```bash
mkdir -p content/personal-work/my-project
touch content/personal-work/my-project/index.md
```

#### Publications
Create a new folder in `content/publications/` with an `index.md` file:
```bash
mkdir -p content/publications/my-publication
touch content/publications/my-publication/index.md
```

#### Certifications
Add entries directly to `content/certifications/_index.md` or create individual certification pages.

### Online deployment

Once your changes are ready, commit and push them to the repository:

```bash
git add .
git commit -m "Update website content"
git push origin main
```

GitHub Actions will automatically build and deploy the website to GitHub Pages.

## Configuration

The main configuration file is `config.yml`. Key settings include:

- `baseURL`: Your website URL (currently set to `https://daliego.github.io`)
- `title`: Site title
- `params.description`: Site description
- `params.profileMode`: Homepage profile configuration
- `params.socialIcons`: Social media links and icons
- `menu.main`: Navigation menu items

## Custom Features

### Custom Icons
Custom SVG icons for "Website" and "University" are defined in `layouts/partials/svg.html`.

### Logo and Favicons
The site logo and favicons use `application_logo.png` located in the `static/` folder. Configuration is in `config.yml` and `layouts/partials/head.html`.

### Theme Modifications
Custom CSS and layout modifications are in:
- `layouts/`: Custom layout templates
- `assets/css/`: Custom stylesheets
- `static/`: Static assets (images, videos, PDFs)

## Technology Stack

- **Static Site Generator**: Hugo v0.152.2
- **Theme**: PaperMod (with custom modifications)
- **Deployment**: GitHub Pages via GitHub Actions
- **Content Format**: Markdown with YAML frontmatter

## Project Structure

```
hugo-website/
├── assets/              # CSS, images, and other assets
├── content/            # Website content
│   ├── professional-work/  # Professional projects
│   ├── personal-work/      # Personal projects
│   ├── publications/       # Academic publications
│   └── certifications/     # Certifications and awards
├── layouts/            # Custom layout templates
├── static/             # Static files (images, videos, PDFs)
├── themes/             # Hugo theme (PaperMod)
└── config.yml          # Site configuration
```

## Software

+ The website is built with Hugo v0.152.2 via GitHub Actions.
+ The website was developed locally with Hugo v0.152.2 on Linux.
+ The website is tested on modern browsers (Chrome, Firefox, Safari, Edge).

## License

This repository is licensed under the [MIT License](LICENSE.md).

---

## Acknowledgments

This website is based on the [Minimalist Hugo Template for Academic Websites](https://github.com/pmichaillat/hugo-website) created by [Pascal Michaillat](https://pascalmichaillat.org/). The template uses the [PaperMod theme](https://github.com/adityatelange/hugo-PaperMod) by [Aditya Telange](https://github.com/adityatelange).

### Original Template

+ **Template Repository**: [pmichaillat/hugo-website](https://github.com/pmichaillat/hugo-website)
+ **Template Documentation**: https://pascalmichaillat.org/b/
+ **Template Illustration**: https://pascalmichaillat.org/hugo-website/

### Real-world implementations of the original template

+ [Pascal Michaillat's website](https://pascalmichaillat.org/) ([source code](https://github.com/pmichaillat/pmichaillat.github.io))
+ [Rosa van den Ende's website](https://rosavandenende.github.io) ([source code](https://github.com/rosavandenende/rosavandenende.github.io))
+ [Samia Kabir's website](https://samiakabir.com) ([source code](https://github.com/SamiaKabir/samiakabir.github.io))
+ [Dylan Laplace Mermoud's website](https://dylanlaplacemermoud.github.io) ([source code](https://github.com/DylanLaplaceMermoud/dylanlaplacemermoud.github.io))
+ [Maarten Goos's website](https://maartengoos.com) ([source code](https://github.com/MaartenGoos/website))
+ [Jun Wong's website](https://junwong.org) ([source code](https://github.com/junwong97/junwong97.github.io))
+ [Erling Rennemo Jellum's website](https://erlingrj.github.io) ([source code](https://github.com/erlingrj/erlingrj.github.io))
+ [Yangkeun Yun's website](https://yangkeunyun.github.io) ([source code](https://github.com/yangkeunyun/yangkeunyun.github.io))
+ [Lucas Warwar's website](https://lucaswarwar.github.io) ([source code](https://github.com/lucaswarwar/lucaswarwar.github.io))
+ [Franz Louis Cesista's website](https://leloykun.github.io) ([source code](https://github.com/leloykun/leloykun.github.io))
+ [Gabe Sekeres's website](https://gabesekeres.com) ([source code](https://github.com/gsekeres/hugo_site))
+ [Kevin Roice's website](https://kevroi.github.io) ([source code](https://github.com/kevroi/kevroi.github.io))
+ [Daniel Barbosa's website](https://dacbarbosa.github.io) ([source code](https://github.com/dacbarbosa/dacbarbosa.github.io))
+ [Wei Zhang's website](https://weizhang-econ.github.io) ([source code](https://github.com/weizhang-econ/weizhang-econ.github.io))
+ [Ben Hermann's website](http://benhermann.eu) ([source code](https://github.com/bhermann/bhermann.github.io))
+ [Franco Corona's website](http://fcorona.me) ([source code](https://github.com/exibios/exibios.github.io))
+ [Tom George's website](https://tomge.org) ([source code](https://github.com/TomGeorge1234/TomGeorge1234.github.io))
+ [Yucheng Zhou's website](https://yuchengzhou.com) ([source code](https://github.com/YuchengZ-Fin/YuchengZ-Fin.github.io))
+ [Rui Sousa's website](https://ruiagmsousa.github.io) ([source code](https://github.com/ruiagmsousa/ruiagmsousa.github.io))
+ [Stefano Sangiovanni's website](https://ste-sangiovanni.github.io) ([source code](https://github.com/ste-sangiovanni/ste-sangiovanni.github.io))
+ [Seth Watts's website](https://www.sethbwatts.com) ([source code](https://github.com/sBwatts/hugo-website))
+ [Louise Demoor's website](https://louisedemoor.github.io/website/) ([source code](https://github.com/louisedemoor/website))
+ [Giwon Bahg's website](https://giwonbahg.github.io) ([source code](https://github.com/giwonbahg/giwonbahg.github.io))
+ [Arthur Douillard's website](https://arthurdouillard.com)
+ [Benjamin Hattemer's website](https://benjaminhattemer.com)
+ [Kostas Bimpikis's website](https://stanford.edu/~kostasb/)
+ [Qiwei He's website](https://www.qiwei-he.com)
+ [Pierre Bardier's website](https://pierrebard.github.io/pierre-bardier/)
+ [Marek Wiewiórka's website](https://marekwiewiorka.org)
+ [Eran Shmuëli's website](https://eranshmueli.com)
+ [Bo Wang's website](https://bowang.finance)

### Related resources

+ [latex-cv](https://github.com/pmichaillat/latex-cv) - This LaTeX template produces a minimalist academic CV, which you can post on your website. The CV should be named `cv.pdf` and placed in the `static` folder. It will be accessible from the homepage via a social icon.
+ [latex-paper](https://github.com/pmichaillat/latex-paper) - This LaTeX template produces a minimalist research paper, which you can post on your website.
