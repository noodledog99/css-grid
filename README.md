# css-grid
Note
 - grid-template-columns: 33.3% 33.3% 33.3%; is mean column 1 width 33.3%, column 2 width 33.3% and column 3 width 33.3%
 - grid-template-columns: repeat(3,1fr); is that mean 3 column
 - grid-grab: sets the gaps (gutters) between rows and columns
 ```
    (1) grid-column-start: 1;
        grid-column-end: 3; 
    (2) grid-column: 1/3;
    
    (1) and (2) it's the same
 ```
 ```
    (1) grid-column: 1/4;
    (2) grid-column: span 3;

    (1) and (2) it's the same thing
 ```