# Number Systems and Conversions

##### Written By: Grace Hardester

Conversion of numbers is important when working in the digital world. No matter how old or how young, if you want to work in the digital world, you need to know this information! There are lots of different ways numbers can be converted and they all have their own purpose. For this project, I am going to talk about the Decimal, Binary, Octal,and Hexadecimal.  

## Decimal

I started with the decimal system because it is what we grow up learning as kids, so we are most familiar with it. It is also known as the base-10 system, which means it represents any number using 10 digits: 0 through 9. When first learning numbers, we learn about the one's place, ten's place, hundredth's place, and so on. The reason they are called those place holders is because of this: 


| Base-10 | Outcome          |
|---------|------------------|
|   10^0  |   1's place      | 
|   10^1  |   10's place     | 
|   10^2  |   100's place    |  
|   10^3  |   1,000's place  | 
|   10^4  |   10,000's place |

![Here is an example of a number showing how the base-10 is used](https://slideplayer.com/slide/6839307/23/images/4/Decimal+Numbering+System.jpg)

## Binary
The Binary system is known as the base-2 system, and is only composed of 0's and 1's. Binary is most commonly found in computer technology. The reason binary only has two numbers is because it is much easier for a computer to analyze two numbers versus ten. In binary, the zero acts as an "off switch" and the one acts as the "on switch". So, whenever the number one is present in the binary number presented, that number is added to the total, while the zero is not. Just like the decimal chart above, the binary can be written out as a chart as well. 

| Base-2:             | 2^7 | 2^6 | 2^5 | 2^4 | 2^3 | 2^2 | 2^1 | 2^0 |           |
|---------------------|-----|-----|-----|-----|-----|-----|-----|-----|-----------|
| Outcome:            | 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |           |
| Example in Binary:  | 0   | 0   | 1   | 1   | 0   | 0   | 0   | 1   | TOTAL: 49 |

In this chart there are lots of things going on:
1. The top row explains the base-2 system. So, instead of using 10 to the something power, we are now using 2. The base-2 system also works the same way as the base-10 system with the smallest number to the farmost right. 
2. The middle row computes the top row and gives you the answer.
3. The bottom row is an example of a binary number. The way you look at this number is 1's being the "on switch" and 0's being the "off switch". So, to compute this you will add up all of the numbers where there is a 1: 1+16+32 for a total of 49. The answer 49 is in decimal form. 

## Octal
Octal is known as the base-8 system and contains the digits 0,1,2,3,4,5,6,7. It is not as common as it used to be, but can be used when the number of bits is a multiple of three. Here is an example of converting octal to decimal. Today, hexadecimal is usually used instead of octal.
![Here is an example of a number showing how the base-8 is used](https://media.geeksforgeeks.org/wp-content/uploads/octToDec.png)

## Hexadecimal
Hexadecimal is known as the base-16 system and is composed of 0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F. Only single digit numbers are allowed when using Hexadecimal, so because of that, A through F represents the two digit numbers 10 through 15: 
* A=10, B=11, C=12, D=13, E=14, F=15 <br />
We use hexadecimal because instead of representing a number with 8 digits, we can do it with two. For example, in order to represent the number 255 in Binary you would need eight 1s (11111111), but in hexicadecimal, it only takes two values (FF). The chart below will explain how to convert from Hexadecimal to Binary.

| Base-16  | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7  | 8 | 9 | A  | B  | C  | D  | E  | F  |
|----------|---|---|---|---|---|---|---|----|---|---|----|----|----|----|----|----|
| Decimal: | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 17 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 |

#### Example:
1. Hexadecimal Value: 2A5

|       2       |         A        |     5     |
|:-------------:|:----------------:|:---------:|
|      16^2     |       16^1       |    16^0   |
| 256 x 2 = 512 |   16 x 10 = 160  | 1 x 5 = 5 |
|     512 +     |      160 +       |     5     |
|               | = 677 in decimal |           |



## In Conclusion...
In conclusion, number systems are very important and necessary when working in the digital world and with computers. Although all of my examples show how to convert to decimal, you can also convert to any of the other systems: binary, octal, decimal, and hexadecimal. Down below is a link to show how all of the different systems relate. 

[More Help on Converting](https://www.tutorialspoint.com/computer_logical_organization/number_system_conversion.htm)
