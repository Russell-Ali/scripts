<h1>dependency free <font color="#005577" >dwmblocks</font>
scripts
</h1>

**anything starts with "blk-" can be used as block**
<br>
*You can delete everything else. They aren't meant to be used with dwmblocks*
<br>
<br>
*Note that some of the scripts need correction since they directly access your system files with absolute path.*
<br>
***Ex:***
<br>
```
/sys/class/power_supply/BAT1/capacity
```
could look like this on your device:

```
/sys/class/power_supply/BAT0/capacity
```
<h3>How to install it though</h3>

1. Clone the repo:

```
git clone https://github.com/Russell-Ali/scripts
```

2. Add scripts to your path:

```
export PATH="$HOME/scripts:$PATH"
```
3. Source the terminal or simply open new one and test the scripts
```
source ~/.zshrc
```
or
```
source ~/.bashrc
```

4. Finally add them to your blocks.def.h
