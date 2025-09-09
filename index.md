# layouts/index.html

```html
<html>
<head>
  <title>{{ .Site.Title }}</title>
</head>
<body>
  <h1>Hello, Hugo!</h1>
  {{ range .Site.RegularPages }}
    <h2><a href="{{ .RelPermalink }}">{{ .Title }}</a></h2>
    <p>{{ .Summary }}</p>
  {{ end }}
</body>
</html>
