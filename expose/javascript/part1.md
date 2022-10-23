1. "values added: 20". var is function scope, so result can be access anywhere inside the sumValues funtion.
2. "final result: 20". same reason as no.1.
3. "values added: 20" let is block scope, result in line 9 is inside the block result is defined so it would return a number.
4. Returns an error, because result was defined in the if block, and line 13 is outside that block, therefore, reuslt is not defined here.
5. Returns an error, because const can not be reassigned, so line 7 creates the error.
6. Returns an error, same reason as no.5
