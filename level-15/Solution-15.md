
# Solution #15

## GRID GARDEN

You can also use grid-column and grid-row together to span larger areas within the grid. Give it a try!

### Code: 

```



```

#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
    grid-row: 1 /6; 
    grid-column: 2 / 6; 
}