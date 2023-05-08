# TypeScriptLab

# Java script

class Dog {
  constructor(name, breed) {
    this.Name = name;
    this.Breed = breed;
  }

  Bark() {
	return "Woof!";
  }
}

let dogBreeds = ["Labrador", "Golden Retriever", "Bulldog"];
function GetRandonBree(breeds)
{
  return breeds[Math.floor((Math.random()*breeds.length))];
}
