# asset-faucet

# Faucet types:
# 1 -Vote
Gives users x token if params are met
Voting metrics should exist in the .js
# 2 -Marketing
Filter for tap limits.  Filter can be any combination; rvn @ addy,age of addy, IP, etc
# 3 -Paywall
Possible features of all the above + paywall.  Possibly use: https://microraiden.readthedocs.io/en/latest/tutorials/paywall-tutorial.html





# Notes:
# Security
"well you could look at nginx ruleset modules couldnt you or cloudflare limit rates to take care of that, or recaptcha. or user identity validation controls and increment counters
there is a variety of ways you can roll the pudding chap
the philosophical argument is whether you resolve the problem directly at the application layer via identity and increment counters or on it's perimeter, at load balancer, like AWS LB, cloudflare rules, nginx rules"  -Push
# Features
Make a couple different js templates for better user experience 
