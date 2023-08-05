# Little's law

[Little's law](https://en.wikipedia.org/wiki/Little%27s_law) is a theorem in mathematical queueing theory. It describes the relationship between:

1. **L**: The average number of entities in the system.
2. **λ**: The average arrival rate of entities in the system.
3. **W**: The average time an entity spends in the system.

```
L = λW
```

It applies to queues in day-to-day life (e.g. at the supermarket, at traffic lights etc). It can also be applied usefully to queues in software systems. For instance, if you need to reduce latency in a system that receives messages on a queue then you know you need to reduce the amount of traffic you put on it and/or reduce the processing time for those messages.

When it comes to software engineering it is particularly useful when applied to the SDLC. If you want to decrease your delivery lead time then you need to decrease the amount of work the team picks up and/or decrease the amount of time it takes to complete that work. Alternatively, if you try to start more work than the team has capacity for then your lead times and work in progress will increase. This last case is a very common failure mode and I have often seen managers try to jam more and more work into the software engineering team and marvel at how it takes longer and longer to complete anything.

More people should be aware of Little's Law. It is a very useful little law.
