### Normal mode

Most of the time all processes are up and running, none of them runs some mallicious Byzantine code, network conditions are good, meaning that all messages are delivered in time, and all processes are perfectly synchronized, i.e. they all have the same transaction log. We will call these conditions normal mode. In normal mode there's always some flow of entries to be added, originating from clients. It is needed to distinguish normal mode from idle mode when nothing happens. 

![Normal mode messages](doc/d1.png)

### Faulty follower

![Faulty follower messages](doc/d2.png)

### Faulty leader

![Faulty leader messages](doc/d3.png)

### Catch-up

![Catch-up messages](doc/d4.png)


### Idle mode

![Idle mode messages](doc/d5.png)