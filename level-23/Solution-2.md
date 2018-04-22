
# Solution #23

## GRID GARDEN
Grid also introduces a new unit, the fractional fr. Each fr unit allocates one share of the available space. For example, if two elements are set to 1fr and 3fr respectively, the space is divided into 4 equal shares; the first element occupies 1/4 and the second element 3/4 of any leftover space.

Here, weeds make up the left 1/6 of your first row and carrots the remaining 5/6. Create two columns with these widths using fr units.


### Code: 

```

#garden {
  display: grid;

grid-template-columns: ;
  grid-template-rows: 20% 20% 20% 20% 20%;
}
```