### It's like playing whack-a-mole with Youtube ads.

Quick and dirty install method.

ssh into your pi and...
```
sudo cp /etc/pihole/adlists.default /etc/pihole/adlists.list && sudo echo "https://raw.githubusercontent.com/impshum/impshum.github.io/master/adblocklist.txt" | sudo tee -a /etc/pihole/adlists.list && pihole -g
```
