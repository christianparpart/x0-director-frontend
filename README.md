# x0 Director Frontend

This is the soon to be web interface for the x0' director load balancer plugin.

# Requirements

- connects to external x0 directors by JSON API, possibly via Basic Auth or a PSK xor'd against current UTC timestamp.
- manage multiple directors, each having 1 to N clusters configured.
- manage clusters by adding/manipulating/removing backends.
- graph x0 overall load, cluster load and backend load in req/s and Mb/s
- access x0 system log
- write a service to collect data from directors and submit them into some database the web app can read frong.

# References

- webapp either in Rails (or Python's equivalent, so I actually put my hands on Python ^o^)
- Google Charts API
