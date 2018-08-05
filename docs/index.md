---
title: phpSmug
homepage: true
layout: page
---

# phpSmug 

{% capture my_include %}{% include installation.md %}{% endcapture %}
{{ my_include | markdownify }}

{% capture my_include %}{% include usage.md %}{% endcapture %}
{{ my_include | markdownify }}

{% capture my_include %}{% include authentication.md %}{% endcapture %}
{{ my_include | markdownify }}

{% capture my_include %}{% include private-images.md %}{% endcapture %}
{{ my_include | markdownify }}

{% capture my_include %}{% include uploading.md %}{% endcapture %}
{{ my_include | markdownify }}

{% capture my_include %}{% include other.md %}{% endcapture %}
{{ my_include | markdownify }}

---

# Requirements & Installation](installation.md)
# [Usage](usage.md)
  - Basic Usage
  - More In-depth Usage Details
    - Instantiating the Client
    - Interacting with the SmugMug API
      - GETting Information
      - Making Changes
      - Probing the API
# [Authentication](authentication.md)
# [Display Private Images](private-images.md)
# [Uploading & Replacing Images](uploading.md)
  - Upload a Local Image
  - Upload an Image from a URL
  - Replacing Images
# [Other Notes](other.md)
  - Access SmugMug via a Proxy
  - Examples

You can also view all of the documentation in this repository at http://phpsmug.com/docs/.
