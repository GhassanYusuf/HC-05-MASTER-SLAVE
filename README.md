# HC-05 MASTER & SLAVE
This is a repository as a tutorial how to make hc-05 bluetooth connect with each other via making one of them a master and the other as a slave

## AT COMMANDS FOR SLAVE UNIT
```
AT
AT+ROLE=0
AT+CMODE=1
AT+NAME=Your Desired Name
AT+UART=Your Baud Rate
AT+ADDR?
```

## AT COMMANDS FOR MASTER UNIT
```
AT
AT+ROLE=1
AT+CMODE=0
AT+UART=Your Baud Rate
AT+BIND=MAC ADDRESS OF SLAVE BLUETOOTH DEVICE
```
