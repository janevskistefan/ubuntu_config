# powertop

`sudo apt install powertop`

`sudo powertop --calibrate`

# auto-cpufreq
```bash
git clone https://github.com/AdnanHodzic/auto-cpufreq.git &&
cd auto-cpufreq && 
sudo ./auto-cpufreq-installer && 
sudo auto-cpufreq --install && 
sudo ln -s $(pwd)/auto-cpufreq.conf /etc/
```

# tlp

```bash
sudo add-apt-repository ppa:linrunner/tlp &&
sudo apt update &&
sudo apt install tlp &&
sudo ln -s $(pwd)/tlp.conf /etc/tlp.d/
```
# s2idle -> s2deep

https://devnull.land/laptop-s2idle-to-deep