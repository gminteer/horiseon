# Code Refactor Starter Code

[Live github.io page is here](https://gminteer.github.io/horiseon/)

Week 1 challenge, refactoring the Horiseon landing page to make use of semantic tags, simplify the CSS, and add alt tags to images.

Summary of changes:
- Moved all files from "urban-octo-telegram/Develop" to root of tree.
- Replaced div class="header" & div class="footer" with actual header/footer tags and updated CSS accordingly (removed unnecessary class attributes)
- Replaced div class="content" and div class="benefits" with section tags (left class attributes), replaced div tags within those sections with article tags.
    As part of this change, dropped class attributes from articles and simplified CSS: originally each content article and each benefit article had a unique class that had its own CSS definitions, but the definitions were identical for each content/benefit. There's now just two sets of CSS definitions for .content article and .benefit article.
- Added (blank) alt tags to the images (and got rid of an unnecessary </image> tag). The alt tags are blank because none of the images really add any information to the content -- the images in the .content articles are just stock photos and the images in the .benefits articles are meaningless icons.