# Passing-Data-Learning

# ✅ Definition of EJS
EJS (Embedded JavaScript Templates) is a simple templating language that lets you generate HTML markup with plain JavaScript. It’s used with Node.js (often via Express.js) to render dynamic web pages on the server.

# ⚙️ How EJS Works
HTML Template with Embedded JS

You create .ejs files that look like HTML but include special tags (<%= %>, <% %>) to inject JavaScript and data.

Server Sends Data

In your Node.js/Express app, you use res.render('template', { data }) to send data to the EJS file.

EJS Compiles to HTML

EJS parses the template, replaces the JS placeholders with actual data, and generates a full HTML page.

Client Receives HTML

The browser gets a fully-rendered HTML page — no EJS or JS tags remain.
