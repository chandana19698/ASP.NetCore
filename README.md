Middleware are chained one after the other and they are executed in order in which they are defined. 
In order to call the next middleware in request pipeline, we need to explicitly call it by using next() method.
If a middleware doesn't call the next middleware, then it is called a terminal middleware/ used to short circuit.
