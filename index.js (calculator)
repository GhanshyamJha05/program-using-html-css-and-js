let input=document.querySelector("#inputBox")
let buttons = document.querySelectorAll('button');

let string = "";
let arr = Array.from(buttons);
arr.forEach(button => {
    button.addEventListener('click', (e) =>{
        // input.value=e.target.value;
        if(e.target.value == '='){
            string = eval(string);
            input.value = string;
        }

        else if(e.target.value== 'AC'){
            string = "";
            input.value = string;
        }
        else if(e.target.value == 'DEL'){
            string = string.substring(0, string.length-1);
            input.value = string;
        }
        else{
            string = string + e.target.value;
            input.value = string;
        }
        
    })
})
