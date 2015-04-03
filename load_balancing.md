Let's continue our cooking analogy by considering the line at a grocery store

When traffic is low, one cashier works fine
When traffic grows, one cashier gets backed up

One solution is to add more cashiers:
- Now how do you decide which customers go to which cashier
- DNS round-robin
  - inconsistent queue length
- Load balancer
  - round robin
  - weighted
- Session persistence
