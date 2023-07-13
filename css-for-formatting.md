### change font style to Reboto

```
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap'); 

  

/* changing the font as globally as possible */ 

#main-menu + div *{ 

    font-family: 'Roboto', sans-serif !important; 

} 
```

### hide filter indicator and chart menu
```
/* this hides BOTH the filter indicator and the chart menu */ 

.header-controls { 

  display: none !important; 

} 
```

### change the markdown's background from white to transparent
```
/* this turns the first markdown’s background from white to transparent */ 

.grid-content > :nth-child(1) .dashboard-component-chart-holder { 

  background-color: rgba(0,0,0,0) !important; 

} 
```

### hide grid lines in some charts for a cleaner look
```
/* this hides the grid lines in some charts */

line{ display:none !important; }
```