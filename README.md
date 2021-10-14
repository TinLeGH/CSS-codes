# CSS-codes

.parent {
    width: 100vw; /* 'vw' means 'view width', browser's resolution */
    height: 100vh; /* 'vh' means 'view height' */
    /* padding: 1.25rem; */
    background-color: #fafafa;
    display: flex; /* flex to display flex, inline-flex for same line if there's space */
    flex-flow: row wrap; /* flex-flow: flex-direction flex-wrap*/
    /*
        flex-direction: row | row-reverse | column | column-reverse;
        flex-wrap: wrap | nowrap | wrap-reverse;
    */
    justify-content: space-evenly; /* flex-start | flex-end | center | space-around | space-between | space-evenly; affect x-axis if row, y-axis if column
    */
    align-items: flex-start; /* flex-start | flex-end | center | stretch | baseline */
    align-content: flex-start; /* flex-start | flex-end | center | space-between | space-around | space-evenly | stretch | baseline */
}
