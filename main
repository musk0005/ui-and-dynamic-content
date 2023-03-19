
// store the content of a paragraph in a variable
let ui = document.getElementById("user-input");

// accessing empty div
let dc = document.getElementById("dynamic-content");

// define event-target-object
let btn = document.getElementById('add');

//let store = document.getElementById('list');

let errormsg = document.getElementById('error');

// create event-handler
function addui(){
    // create a paragraph element
    let pg = document.createElement("li");

    // make sure innerText of the paragraph is the value of the variable content
    if (ui.value!='') { 
        let item = ui.value;
        pg.textContent = item;
        dc.appendChild(pg);
        errormsg.innerText='';
        ui.value ='';
        

    } else {
        errormsg.innerText="Nothing Entered";
    }


}


