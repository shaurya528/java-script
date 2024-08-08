const array1 = ['hii', 'byy', 'speec', 'search', 'byy'];
function find(){
  let index = -1
  for (i = 0; i < array1.length; i++) {
    if (array1[i] === 'byyit') {
      index = i;
      break;

    }
  }
  return index;
}

console.log(find());

