
# Solution #13

## GRID GARDEN

Now give the shorthand property grid-row a try.

### Code: 

```

#garden {
  display: grid;
  grid-template-columns: 20% 20% 20% 20% 20%;
  grid-template-rows: 20% 20% 20% 20% 20%;
}

#water {
  grid-row: span 3 / 6;
}

```

