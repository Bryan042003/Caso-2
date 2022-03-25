# Caso-2
Quickosrt:
//Example
//{1,2,3,4,5,6,7,8,9,10}
//{1,2,3,4,5,6,7,8,9,10}
//                    p
//{1,2,3,4,5,6,7,8,9,10}
// i               j  p
//{1,2,3,4,5,6,7,8,9,10}
// i             j p
//{1,2,3,4,5,6,7,8,9,10}
// i           j p
//{1,2,3,4,5,6,7,8,9,10}
// i         j p
//{1,2,3,4,5,6,7,8,9,10}
// i       j p
//{1,2,3,4,5,6,7,8,9,10}
// i     j p
//{1,2,3,4,5,6,7,8,9,10}
// i   j p
//{1,2,3,4,5,6,7,8,9,10}
// i j p
//{1,2,3,4,5,6,7,8,9,10}
//   p
//1
//2,3,4,5,6,7,8,9,10
//1,2,3,4,5,6,7,8,9,10
//O(n)

//Explanation
//As can be seen in the various tests carried out, it is possible to notice that in certain cases
//the algorithm can behave in the form O(nlog(n)) in the best case where the
//pivot ends up in the middle of the list and then splits into subcases of equal size
//In the worst case it is possible to notice that the algorithm can behave in the form
//O(n^2) locating the pivot at either end and therefore making larger
//runs the program to find out the midpoints of the pivot and power of this
// way to order the list.

Insertion sort:
//Implementation example
//{ 1,2,3,4,5,6,7,8,9,10 }
//In this case it would have an O(n) behavior
//since they are all sorted you don't need to move any element in
//the list and just compare one with the next
//in this case compare 1 with 2 but since 2 is greater than one
//leave it in the same place and then compare the 2 with it and as the 3
// it is the older of the two so it leaves it in the same place, then
//compare the 3 with the 4 and since the 4 is greater then it leaves it in the same
// place, and so on until you reach number 10.

//example with worst case
//{ 10,9,8,7,6,5,4,3,2,1 }
//Compare the first number with the second in this case the first number
//it would be the 10 that compares it with the 9 and since the 9 is less than 10
//then put it in the previous position where the 10 was and the 10 where the 9 was
//now compare the 10 to the 8 and since the 8 is less than 10 then move the 10 one space and
//also compares 8 with 9 and since nine is greater, 8 is first
//and so on until the entire list is accommodated.

//Explanation:
//As can be seen in the various tests carried out, it is possible to notice that in certain cases
//the algorithm can behave in the form O(n^2) when the order of the elements in the
// list originates from descending order and that the values to the left of the number taken
//for reference they are older and this would become one of the worst possible cases.
//And the algorithm would behave inversely when all the elements are ordered in the same way
//ascending form and would tend to behave in the form O(n) and would be one of the best possible cases,
//because you could also have all the same elements in the list and get the same behavior and
//almost ordered case can be seen represented.
