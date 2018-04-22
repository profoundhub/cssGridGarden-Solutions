
# Solution #22

## GRID GARDEN

grid-template-columns doesn't just accept values in percentages, but also length units like pixels and ems. You can even mix different units together.

Here, set three columns to 100px, 3em, and 40% respectively.

### Code: 

```
#garden {
    display: grid;
    grid-template-columns: 100px 3em 40%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}
```