# wheel-spy
Hypothesis:
On the long term SPY index always go up so selling naked puts on SPY will always and up with new high and turning wheel cycle into cash

Strategy:
1) open short naked weekly ATM put and wait for expiration.
IF not assigned (expired worthless): go to 1), ELSE: go to 2)
2) open short covered weekly OTM call (the same strike as was in put) and wait for expiration.
IF not assigned (expired worthless): go to 2), ELSE: go to 1)

Questions:
1) what investing outcome is possible?
2) what is historical greatest dropdown?
3) what is minimum and maximum trade time before chash out?
4) what is a frequncy of wheel cycles?
5) what is annual performance with given strategy?
6) how profit withdrawal affects portfolio value?

Specifics - biggest option premium is in ATM (at the money) options, the deeper it is OTM (out of the money, distance between actual asset price and option strike - bet price) the less premium it has, so if SPY does not renew its high for long time, we earn nothing.

#wheel_strategy
