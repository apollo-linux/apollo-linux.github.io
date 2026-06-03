---
title: An up to date, easy to use and privacy respecting operating system for your computer
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
    {{ button(id="download-button", extra_classes="suggestive", href="/downloads", label="Download Apollo") }}
    {{ button(href="#ready-from-day-one", label="Learn more") }}
</div>

<img id="landing-screenshot" src="/images/screenshots/landing_screenshot.png" alt="An Apollo desktop with the terminal open">
{% end %}

{% index_section(id="ready-from-day-one") %}
<div id="rfd1-text">
    <h1>Ready from day one</h1>
    <p>Apollo stays out of your way and makes it easier to do the things you love. We include all the drivers, media codecs and default apps you need, making it quicker to get going from day one. Apollo works great for everyday use, containerised development, gaming, and everything in between.</p>
</div>

<img id="window-assortment" src="/images/screenshots/window_assortment.png" alt="VSCodium, Firefox and Warframe open">
{% end %}

{% index_section(id="get-software") %}
<div id="software-header">
    <h1>Get the software you need</h1>
    <p>Apollo comes with <a href="https://usebazaar.org">Bazaar</a>, powered by <a href="https://flathub.org">Flathub</a>, as the main way for installing and running software, so you can easily find, install and manage the apps you love alongside new ones to fall in love with.</p>
</div>

<img id="bazaar-screenshot" src="/images/screenshots/bazaar.png" alt="The Bazaar software store">

<p>Beyond that, Apollo comes with <a href="https://distrobox.it">Distrobox</a>, making it easy to install and run software for a variety of distros, including but not limited to Fedora, Ubuntu and Arch. We also include <a href="https://brew.sh">Homebrew</a> for installing CLI software and Podman and Docker for running containerised software.</p>
{% end %}