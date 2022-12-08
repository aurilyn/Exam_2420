## EXAM_2420

# Question 1
```
sudo apt update
sudo apt upgrade
```

# Question 5
```
    [Unit]
    Description=My Script Service
    [Service]
    Type=simple
    ExecStart=/home/vagrant/bin/part5
    [Install]
    WantedBy=multi-user.target
```

# Question 6
```
  [Unit]
  Description=My Timer
  
  [Timer]
  OnBootSec=1min
  OnUnitActiveSec=1d
  
  [Install]
  WantedBy=timers.target
                       
```