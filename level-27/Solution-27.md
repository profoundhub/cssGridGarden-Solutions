
# Solution #27

## GRID GARDEN

grid-template is a shorthand property that combines grid-template-rows and grid-template-columns.

For example, grid-template: 50% 50% / 200px; will create a grid with two rows that are 50% each, and one column that is 200 pixels wide.

Try using grid-template to water an area that includes the top 60% and left 200 pixels of your garden.

### Code: 

```

    #garden {
        display: grid;
        grid-template: 60% 60% 60% / 200px;
    }

    #water {
        grid-column: 1;
        grid-row: 1;
    }

```