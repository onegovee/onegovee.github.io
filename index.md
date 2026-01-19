---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
[About](./about.md)  
[Welcome to Jekyll](./_posts/2025-05-04-welcome-to-jekyll.markdown)  

{% if site.bluesky_username %}
<a href="https://bsky.app/profile/{{ site.bluesky_username }}" target="_blank">
  <img src="https://upload.wikimedia.org/wikipedia/commons/7/7a/Bluesky_Logo.svg" alt="Bluesky" width="18" height="18">
</a>
{% endif %}