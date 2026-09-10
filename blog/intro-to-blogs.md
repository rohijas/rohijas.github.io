No. They are entirely different mechanical concepts.

A Folder (or directory) is structural. It is exactly like a folder on your laptop. You put files inside it to keep things organized. If you want a blog section you create a folder named blog.

A Branch is an alternate timeline of your entire project. It is a version control mechanism. Engineers use branches to build and test new features without breaking the live website. Your live website runs on the main branch. If an engineer wants to test a radical new design they create a test branch. The test branch is a complete, parallel duplicate of the site. Once the design works they "merge" the test branch back into the main branch.

Here is your operational rule: Ignore branches.

Your GitHub Pages deployment is locked to your main branch. You will do all your work right there.

When you want to add a blog post you will just create a new folder.

To do this directly in GitHub's web interface:

Go to your rohijas.github.io repository.
Click Add file -> Create new file.
In the name box type blog/ (typing the forward slash automatically creates the folder).
The cursor will move to the right. Now type the file name (e.g. first-post.md).
Write your text and click Commit changes.
Keep it in one timeline. One workspace.
