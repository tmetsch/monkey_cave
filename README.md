# The Monkey Cave

Tools to simulate application behavior and misbehavior. Inspired by Netflix's Chaos Monkeys.

## The good monkeys

Simulate normal application behavior: 

* like a simple web service causing some I/O on incoming TCP requests.
* like a VM start up.

## The bad monkeys

Randomly spin up and cause I/O or other 'weird' behaviour patterns on the system.

Also there is a monkey for trying to grab all virtual CPU, disk IO and therefore create an unbalance for multiple VMs running on a host - a good system should use I/O capping/limiting here and hinder this behavior.

## The intruding monkeys

Simulate DoS attacks.

More monkeys to come soon...

The monkeys are used by us to test a system which learns form application behavour and adjusts the overall system according to the learned knowledge. These monkeys here are used to test drive the system.

(c) 2013 engjoy UG (haftungsbeschraenkt).
