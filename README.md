void main () {
  
  plus (7,5);
  
  minus (8,8);
  
  multiply (2,2);
  
  divide (9,0);
  
  String a = "hello world";
  
  int number = 5;
  
  int room = 3; 
  
  int floor = 6;
  
  double bin = 7.25;
  
  print (number - room + bin);
  
  plus (3,8);
  
  isAlcoAllowed (18);
  
  areYouTooFatForThisFlight (-5); 
  
  toRentAFlatWithAnimals (2);
  
}

void plus (a,b) {
  
  print (a+b); 
  
}

void minus (a,b) {
  
  print (a-b);
  
}

void multiply (a,b) {
  
  print (a*b);
  
}

void divide (a,b) {
  
  if (b==0) {
    
    print ("error");
    
  } else {
    
    print (a/b);
    
  }
  
} 

void isAlcoAllowed (age) {
  
  if (age<18) {
    
    print ("not allowed");
    
  }
  
  if (age>18) {
    
    print ("allowed");
    
  }
    
  if (age==18) {
    
    print ("allowed");
    
  }
  
  
}

void areYouTooFatForThisFlight (kg) {
  
  if (kg>100) {
    
    print ("Sorry, we cannot put you on this fligh");
    
  } else {
      
      print ("Welcome to the flight!");
   
  }
  
  if (kg<2) {
    
    print ("Are you alive if your weight is ${kg}?");
    
  }
  
}

void toRentAFlatWithAnimals (quantity) {
  
  if (quantity<2) {
    
    print ("Welcome fluffy creature!");
    
  }
  
  if (quantity>2) {
    
    print ("Sorry, too many pets for this flat");
  
  }
  
  if (quantity==2) {
    
    print ("I love animals, welcome home!");
    
  }
  
  /*Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam tempus 
   * gravida ante in pharetra. In enim turpis, 
   * molestie in posuere vel, cursus id dui*/
  
  /// hkhjgf ffjhgb

}
