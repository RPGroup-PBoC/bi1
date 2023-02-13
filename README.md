# [Bi 1: The Great Ideas of Biology](https://bi1.caltech.edu/) @ Caltech

This is the public repository corresponding to the website for Bi 1, the introductory undergraduate biology course at Caltech.

The website is based off of that from the 2017 edition of the class. Visiting `bi1.caltech.edu` will automatically redirect you to the most recent version (which is 2023 as of this writing). You can also append the appropriate year to view archived versions, e.g. `bi1.caltech.edu/2017` will take you to the 2017 website.

This versioning is accomplished by placing each year's content (like `_posts` and `assets`) in separate directories, and performing the redirect in the `index.html` file. Some special files and folders, such as `_data` and `_layouts`, can only be placed in the root directory -- so we do a similar kind of versioning within them.

Future iterations of the course should use a similar strategy to preserve previous version of the website in-place.
