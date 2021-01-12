# bash-shell

## ubuntu 18.04 && macOSX

copy file and paste to ./$HOME
```
.bash_profile
git-completion.bash
git-prompt.sh
```

add code in ~/.bashrc
```
source ~/.bash_profile
```

add shell Miniconda 
add cone in .bash_profile
```
# >>> conda initialize >>>
# !! Contents within this block are managed by 'conda init' !!
__conda_setup="$('/home/nt/miniconda3/bin/conda' 'shell.bash' 'hook' 2> /dev/null)"
if [ $? -eq 0 ]; then
    eval "$__conda_setup"
else
    if [ -f "/home/nt/miniconda3/etc/profile.d/conda.sh" ]; then
        . "/home/nt/miniconda3/etc/profile.d/conda.sh"
    else
        export PATH="/home/nt/miniconda3/bin:$PATH"
    fi
fi
unset __conda_setup
# <<< conda initialize <<<
```

run in ./$HOME
```
 $ source ~/.bashrc
```

<p align="center"><img width="500" src="/markdown/bash-shell.png" /> </p>

## Gnome-tweaks Dark Theme 
```
 $ sudo -s
 $ apt install -y gnome-tweaks
 $ apt-get install gnome-tweak-tool
 $ gnome-tweaks
```
<p align="center"><img width="500" src="/markdown/tweaks.png" /> </p>

wallpaper kali : [markdown/kali.png](./markdown/kali.png)