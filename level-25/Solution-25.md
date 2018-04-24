
# Solution #25

## GRID GARDEN

Now there is a 75 pixel column of weeds on the left side of your garden. 3/5 of the remaining space is growing carrots, while 2/5 has been overrun with weeds.

Use grid-template-columns with a combination of px and fr units to make the necessary columns.

### Code: 

```
    #garden {
        display: grid;  
        grid-template-columns: 75px 3fr 2fr;
        grid-template-rows: 100%;
    }
```