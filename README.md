# HNG-i8

//Simple JavaScript program
let x;

function handle_click() {
    if (x==1) {
        document.getElementById("show").style.display="none";
        return x=0;
    }
    else {
        document.getElementById("show").style.display="inline";
        return x=1
    }
} 
