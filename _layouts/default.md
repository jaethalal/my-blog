<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title }} - {{ site.title }}</title>
</head>
<body>
    <header>
        <h1>{{ site.title }}</h1>
        <nav>
            <a href="{{ site.baseurl }}/">Home</a>
        </nav>
    </header>
    <main>
        {{ content }}
    </main>
    <footer>
        <p>&copy; 2024 {{ site.title }}</p>
    </footer>
</body>
</html>