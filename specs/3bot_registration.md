# 3bot registration ideas

## principle

- ThreeFold Foundation runs the registration service for 3bot's & internal DNS names
- ThreeFold Foundation runs a bootstrap mechanism, which bootstraps a 3bot service and allows user to access
- ThreeFold Foundation has no access to where the 3bots run, its just a bootstrap, no access ever to such a process !
- all proceeds get in a wallet of the TFF with multi sig of 3 TF Foundation Founders

## suggested fees

- registration of a new 3bot = 100 TFT
- monthly fee per 3bot = 10 TFT
- deletion of name = free
- alias name to a 3bot = 50 TFT
- ip address info change = 20 TFT
- public key change = 20 TFT
- deletion = free

other remarks

- 30% discount if year payment
- 50% discount if 2 year payment
- min = 1 month, 30 days
- month = 30 days, year = 365 days

## definitions

- 3bot = a virtual service = digital avatar for a person or group of persons running in a ThreeFold Container

##

- Possibility to register 3bot
   - unique id (int, incremental, given by blockchain)
   - list of names: 5char.5char (like dns, min 5 char per part)
   - list of ip addresses: ipv6/4
   - nrmonths
   - public key
   - signature of info in this record
- Update information
   - following info can be changed
     - ipaddress info
     - name changes
   - info can only be changed (updated) by user who has the private key of the already registered info
- Ability to query  this information 
  - through  the explorers  and light clients 

