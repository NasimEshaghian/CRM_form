# CRM_form

## My Redirect Page

This repository hosts a simple static HTML page on **GitHub Pages** that automatically redirects visitors to another URL — for example, an **n8n Webhook** or any external link.

---

### 🌐 Live Demo
Once published via GitHub Pages, your page will be available at:

👉 **https://your-username.github.io/my-redirect-page/**

*(Replace `your-username` with your actual GitHub username.)*

---

### 🚀 How It Works
The `index.html` file contains a simple HTML redirect using the `<meta>` tag.  
When a user opens the page, they are immediately redirected to the target URL you specify.

#### Example:
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="refresh" content="0; url=https://your-n8n-domain/webhook/target-node" />
  <title>Redirecting...</title>
</head>
<body>
  <p>You are being redirected...</p>
</body>
</html>


### how to deploy:
Create a new public repository on GitHub.

Upload your index.html file.

Go to Settings → Pages.

Under Source, select the main branch and / (root) folder.

Click Save.

After a few seconds, GitHub will publish your page online.

### example use case:
Redirecting users to an n8n webhook or automation flow

Creating a custom landing or loading page

Forwarding visitors to another website or domain

### License:
This project is open source and free to use.

