# TypeScriptLab
# C#

public class Dog
{
	public string Name { get; set; }
	public string Breed { get; set; }

	public Dog(string name, string breed)
	{
    	Name = name;
    	Breed = breed;
	}

	public string Bark()
	{
    	return "Woof!";
	}
}

string[] dogBreeds = new string[] { "Labrador", "Golden Retriever", "Bulldog" };

public string GetRandomBreed(string[] breeds)
{
	Random random = new Random();
	int index = random.Next(breeds.Length);
	return breeds[index];
}


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
let dogBreeds = new Array("Labrador", "Golden Retriever", "Bulldog");
function GetRandomBreed(dogbreeds) {
    let index;
    index = Math.floor(Math.random() * dogbreeds.length);
    return index;
}
let indexnum = GetRandomBreed(dogBreeds);


# Type Script

class Dog
{
	Name: string;
	Breed: string;

	constructor(name: string, breed: string)
	{
		this.Name = name;
		this.Breed = breed;
	}

	Bark() {
		return "Woof!";
	}

	
} 

let dogBreeds: string[] = new Array ("Labrador", "Golden Retriever", "Bulldog");

function GetRandomBreed(dogbreeds:String[]) {
	let index: number;
	index = Math.floor(Math.random() * dogbreeds.length);	
	return index;
}


let indexnum = GetRandomBreed(dogBreeds);
