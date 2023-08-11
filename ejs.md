<!-- Variables -->

```ejs
<% const name = 'mario' %>
<%= name %>

// app.js
res.render('index', { title: 'Home', blogs })

// index.ejs
<%= title %>
```

<!-- Partials -->

```ejs
// All pages
<%- include('./partials/head.ejs') %>

// Dynamic meta content

<%= title %>
<%= decription %>
```
