---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
[About](./about.md)  
[Welcome to Jekyll](./_posts/2025-05-04-welcome-to-jekyll.markdown)  

{% if site.bluesky_username %}
<a href="https://bsky.app/profile/{{ site.bluesky_username }}" target="_blank">
  <img alt="Updated Bluesky logo, published February 2024." src="./_assets/Bluesky_Logo.svg.png"> width="18" height="18">
</a>
{% endif %}