# [CS50 Lecture 1](https://www.youtube.com/watch?v=8mAITcNt710&ab_channel=freeCodeCamp.org) Study Notes

## Binary and Base Systems
Decimal is the number system taught in early mathematics, it comprises of the digits from **0 - 9**.

An example of how a decimal number is actually understood by modern mathematics is the following:

`524 = 5 x 10^2 + 2 x 10^1 + 4 x 10^0`

The reason for this comes from how number systems work, there are a total of **10** digits which can be written using decimal format, we therefore consider this format to be a base **10** number system. This means that when we write a number in decimal, the value of each digit is in turn the product of multiplying itself with **10** raised to the power of its index. It is important to note that the indexes of written digits start from **0** and work backwards such that the last digit of a number will have index **0** and the first digit will have an index equal to the total number of digits minus **1**.

Knowing this we can now determine how binary should and **does** infact work, we know that binary comprises of the digits **0** and **1** which is a total of **2** digits. This means that to calculate the value of each digit in a binary number we multiply itself with **2** raised to the power of its index.  An example is shown below.

`1010 = 1 x 2^3 + 0 x 2^2 + 1 x 2^1 + 0 x 2^0`

The value of the binary number **1010** in decimal is therefore the following.

`1 x 8 + 0 + 1 x 2 + 0 = 10`
