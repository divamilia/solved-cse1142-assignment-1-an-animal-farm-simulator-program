Download Link: https://assignmentchef.com/product/solved-cse1142-assignment-1-an-animal-farm-simulator-program
<br>
In this homework, you will implement an animal farm simulator program with an object-oriented approach.

<ol>

 <li>Implement an Animal class with the following UML diagram.</li>

</ol>




<table width="312">

 <tbody>

  <tr>

   <td width="26"> </td>

   <td width="286">Animal</td>

  </tr>

  <tr>

   <td width="26">–––––</td>

   <td width="286">name : StringlegNumber: int age: intpregnancyPerYear: int numberOfOffsprings: int</td>

  </tr>

  <tr>

   <td width="26">++++</td>

   <td width="286">Animal (name: String, age: int) sayGreeting() : void reproduce() : void toString() : String</td>

  </tr>

 </tbody>

</table>







<ul>

 <li>An Animal object represents an animal with a unique name, leg number, age, pregnancy per year and number of offsprings per pregnancy.</li>

 <li>sayGreeting method should print “Have nothing to say!” on the screen.</li>

 <li>reproduce method should print “None of your business!!” on the screen.</li>

 <li>toString method returns a string containing name, age and leg number of the Animal.</li>

</ul>

An example string as the following:

My name is Cinnamon!

I am 3 years old! I have 4 legs!

<ul>

 <li>Access and modifier methods are not shown in the UML diagram for simplicity. However you are supposed to implement these methods as well.</li>

</ul>







<ol start="2">

 <li>Implement a Bird class with the following UML diagram.</li>

</ol>




<table width="244">

 <tbody>

  <tr>

   <td width="26"> </td>

   <td width="217">Bird</td>

  </tr>

  <tr>

   <td width="26"> </td>

   <td width="217"> </td>

  </tr>

  <tr>

   <td width="26">++++</td>

   <td width="217">Bird (name:String, age:int)fly(): void reproduce(): void omnivore(): void</td>

  </tr>

 </tbody>

</table>







<ul>

 <li>Bird class extends Animal class. In Bird class’s constructor, you are supposed to call the Animal class’s constructor.</li>

 <li>fly method prints “I can fly to the endless skies!” on the screen.</li>

 <li>You should override reproduce method to print “I lay eggs!” on the screen.</li>

 <li>omnivore method prints “I can eat everything!” on the screen.</li>

</ul>







<ol start="3">

 <li>Implement a Mammal class with the following UML diagram.</li>

</ol>




<table width="244">

 <tbody>

  <tr>

   <td width="26"> </td>

   <td width="217">Mammal</td>

  </tr>

  <tr>

   <td width="26"> </td>

   <td width="217"> </td>

  </tr>

  <tr>

   <td width="26">++++</td>

   <td width="217">Mammal (name:String, age:int)walk(): void reproduce(): void herbivore(): void</td>

  </tr>

 </tbody>

</table>




<ul>

 <li>Mammal class extends Animal class. In Mammal class’s constructor, you are supposed to call the Animal class’s constructor.</li>

 <li>walk method prints “I can walk to the far away lands!” on the screen.</li>

 <li>You should override reproduce method to print “I give birth!” on the screen.</li>

 <li>herbivore method prints “I eat plants only!” on the screen.</li>

</ul>




<ol start="4">

 <li>Implement a Chicken class with the following UML diagram.</li>

</ol>




<table width="468">

 <tbody>

  <tr>

   <td width="26"> </td>

   <td width="442">Chicken</td>

  </tr>

  <tr>

   <td width="26">–</td>

   <td width="442"><u>count </u>: int</td>

  </tr>

  <tr>

   <td width="26">++++ </td>

   <td width="442">Chicken( name:String, age:int) sayGreeting(): void <u>getCount</u>():int<u>decrementCount</u>(): void </td>

  </tr>

 </tbody>

</table>




<ul>

 <li>A Chicken object represents a real-life chicken. It extends Bird class. In Chicken class’s constructor, you are supposed to call the super class’s constructor, set leg number to be 2, number of offsprings to be 1 and pregnancy per year to be 200.</li>

 <li>count static data field keeps the number of chickens created. You should change it appropriately.</li>

 <li>You should override sayGreetings method to print “I have nothing to say other than I am against Pigs!” on the screen.</li>

 <li>getCount method is the accessor method for the count data field.</li>

 <li>decrementCount method decrements the count data field.</li>

</ul>

<ol start="5">

 <li>Donkey class with the following UML diagram.</li>

</ol>

<table width="468">

 <tbody>

  <tr>

   <td width="26"> </td>

   <td width="442">Donkey</td>

  </tr>

  <tr>

   <td width="26">–</td>

   <td width="442"><u>count </u>: int = 0</td>

  </tr>

  <tr>

   <td width="26">++++ </td>

   <td width="442">Donkey( name:String, age:int) sayGreeting(): void <u>getCount</u>():int<u>decrementCount</u>(): void </td>

  </tr>

 </tbody>

</table>




<ul>

 <li>A Donkey object represents a real-life donkey. It extends Mammal class. In Donkey class’s constructor, you are supposed to call the super class’s constructor, set leg number to be 4, number of offsprings to be 1 and pregnancy per year to be 1.</li>

 <li>count static data field keeps the number of donkeys created. You should change it appropriately.</li>

 <li>You should override sayGreetings method to print “Life will go on as it has always gone –that is, badly!” on the screen.</li>

 <li>getCount method is the accessor method for the count data field.</li>

 <li>decrementCount method decrements the count data field.</li>

</ul>




<ol start="6">

 <li>Implement a Horse class with the following UML diagram.</li>

</ol>




<table width="468">

 <tbody>

  <tr>

   <td width="26"> </td>

   <td width="442">Horse</td>

  </tr>

  <tr>

   <td width="26">–</td>

   <td width="442"><u>count </u>: int = 0</td>

  </tr>

  <tr>

   <td width="26">++++ </td>

   <td width="442">Horse( name:String, age:int) sayGreeting(): void <u>getCount</u>():int<u>decrementCount</u>(): void </td>

  </tr>

 </tbody>

</table>




<ul>

 <li>A Horse object represents a real-life horse. It extends Mammal class. In Horse class’s constructor, you are supposed to call the super class’s constructor, set leg number to be 4, number of offsprings to be 1 and pregnancy per year to be 1.</li>

 <li>count static data field keeps the number of horses created. You should change it appropriately.</li>

 <li>You should override sayGreetings method to print “I will work harder!” on the screen.</li>

 <li>getCount method is the accessor method for the count data field.</li>

 <li>decrementCount method decrements the count data field.</li>

</ul>

<ol start="7">

 <li>Pig class with the following UML diagram.</li>

</ol>

<table width="468">

 <tbody>

  <tr>

   <td width="26"> </td>

   <td width="442">Pig</td>

  </tr>

  <tr>

   <td width="26">–</td>

   <td width="442"><u>count </u>: int = 0</td>

  </tr>

  <tr>

   <td width="26">++++ </td>

   <td width="442">Pig( name:String, age:int) sayGreeting(): void <u>getCount</u>():int<u>decrementCount</u>(): void </td>

  </tr>

 </tbody>

</table>




<ul>

 <li>A Pig object represents a real-life pig. It extends Mammal class. In Pig class’s constructor, you are supposed to call the super class’s constructor, set leg number to be 4, number of offsprings to be 12 and pregnancy per year to be 2.</li>

 <li>count static data field keeps the number of pigs created. You should change it appropriately.</li>

 <li>You should override sayGreetings method to print “All animals are equal, but some animals are more equal than others!” on the screen.</li>

 <li>getCount method is the accessor method for the count data field.</li>

 <li>decrementCount method decrements the count data field.</li>

</ul>

<ol start="8">

 <li>Implement a Raven class with the following UML diagram.</li>

</ol>




<table width="468">

 <tbody>

  <tr>

   <td width="26"> </td>

   <td width="442">Raven</td>

  </tr>

  <tr>

   <td width="26">–</td>

   <td width="442"><u>count </u>: int = 0</td>

  </tr>

  <tr>

   <td width="26">++++ </td>

   <td width="442">Raven( name:String, age:int) sayGreeting(): void <u>getCount</u>():int<u>decrementCount</u>(): void </td>

  </tr>

 </tbody>

</table>




<ul>

 <li>A Raven object represents a real-life raven. It extends Bird class. In Raven class’s constructor, you are supposed to call the super class’s constructor, set leg number to be 2, number of offsprings to be 5 and pregnancy per year to be 1.</li>

 <li>count static data field keeps the number of ravens created. You should change it appropriately.</li>

 <li>You should override sayGreetings method to print “A happy country where we poor animals shall rest forever!” on the screen.</li>

 <li>getCount method is the accessor method for the count data field.</li>

 <li>decrementCount method decrements the count data field.</li>

</ul>

<ol start="9">

 <li>Sheep class with the following UML diagram.</li>

</ol>

<table width="468">

 <tbody>

  <tr>

   <td width="26"> </td>

   <td width="442">Sheep</td>

  </tr>

  <tr>

   <td width="26">–</td>

   <td width="442"><u>count </u>: int = 0</td>

  </tr>

  <tr>

   <td width="26">++++ </td>

   <td width="442">Sheep( name:String, age:int) sayGreeting(): void <u>getCount</u>():int<u>decrementCount</u>(): void </td>

  </tr>

 </tbody>

</table>




<ul>

 <li>A Sheep object represents a real-life sheep. It extends Mammal class. In Sheep class’s constructor, you are supposed to call the super class’s constructor, set leg number to be 4, number of offsprings to be 1 and pregnancy per year to be 1.</li>

 <li>count static data field keeps the number of sheep created. You should change it appropriately.</li>

 <li>You should override sayGreetings method to print “Four legs good, two legs better!” on the screen.</li>

 <li>getCount method is the accessor method for the count data field.</li>

 <li>decrementCount method decrements the count data field.</li>

</ul>




<ol start="10">

 <li>Implement an AnimalFarm class with the following UML diagram.</li>

</ol>




<table width="468">

 <tbody>

  <tr>

   <td width="26"> </td>

   <td width="442">AnimalFarm</td>

  </tr>

  <tr>

   <td width="26">––––</td>

   <td width="442">animalList : Arraylist&lt;Animal&gt; animalNames : ArrayList&lt;String&gt; CAPACITY: int<u>numberOfAnimals </u>: int = 0</td>

  </tr>

  <tr>

   <td width="26">++++++++++++++++++</td>

   <td width="442">AnimalFarm(capacity:int) getNumberOfAnimals():int addAnimal(animal:Animal):boolean removeAnimal(name:String):Boolean printAllAnimalGreetings():voidprintOneAnimalGreeting(animal:Animal):void printAllAnimalNames():voidprintOneAnimalName(animal:Animal):voidprintAllAnimals():void nextYearPopulationForecast():int animalMovements():void eatingHabits():void sortAlphabetically():void sortBasedOnLegNumber():void sortBasedOnAge():voidsearchBasedOnName(name: String):void searchBasedOnAge(age:int):void printReport(filename:String)</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>An AnimalFarm object represents an animal farm containing animals.</li>

 <li>animalList is an ArrayList of Animal objects. It contains all animals in the animal farm.</li>

 <li>animalName is an ArrayList of String objects. It contains all animals’ names in the animal farm.</li>

 <li>CAPACITY represents the capacity of the animal farm.</li>

 <li>numberOfAnimals represent the number of animals the farm has.</li>

 <li>In the constructor of the AnimalFarm class, an animal farm with the given capacity has to be created.</li>

 <li>getNumberOfAnimals is the accessor for the numberOfAnimals</li>

 <li>addAnimal method adds the given animal to the animalList only if o there is enough room in the farm, and  o there is no animal with the same name.</li>

</ul>

It also adds the animal name to the animalName for further check. It returns true if the animal and its name are successfully added to the ArrayLists, false otherwise. If the user tries to enter an animal with the same name, then addAnimal method throws an IllegalNameException you will implement.

<ul>

 <li>removeAnimal method removes an animal from the animalList and It also decrements the counter of either Chicken, Donkey, Horse, Pig, Raven, or Sheep classes depending on the type of the removed animal. It returns true if the animal and its name are successfully removed from the ArrayLists, false otherwise.</li>

 <li>printAllAnimalGreetings method iterates on the animalList and calls printOneAnimalGreeting method with each animal on the list.</li>

 <li>printOneAnimalGreeting method calls the sayGreetings method of the animal.</li>

 <li>printAllAnimalNames method iterates on the animalList and calls printOneAnimalName method with each animal on the list.</li>

 <li>printOneAnimalName method prints the name of the animal.</li>

 <li>printAllAnimals method iterates on the animalList and calls toString method of each animal.</li>

 <li>nextYearPopulationForecast method calculates the expected population for the next year. For this purpose, it has to use the numberOfOffsprings and pregnancyPerYear for every animal in the animal farm.</li>

 <li>animalMovements method iterates on the animalList and if the animal is of type Bird, calls fly method of the animal. If the animal is of type Mammal, however, it calls the walk</li>

 <li>eatingHabits method iterates on the animalList and if the animal is of type Bird, calls omnivore method of the animal. If the animal is of type Mammal, however, it calls the herbivore</li>

 <li>sortAlphabetically method sorts the animals alphabetically based on their names <strong>without</strong> changing the original animalList and prints the sorted version on the screen.</li>

 <li>sortBasedOnLegNumber method sorts the animals increasingly based on their leg numbers <strong>without</strong> changing the original animalList and prints the sorted version on the screen.</li>

</ul>




<ul>

 <li>sortBasedOnAge method sorts the animals increasingly based on their ages <strong>without</strong> changing the original animalList and prints the sorted version on the screen.</li>

 <li>searchBasedOnName method finds and prints the animal with the given name.</li>

 <li>searchBasedOnAge method finds and prints the animals with the given age.</li>

 <li>printReport method prints the information about the animal farm on a file in the following format:</li>

</ul>







First, you will write the total number of animals in the animal farm. Then you will print every animal type separately, and print name, age and leg number attributes of each animal. You should follow the format above.




<ol start="11">

 <li>Implement an IllegalNameException class that extends Exception class. This exception will be thrown when the user tries to add an animal with an existing name.</li>

</ol>

<strong> </strong>

<ol start="12">

 <li>Write a test program with the following specifications:</li>

</ol>

<strong> </strong>

<ul>

 <li>First, it has to ask for the capacity of the animal farm and create an animal farm object with given value as capacity.</li>

 <li>Then it will print a menu as follows to perform operations:</li>

</ul>










<ul>

 <li>If the user enters 0, the program will terminate.</li>

 <li>If the user enters 1, you will print another menu for user to choose animal type</li>

</ul>

(Chicken,Pig, Donkey, etc.). After user chooses the animal type, you will ask for name and age of the animal and create an appropriate type animal with specified information and call addAnimal method of the AnimalFarm class. This is also where you will handle a possible exception. For example:










<ul>

 <li>If user enters 2, you will ask the user the name of the animal and call the removeAnimal method of the AnimalFarm</li>

</ul>




<ul>

 <li>If the user enters 3, you will print another menu for user to choose in between a search based on name or age. According to the user’s choice, you will either ask for name or age then call either searchBasedOnName or searchBasedOnAge method of the AnimalFarm For example:</li>

 <li>If the user enters 4, you will print another menu for user to choose in between a sort based on name, leg number, age or addition date. According to the user’s choice, you will call either sortAlphabetically, sortBasedOnLegNumber, searchBasedOnAge or printAllAnimals method of the AnimalFarm</li>

</ul>

For example:

<ul>

 <li>If the user enters 5, you will call the nextYearPopulationForecast method of the AnimalFarm For example</li>

 <li>If the user enters 6, you will call the animalMovements method of the AnimalFarm For example:</li>

 <li>If the user enters 7, you will call the eatingHabits method of the AnimalFarm For example:</li>

 <li>If the user enters 8, you will ask the user for a filename and call the printReport method of the AnimalFarm For example:</li>

</ul>

After each operation, this menu will be printed on the screen over again, until the user enters 0 to exit the program.


