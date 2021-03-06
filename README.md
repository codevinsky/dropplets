Dropplets
=========

> [v1.0.7](#version-107)

Dropplets is a minimalist **Markdown** blogging platform focused on delivering just what you need in a blogging solution, but absolutely nothing you don't. When it comes to basic blogging, all you really want to do is write & publish which is where Dropplets excels. It's databaseless, so it installs on any server in just about 30 seconds. 

## What's Markdown?
Markdown is a text formatting syntax inspired on plain text email. It is extremely simple, memorizable and visually lightweight on artifacts so as not to hinder reading.

> The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it's been marked up with tags or formatting instructions.

## Getting Started
- [Installation](#installation)
- [Writing Posts](#writing-posts)
- [Publishing Posts](#publishing-posts)
- [Editing Posts](#editing-posts)
- [Changing Settings](#changing-settings)
- [Changing Templates](#changing-templates)
- [Changelog](#changelog)
- [License](#license)

## Installation
Dropplets is compatible with most server configurations and can be typically installed in under a minute using the few step-by-step instructions below:

1. Download the latest version here on [GitHub](https://github.com/circa75/dropplets/archive/master.zip) and then extract the downloaded zip file.
3. Upload the entire contents of the extracted zip file to your web server wherever you want Dropplets to be installed. 
4. Pull up your site in any modern web browser and follow the installation prompts. For instance, if you uploaded Dropplets to **yoursite.com**, load **yoursite.com** in your browser to finish the installation.

## Writing Posts
With Dropplets, you write your posts offline (using the text or Markdown editor of your choice) in Markdown format. Here's a handy [syntax guide](https://github.com/circa75/dropplets/wiki/Markdown-Syntax-Guide) if you need a little help with your Markdown skills. All posts for Dropplets **MUST** be composed using the following format:

    # Your Post Title
    - Post Author Name (e.g. "Dropplets")
    - Post Author Twitter Handle (e.g. "dropplets")
    - Publish Date in YYYY/MM/DD Format (e.g. "2013/04/28")
    - Post Category (e.g. "Random Thoughts")
    - Post Status (e.g. "published" or "draft")

    Your post text starts here. 
    
All posts must also be saved with the **.md** file extension. For instance, if your post title is **My First Blog Post**, your post file should look like this:

    my-first-blog-post.md

Some templates include the ability to add a post image or thumbnail along with your post in which should match your post file name like this:

    my-first-blog-post.jpg

Post file names are used to structure post permalinks on your blog. So, a post file saved as **my-first-blog-post.md** will result in **yoursite.com/my-first-blog-post** as the post permalink.

## Publishing Posts
After you've finished writing your post offline, you can then publish your post within the Dropplets Dashboard using these few steps:

1. Login to your Dropplets Dashboard (e.g. **yoursite.com/dashboard/**) using the password you created during the installation and setup process.
2. Drag and drop your post file onto the ***droplet*** in the center of your dashboard.

## Editing Posts
Simply re-upload your edited post file within the Dropplets Dashboard using the steps above. Doing this will automatically overwrite the existing post and publish your new edits. To delete a post, change the **Post Status** at the top of your post file to **draft**.

## Changing Settings
To change your blog settings, login to your Dropplets Dashboard (e.g. **yoursite.com/dashboard/**) using the password you created during the installation and setup process and then click the settings icon to the left of the home icon. This will load the settings panel where you will be able to change all of your blog settings including your password.

## Changing Templates
To change your blog template, login to your Dropplets Dashboard (e.g. **yoursite.com/dashboard/**) using the password you created during the installation and setup process and then click the templates icon to the right of the home icon. This will load the templates panel where you will be able to browse and change your blog template.

## Changelog

### Version 1.0.7
- **NEW**: Any plugin added to the "plugins" directory is now auto-included.
- **REVISED**: Post and index caching has been re-implemented with cache invalidation when a new post has been published.
- **FIXED**: You can now install Dropplets within a sub-directory.
- **FIXED**: Post date and title not being set in RSS.
- **FIXED**: Header and footer inject errors on install.
- **FIXED**: Removed duplicate feed links within the "panels" header.

### Version 1.0.6
- **NEW**: Password recovery integration.

### Version 1.0.5
- **NEW**: Open Graph and Twitter Card meta tag support.
- **REVISED**: Improved post cache.
- **REVISED**: Generate .htaccess on install.
- **REVISED**: Added SHA1 password hashing.
- **FIXED**: Header redirects for saving settings, publishing posts and changing templates.
- **FIXED**: Dashboard shouldn't be accessible prior to installation.

## License
Copyright (c) 2013 Circa75 Media, LLC

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.