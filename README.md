## Coding challenge IV: Save our app from DDos attacks
### Problematic
Haproxy provides a high, fast and efficient availability load balacing and proxying.
We would like to get benefits of its in-memory storage stick table technology to secure our platform by tracking our users activities including malicious ones. 
We would like to introduce haproxy in top level or our web architecture.

### Expected solution
Using ansible and docker-compose, pop up 3 containers distributed as following:

1. One Haproxy container that holds your haproxy config.
2. One nginx container  that holds your vhosts to redirect requests to the php container.
3. One php container that serves your sample.