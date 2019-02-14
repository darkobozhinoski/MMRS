# Experiment Setup

## GOAL

Analyze the CAP implementation for the purpose of evaluation  with respect to mission satisfiability, safety, and run-time efficiency 
from the point of view of researchers in the context of UAV-based missions

## Design
The experiment is designed as a multi-test within object study, because it is conducted on a single object (i.e., the current implementation of CAP) across a set of subjects (i.e., a set of UAV-based missions and a set of robots’ teams).

## Research questions

**RQ1**: To what extent does the CAP implementation achieves mission completion? [mission satisfiability]
_Used metrics_:
- Number of completed tasks

**RQ2**: To what extent does the CAP implementation preserve mission safety? [safety]
_Used metrics_:
- Number of collisions
- Number of collisions between agents
- Number of collisions between agents and obstacles

**RQ3**: What is the run-time efficiency of the CAP implementation? [efficiency]
_Used metrics_:
- memory consumption (bytes)
- CPU utilization (%)
- network traffic (number of packets)
- mission execution time (milliseconds)








You can use the [editor on GitHub](https://github.com/darkobozhinoski/mmrs.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/darkobozhinoski/mmrs.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
