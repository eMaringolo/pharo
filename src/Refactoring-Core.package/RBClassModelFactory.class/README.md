None of the classes inside this package should be directly accessed. They should be accessed via myself. I'm a class factory. 

I'm an important design point: I will let future evolution of the system to be experimented without the needs to change all the users. Then once the experiments and a good solution is found it may be the time to remove me and to think that I'm an overengineered solution. Right now I'm a change enabler. For example people can try to use Ring models to model RBmodel. 