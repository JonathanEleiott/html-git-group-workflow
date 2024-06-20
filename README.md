# HTML and more Git Workflow

## HTML

- Structure for your website
- elements -> what the browser reads and displays to the user
  - tags
    - name
    - opening
    - closing
  - content
- general structure
  - html -> contains all other elements
  - head -> information that the user will NOT see on the page (metadata)
  - body -> information that will be displayed to the user on the page
  - title -> displayed in the browser's tab

- formatting "rules"
  - HTML files should be named in lowercase and separated by hyphens
  - convert tabs to spaces
  - avoid leaving trailing spaces
  - elements inside of other elements should be indented one time (2 spaces)

- semantic elements -> named based on what is inside of them
  - header -> top of the page and contains logos, introductory content, navigation
  - main -> between the header and the footer -> main content (articles, information, products, etc.)
  - footer -> at the bottom containing contact info, special links, back to top link
  - h1-h6 -> header 1 (title) (largest) - header 6 (smallest)
  - nav -> navigation - nav bars
  - a -> hyperlink (anchor tag)
  - section/articles -> grouping of content
  - img -> shows an image
  - ol/ul -> ordered list (numbered) / unordered list (bullet points)
    - li -> list item
  - p - paragraph

- non-semantic elements
  - div -> divider
  - span

- advantages of semantic HTML
  - Search Engine Optimization (SEO)
  - Screen Readers
  - Working with humans

- attributes - give additional for the element

- comments
  - do not display in the browser
  - used to be used before semantic HTML
  - should explain WHY the code is there, not WHAT it's doing
  - used to test portions of your code
- troubleshooting and debugging
  - ALWAYS write and test your code as you go!!!
  - are you missing a closing tag
  - are there spelling errors
  - comment out certain parts of the code to find the broken code

Chrome Dev Tools - function F12 or right click + inspect

## More Git Workflow

- Merge Conflicts
  - happens when two people change the same file without pushing/pulling the changes first

- Branches
  - git checkout -> changes branches
    - -b <feature-name> -> create a new branch
  - allow working on a feature without messing up the main branch
  - very important when working in groups

- Pull Requests
  - allow for a second set of eyes to catch any bugs or mistakes
  - 1st Person -> GitHub -> Make a Pull Request (at the top)
  - 2nd Person -> GitHub -> Reviews the commits on the Pull Request -> Approve or tells Person 1 to make changes first
