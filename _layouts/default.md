<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>{% if page.title and page.title != 'Home' %}{{ page.title }} · {% endif %}{{ site.title }}</title>
  <meta name="author" content="Seyone Chithrananda">
  <meta name="description" content="{{ page.summary | default: site.description | escape }}">
  <meta name="theme-color" content="#f4efe4">
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
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;1,400;1,500&amp;family=DM+Sans:wght@400;500;600&amp;family=IBM+Plex+Mono:wght@400;500&amp;display=swap" rel="stylesheet">
  <link rel="stylesheet" href="/assets/styles.css">
</head>
<body>
  <div class="site-shell">
    <header class="site-header">
      <a class="site-brand" href="/" aria-label="Seyone Chithrananda, home"><span class="brand-mark" aria-hidden="true">SC</span><span>Seyone C.</span></a>
      <nav class="site-nav" aria-label="Main navigation">
        <a href="/#research">Research</a>
        <a href="/#work">Work</a>
        <a href="/#story">Story</a>
        <a href="/blog.html">Writing</a>
        <a class="nav-contact" href="mailto:seyonec@stanford.edu">Email ↗</a>
      </nav>
    </header>
    <main class="{% if page.homepage %}home-content{% else %}page-content{% endif %}" id="main-content">
      {{ content }}
    </main>
    {% include footer.html %}
  </div>
</body>
</html>
