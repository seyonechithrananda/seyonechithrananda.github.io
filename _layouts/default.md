<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>{% if page.title and page.title != 'Home' %}{{ page.title }} · {% endif %}{{ site.title }}</title>
  <meta name="author" content="Seyone Chithrananda">
  <meta name="description" content="{{ page.summary | default: site.description | escape }}">
  <meta name="theme-color" content="#f7f5ed">
  <meta property="og:type" content="website">
  <meta property="og:title" content="{% if page.title and page.title != 'Home' %}{{ page.title }} · {% endif %}{{ site.title }}">
  <meta property="og:description" content="{{ page.summary | default: site.description | escape }}">
  <meta property="og:url" content="{{ page.url | prepend: site.url }}">
  <meta name="twitter:card" content="summary">
  <meta name="twitter:creator" content="@SeyoneC">
  <link rel="icon" href="/favicon.svg" type="image/svg+xml">
  <link rel="icon" href="/favicon.ico" sizes="any">
  <link rel="apple-touch-icon" href="/apple-touch-icon.png">
  <link rel="manifest" href="/site.webmanifest">
  <link rel="stylesheet" href="/assets/styles.css">
</head>
<body>
  <div class="site-shell">
    <nav class="site-nav" aria-label="Main navigation">
      <a href="/">Home</a>
      <a href="/#research">Research</a>
      <a href="/#publications">Publications</a>
      <a href="/blog.html">Writing</a>
    </nav>
    <main id="main-content" class="{% if page.homepage %}home-content{% else %}page-content{% endif %}">
      {{ content }}
    </main>
    {% include footer.html %}
  </div>
</body>
</html>
