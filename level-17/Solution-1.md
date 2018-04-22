
# Solution #17

## GRID GARDEN

How about multiple items? You can overlap them without any trouble. Use grid-area to define a second area that covers all of the unwatered carrots.

#garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
}

#water-1 {
    grid-area: 1 / 4 / 6 / 5;
}

#water-2 {
    grid-area: 2 / 3 / 5 / 6;
}