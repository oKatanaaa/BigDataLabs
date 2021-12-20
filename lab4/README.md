## Setup
The lab was done in Python using Kazoo library. 

ZooKeeper is being launched in a docker using the following command:
`docker-compose up --build`

Once the docker has launched, execute the following command:
`./bin/zkCli.sh -server localhost:2181`


## Exercises
Every part of the lab is contained in a separate file:
- `StartingWithZooKeeper.ipynb` - taking a look at the API.
- `AnimalExample.ipynb` - implementing the example with animals.
- `Philosophers` - contains solution to the Dining Philosophers problem.
- `TwoPhaseCommit` - contains an implementation of the two phase commit protocol.
