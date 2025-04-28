1. line 9 prints "values added: 20" 
2. line 13 prints "undefined"
3. var is function scoped so even if i declared a variable inside an if block or for loop, it would be able to be accessed outside said block. This can lead to name conflicts and strange errors
4. line 9 prints "values added: 20"
5. line 13 returns an error since result is undefined. let is block scoped and it was declared inside an if block so it cant be used outside of it.
6. line 9 will print 0 if allowed to run but line 7 will trigger an error since line 7 is trying to change the value of a const past the initial declaration
7. line 13 will run into an error of result being undefined since it was declared inside the for loop. either way, line 7 will trigger an error of trying to change a const value. 