<h1>
  <span class="headline">Documenting A Technical Process Lab</span>
  <span class="subhead">Setup</span>
</h1>

## Setup

### Overview

Before we begin this lab, let's take a few minutes to set up our lab environment. This guide will walk you through the proper folder and file setup, and we'll also have a brief refresher on Markdown syntax to help prepare you for this assignment.

### Step One: Creating Your Lab Folder

1. Create a folder:
   - On your local machine, in the same location you're using to manage today's coursework, create a folder for this lab titled: `documenting-a-technical-process-lab`.
2. Add a README.md file:
   - Inside the folder, create a new file named `README.md`.
   - You'll use this file to write your documentation.

### Step Two: Initializing a Git Repository

1. In the same terminal or command prompt session used to create your folder/file structure:
   - Make sure you're currently navigated inside your lab folder.
   - Run the command, `git init` to initialize a Git repository or "repo".
2. Stage and commit your changes:
   - Stage your `README.md` file for the first commit using the command `git add README.md`.
   - Commit the staged file with a short message using the following command for example:
     - `git commit -m "initial commit with README.md"`

### Step Three: Push to GitHub Enterprise

1. Create a new repo on GitHub Enterprise:
   - Ensure you're logged in and go to your profile for your GitHub Enterprise Account.
   - Create a new repo named after your lab folder, `documenting-a-technical-process-lab`.
2. Add your remote repo:
   - Link your local and remote repos using the following command ***(be sure to use the actual remote URL for your repo)***:
     - `git remote add origin https://git.generalassemb.ly/<your-username-goes-here>/documenting-a-technical-process-lab.git` 
3. Push your changes:
   - Push the changes to your local repo using the following command:
     - `git push -u origin main`

Great! You should be all set now. However, please ensure you frequently stage, commit and push your changes as you draft your documentation for this assignment.

## Markdown Basics

Markdown files are among the most popular ways to create and distribute technical documentation. At this point, you should be familiar with Markdown syntax and have likely written a few Markdown files. However, regardless of your exposure to it, it's a fairly straightforward and easy skill to master; think `HTML`, ***(a markup language similar to Markdown)*** but simpler.

Here are a few essential Markdown element examples you can use for creating your documentation:

### Headings

- We use `#` for headings; you can lower the level of importance by adding additional `#`s.

   ```markdown
   # Heading 1
   ## Heading 2
   ### Heading 3
   ```

As a good rule of thumb, your documentation should only have one single `#` heading; `##` and `###` are typically used as "subheadings" to separate your documentation into individual sections.

### Lists

- Numbered Lists:

   ```markdown
   1. First item
   2. Second item
   3. Third item
   ```

- Bulleted Lists:

   ```markdown
   - First item
   - Second item
   - Third item
   ```

Lists are a great way to "list" a series of steps to a process or a list of requirements or tools; you can display your list items using an ordered *(numbered)* or unordered *(bulleted)* list.

### Bold and Italics

- For **bold** text, use `**` or `__` around text:

   ```markdown
   **Bold Text**
   __Bold Text__
   ```

- For *italic* text, use `*` or `_` around text:

   ```markdown
   *Italicized Text*
   _Italicized Text_
   ```

- For ***Bold Italicized*** text, use `***` around text:

   ```markdown
   ***Italicized Text***
   ```

Using bold and italicized text formatting is an effective way to emphasize important points or reminders.

### Links and Embedded Images

- You can embed links in your markdown using `[text](url)`:

   ```markdown
   [GitHub Flavored Markdown Guide](https://guides.github.com/features/mastering-markdown/)
   ```

- Image files ***(diagrams and visual aids)*** can be embedded in your markdown using `![alt text](relative file path or url)`.

It's common to link external resources in documentation or display a visual aid; this syntax helps us do just that.

## Additional Resources

If you'd like to review additional examples and guidance using Markdown, consider reviewing the official [GitHub Flavored Markdown Guide](https://guides.github.com/features/mastering-markdown/)
