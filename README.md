# HTML5 Boilerplate v5.0.0 for Harp

The bulk of the original boilerplate's `index.html` has been converted into `_layout.jade` to wrap your Harp site. Inside the `<head>` element, the `<title>` tag has been modified to evaluate to one of two values from `_data.json`, either the global `siteTitle` attribute or a `pageTitle` attribute specifically defined for a page.

**Happy building!**

## Usage

### 1. Install Harp

    sudo npm install -g harp

### 2. Clone this project

create a new harp application cloning this boilerplate...

    harp init myproj --boilerplate bradcliffe/hb-html5-boilerplate

### 3. Serve project using harp

change directory to project root...

    cd myproj

start harp web server...

    harp server

Your project is now running at [http://localhost:9000]()
