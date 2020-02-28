In the istio environment, the service access process:
client->gateway->service1

When the client accesses the head, it brings x-forward-for, but in the service1 program, only x-forward-for cannot be obtained, and other heads can be obtained.

It is felt that the x-forward-for of gateway is set to null by default or no delivery is made. I can't find an explanation after reading the data.

How to solve this problem??
