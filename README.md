# loadbalancer
This ryu app loadbalances user traffic to different accel-ppp instances. It
creates sticky sessions after the decision has been taken.

## Run the the loadbalancer app with ryu
`ryu-manager ryu-app/simple_switch_13.py`
