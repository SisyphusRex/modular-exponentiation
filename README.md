# modular-exponentiation
Implementation of Modular Exponentiation Algorithm.

## What Is
In computing arithmetic expressions mod m, taking intermediate results mod m before the final result is obtained  
is sometimes convenient.  Large numbers can cause an overflow.

Theorem:  
Let 𝑚 be an integer larger than 1.  Let 𝑥 and 𝑦 be any integers.  Then:  
[(𝑥 mod 𝑚) + (𝑦 mod 𝑚)] mod 𝑚 = [𝑥 + 𝑦] mod 𝑚  
[(𝑥 mod 𝑚)(𝑦 mod 𝑚)] mod 𝑚 = [𝑥 * 𝑦] mod 𝑚  
