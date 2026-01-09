# Patarawadee Kunna 682115034

## In one sentence: What does res.render(view, data) do?
res.render(view, data) renders an EJS (or other template engine) view into HTML using the provided data and sends the result as the HTTP response.

## What is the difference between <%= %> and <%- %>?
<%= %> escapes HTML for safety, while <%- %> outputs raw, unescaped HTML.

## Where does Express look for EJS templates (folder path)?
Express looks for EJS templates in the views/ folder by default (relative to the project root).