# Homework-1.1.1
Homework for 10/6/2015

//Class for Houses
```java
class House {String name; int sqft; int bed;}
House me = new House()
me.name = "Vicotorian"
me.sqft = 300
me.bed = 3
House g = new House()
g.name = "Stucco"
g.sqft = 600
g.bed = 1
House b = new House()
b.name = "Standard"
b.sqft = 1000
b.bed = 3
House[] reallysmallhouses = {me; g; b;}
```

//Class for Cars
```java
class Car {String name; int mpg; int mph;}
Car me = new Car()
me.name = "Honda"
me.mpg = 30
me.mph = 180
```

//Class and Array for weird Chairs
```java
class Chair {String name; String color; int legs; int armrest;}
Chair me = new Chair()
me.name = "Satllone"
me.color = "Purple"
me.legs = 3
me.armrest = 2
Chair you = new Chair()
you.name = "Bird"
you.color = "Yellow"
you.legs = 1
you.armrest = 1.5
Chair we = new Chair()
we.name = "Oprah"
we.color = "Black"
we.legs = 2
we.armrests = 0
Chair son = new Chair()
son.name = "Jesus"
son.color = "Brown"
son.legs = 2
son.armrests = 100
Chair[] alotachairs = {me; you; we; son;}
```

//My attempt to add a loop to my Class + Array
```java
class Coffee {String type; String size; int ounces; int aweomeness}
Coffee coffee1 = new Coffee()
coffee1.type = "Mocha"
coffee1.size = "Vente"
coffee1.ounces = 16
coffee1.awesomeness = 5
Coffee coffee2 = new Coffee()
coffee2.type = "Regular"
coffee2.size = "Grande"
coffee2.ounces = 12
coffee2.awesomeness = 3
Coffee coffee3 = new Coffee()
coffee3.type = "Salty Nuts"
coffee3.size = "Small"
coffee3.ounces = 8
coffee3.awesomeness = 0
Coffee coffee4 = new Coffee()
coffee4.type = "Police"
coffee4.size = "Extra Small"
coffee4.ounces = 1
coffee4.awesomeness = -10
Coffee[] policecoffeewatchinme = {coffee1; coffee2; coffee3; coffee4;};
for(int i = 0; i < policecoffeewatchinme.length)
```
