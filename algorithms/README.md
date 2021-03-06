# Algorithms for BigInteger

## Sequential Algorithms

### Operations [6]

1. `BigInteger abs()` - returns the absolute value of the BigInteger

2. `BigInteger add( BigInteger val )` - returns the value of the two BigIntegers added together

3. `BigInteger and( BigInteger val )` - returns the value of the two BigIntegers anded together

4. `BigInteger andNot( BigInteger val )` - returns the value of two BigIntegers notanded together

5. `int bitCount()` - returns number of bits in two's complement version of the BigInteger that are different from sign bit

6. `int bitLength()` - returns number of bit in minimal two's complement version of the BigInteger excluding the sign bit

7. `BigInteger clearBit( int n )` - a BigInteger with the appropriate bit clear on the BigInteger

8. `int compareTo( BigInteger val )` - comparison methods for less than, equal, or greater than

9. `BigInteger divide( BigInteger val )` - returns BigInteger that has a value of the designated BigInteger / val

10. `BigInteger divideAndRemainder( BigInteger val )` - returns two BigInteger with the value of one BigInteger divided by val along with the remainder of the operation

11. `double doubleValue()` - converts the BigInteger into a value of double

12. `boolean equals( Object x )` - compares two BigInteger for equality (==)

13. `BigInteger flipBit( int n )` - returns the BigInteger where the value is equal to the appropriate bit flipped of this BigInteger

14. `float floatValue()` - converts the BigInteger into a value of a float

15. `BigInteger gcd( BigInteger val )` - returns the greatest common divisor of the two BigInteger values

16. `int getLowestSetBit()` - 

17. `int hashCode()`

18. `int intValue()`

19. `boolean isProbablePrime( int certainty )`

20. `long longValue()`

21. `BigInteger max( BigInteger val )`

22. `BigInteger min( BigInteger val )`

23. `BigInteger mod( BigInteger val )`

24. `BigInteger modInverse( BigInteger val )`

25. `BigInteger modPow( BigInteger exponent, BigInteger m )`

26. `BigInteger multiply( BigInteger val )`

27. `BigInteger negate()`

28. `BigInteger nextProbablePrime()`

29. `BigInteger not()`

30. `BigInteger or( BigInteger val )`

31. `BigInteger pow( int exponent )`

32. `static BigInteger probablePrime( int bitLength, Random rnd )`

33. `BigInteger emainder( BigInteger val)`

34. `setBit( int n )`

35. `shiftLeft( int n )`

36. `shiftRight( int n )`

37. `int signum()`

38. `BigInteger subtract( BigInteger val )`

39. `boolean testBit( int n )`

40. `byte[] toByteArray()`

41. `String toString()`

42. `String toString( int radix )`

43. `static BigInteger valueOf( long val )`

44. `BigInteger xor( BigInteger val )`

## Parallel Algorithms

## Sources Cited:

1. Bassil, Youssef, and Aziz Barbar. "Sequential and Parallel Algorithms for the Addition of Big-Integer Numbers." arXiv preprint arXiv:1204.0232 (2012).

2. The GNU Multiple Precision Arithmetic Library. https://gmplib.org

3. bigint library. https://github.com/kasparsklavins/bigint

4. BigInteger library. https://github.com/panks/BigInteger

5. TTMath: Bignum C++ Library. http://www.ttmath.org/

6. BigInteger, Oracle. Retrieved November 6, 2016. http://docs.oracle.com/javase/7/docs/api/java/math/BigInteger.html
