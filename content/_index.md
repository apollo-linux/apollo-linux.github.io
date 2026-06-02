---
title: Apollo
---

{% index_section(id="welcome") %}
<div id="landing-start">
    <picture>
        <source srcset="/images/logomark_dark.svg" media="(prefers-color-scheme: light)">
        <img id="welcome-logo" src="/images/logomark.svg" alt="Apollo">
    </picture>

    <p>An up to date, easy to use and privacy respecting operating system for your computer.</p>
</div>

<div id="landing-buttons">
    {{ button(id="download-button", href="/downloads", label="Download Apollo") }}
    {{ button(href="#", label="Learn more") }}
</div>

<img id="landing-screenshot" src="/images/screenshots/landing_screenshot.png" alt="An Apollo desktop with the terminal open">
{% end %}