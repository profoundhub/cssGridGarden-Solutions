
# Solution #28

## GRID GARDEN

Your garden is looking great. Here you've left a 50 pixel path at the bottom of your garden and filled the rest with carrots.

Unfortunately, the left 20% of your carrots have been overrun with weeds. Use CSS grid one last time to treat your garden.

### Code: 

```

    #garden {
        display: grid;
        grid-template: 5fr 50px / 20% 1fr;
    }

```