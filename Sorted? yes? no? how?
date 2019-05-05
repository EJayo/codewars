//Kata: Sorted? yes? no? how?

function isSortedAndHow(array) {
  var arrAsc = array.slice().sort(function(a, b){return a-b})
  var arrDes = array.slice().sort(function(a, b){return b-a})

  if(array.toString()==arrAsc.toString()){
    return "yes, ascending"
  }
  else if(array.toString()==arrDes.toString()){
    return "no, descending"
  }
  else{
    return "no"
  }
}
