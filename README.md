# Personal Website

Welcome to my personal website repository! This website is powered by **GitHub Pages** and hosted under the custom domain [sonumehta.online](https://sonumehta.online). It's a space where I showcase my work, share a bit about myself, and make my online presence known.

## Demo

You can view the live website here:  
[https://sonumehta.online](https://sonumehta.online)

## Repository Overview

This repository contains the source code for my personal website. The site is built using basic web technologies such as:

- **HTML**: For structure and content
- **CSS**: For styling and layout
- **JavaScript**: For interactivity (optional)

## Project Setup

If you would like to clone this repository and view it locally, follow these steps:

### Prerequisites

- A web browser (Google Chrome, Firefox, Safari, etc.)
- Basic knowledge of HTML, CSS, and JavaScript

### Steps to Clone and Run Locally

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/sonumehtaskr/sonumehtaskr.github.io.git
    ```

2. Navigate into the project directory:
    ```bash
    cd sonumehtaskr.github.io
    ```

3. Open the `index.html` file in your preferred web browser to view the site locally.

### How to Contribute

I welcome contributions and improvements to this project! To contribute:

1. Fork the repository.
2. Clone your forked repository:
    ```bash
    git clone https://github.com/your-username/username.github.io.git
    ```
3. Create a new branch for your changes:
    ```bash
    git checkout -b feature-branch
    ```
4. Make your changes and commit them:
    ```bash
    git add .
    git commit -m "Description of your changes"
    ```
5. Push your changes:
    ```bash
    git push origin feature-branch
    ```
6. Open a pull request to merge your changes into the main branch.

## Custom Domain Setup

This website is hosted on a custom domain (`sonumehta.online`). Here’s how I set it up:

1. In the root of this repository, I created a `CNAME` file and added my custom domain (`sonumehta.online`) inside it:
    ```text
    sonumehta.online
    ```

2. In my domain registrar's DNS settings, I added a **CNAME** record to point the subdomain `www` to `sonumehtaskr.github.io`, like so:
    - **Type**: CNAME
    - **Name**: `www`
    - **Value**: `sonumehtaskr.github.io`

3. Alternatively, for root domains like `sonumehta.online` without the `www`, I added **A Records** with GitHub's IP addresses:
    - **Type**: A
    - **Name**: `@` (root domain)
    - **Values**:
      - `185.199.108.153`
      - `185.199.109.153`
      - `185.199.110.153`
      - `185.199.111.153`

4. After DNS changes, I waited for DNS propagation (up to 48 hours).

5. I then enabled **HTTPS** under GitHub Pages settings for a secure browsing experience.


## Contact

If you have any questions or would like to get in touch, feel free to reach out to me at:  
[sonumehtaskr@gmail.com](mailto:sonumehtaskr@gmail.com)

---

Thank you for visiting my personal website repository!
