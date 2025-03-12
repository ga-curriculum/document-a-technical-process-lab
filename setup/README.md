<h1>
  <span class="headline">Documenting A Technical Process Lab</span>
  <span class="subhead">Setup</span>
</h1>

## Setup

Open your Terminal application and navigate to your <code class="filepath">~/code/ga/labs</code> directory:

```bash
cd ~/code/ga/labs
```

### Create and clone a GitHub repo

Make a new repository on [GitHub](https://github.com/) named `documenting-a-technical-process-lab`.

Clone a copy of your remote repo locally by using the `git clone` command:

```bash
git clone https://github.com/<your-username>/documenting-a-technical-process-lab.git
```

Replace `<your-username>` (including the `<` and `>`) with your GitHub username before you run this command.

### Launch in VS Code

Next, `cd` into the cloned directory, <code class="filepath">documenting-a-technical-process-lab</code>:

```bash
cd documenting-a-technical-process-lab
```

Create a new file named `README.md`:

```bash
touch README.md
```

This file will be used to write your documentation.

Open the contents of the directory in VS Code:

```bash
code .
```

Ensure you frequently stage, commit, and push your changes as you draft your documentation for this assignment.

## Markdown basics

Markdown files are among the most popular ways to create and distribute technical documentation. At this point, you should be familiar with Markdown syntax and have likely written a few Markdown files. However, regardless of your exposure to it, it's a fairly straightforward skill to master; think HTML, ***(a markup language similar to Markdown)*** but simpler.

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
