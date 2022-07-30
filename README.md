# Day--3 - Tasks

//Question--1--For the given JSON iterate over all for loop (for,for in)

//For

var json = {
   jsonData:  [
       {one: [11, 12, 13, 14, 15]},
       {two: [21, 22, 23]},
       {three: [31, 32]}
   ]
}; 
for (var i=0; i<json.jsonData.length; i++) {
   for (var key in json.jsonData[i]) {
       for (var j= 0; j<json.jsonData[i][key].length; j++) {
           console.log(json.jsonData[i][key][j])
       }
   }
}




//for in

var me = {
   Firstname: "Rahamadullah",
   Lastname: "Babu",
   Age: 27
}; 
for (let x in me) {
   console.log(x + ": "+ me[x])
}

//Question--2--Create your own resume data in JSON format.



 var resume={
    "Name":"A.Rahamadullah",
    "Age":"27",
    "Gender":"Male",
    "Dob" :"08-02-1995",
    "Fathername":"K.Akbar Ali",
    "Address":"Pudukkottai",
    "Education":"BE.Mech",
    "Mobnum":"0123456789",
     };
  
  console.log(resume);


Question--3--REad about the difference between window,screen and document in javascript.


 window is the execution context and global object for that context's JavaScript
document contains the DOM, initialized by parsing HTML
screen describes the physical display's full screen







