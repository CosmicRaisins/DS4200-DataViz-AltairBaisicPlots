## DS4200 Information Visualization Assignment 5

Assignment 5: Altair Basic Plots
For this assignment, 3 basic visualizations for information related to Netflix movies and TV shows was created using the Altair library for python on Jupyter Notebook.

### Submission 1: Simple Visulization

This is a simple viz created with Altair.
![simpleViz](/images/simpleViz.png)

Source:
```markdown
### simple visualization

# creating viz
alt.Chart(df).mark_bar().encode(
    x = 'count()',
    y = 'type',
# setting viz title
).properties(
    title = "Number of Titles on Netflix by Types",
    height = 200
).configure_bar(
    color = "#E50914",
    height = 50
)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/CosmicRaisins/basic-altair-viz/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
