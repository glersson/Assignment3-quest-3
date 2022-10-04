void main() { 
var sum = 0;
print ("Input five numbers and we will find the avarage of the sum"); 
for (int i = 0; i < 5; i++) { 
var num = stdin.readLineSync();
int num1 = int.tryParse(num); 
print ("-----------"); 
sum+=num1; } 
print ("Total is : ${sum}"); 
print ("The avarage of that number is :${sum/5}"); }
