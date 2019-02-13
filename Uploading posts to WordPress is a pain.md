# Uploading posts to WordPress is a pain!
Good god, I’ve been trying to find a better way to upload posts to WordPress instead of just copy and paste.

## Context
- I write my notes in either Apple’s Notes app or a new app I downloaded called Bear.
- My notes include simple formatting (Markdown format or similar) which includes headings (h1, h2, etc.), bold font, unordered lists, ordered lists, etc.
- I’d also like to include `code` snippets. Markdown supports this with by putting your words between two ticks `. 
- I also have check lists in these notes. It’s not so important that the check list format gets imported into the blog. But it’s nice.
- I also often include photos and screenshots of my work in line with my notes.
- After finishing writing my blog post, I would copy and paste the text into a new post on my WordPress dashboard. 

### The complication
- Copying and pasting the text from one app to another loses a lot of the formatting in my post. Lines that I put in **bold** or have given header designations (h1) are lost.
- The pictures I’ve included never upload properly with the WP console. Perhaps there’s some bug in there. I’ve spent far too long just re-uploading each picture manually into my blog posts.
- Sometimes I make updates to my notes after I’ve published my blog posts. I’d like an easy way to automatically identify the updates and make those same changes in the blog post.

### The ideal solution
I’d like the workflow to work as such:
1. I write up a blog post within my favorite editor (currently Bear).
2. With 1 click, the following happens:
	1. The post is committed to a git repository. Git provides a great, seamless way to identify updates to a text file, highlights those changes, and allows you to review the changes before committing the changes.
	2. If this is a new blog post, the post is sent from the git repository (through Github is OK) to my WordPress server and automatically creates a new post from there. 
		1. It would use the first h1 header as the title. 
		2. It would also find any tags using the hash # symbol and add them to tags.
	3. If the post already exists and this is just an update, the updated git repo would update the existing WordPress blog post.
	4. Any included images in the post would be automatically uploaded to some server, and a link to that public URL would automatically replace the image, so that the image will render Markdown format. Dropbox is first to come to mind, but any service is fine.
3. With this seamless integration, my updated notes on my computer would be easily synced to my WordPress blog post.

### What’s available
I found this WordPress plugin that automatically creates posts from Github markdown files. We’re halfway there! [Markdown to WP on Github](https://github.com/mytory/mytory-markdown)

However, the formatting is not quite there yet.
	- Tabbed unordered lists aren’t recognized
	- The check boxes look too skinny
	- Images don’t get uploaded

Perhaps this is an idea for another project?