
# Solution #9

## GRID GARDEN

You can also use the span keyword with grid-column-start to set your item's width relative to the end position.

### Code: 

```

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {

grid-column-start: -4;
  grid-column-end: 6;
}

```