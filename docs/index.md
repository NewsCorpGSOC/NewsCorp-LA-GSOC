<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title }} | {{ site.title }}</title>
    <link rel="stylesheet" href="{{ "/assets/css/style.css" | relative_url }}">
</head>
<body>
    <div class="header">
        <img src="NewsCorpLogo-Black.png" alt="Site Logo">
        <ul class="nav-menu">
            <li><a href="{{ "/" | relative_url }}">Home</a></li>
            <li>
                <a href="#">Tools</a>
                <div class="dropdown-content">
                    <a href="{{ "/phone-log" | relative_url }}">Phone Log</a>
                    <a href="{{ "/daily-high-risk-sheet" | relative_url }}">Daily High Risk Sheet</a>
                    <a href="{{ "/gpms" | relative_url }}">GPMS</a>
                </div>
            </li>
            <li><a href="{{ "/links" | relative_url }}">Links</a></li>
        </ul>
    </div>
    <div class="sidebar">
        <!-- Sidebar content can go here -->
    </div>
    <div class="content">
        {{ content }}
    </div>
    <footer>
        <p>&copy; {{ site.time | date: "%Y" }} {{ site.title }}. All rights reserved.</p>
    </footer>
</body>
</html>
