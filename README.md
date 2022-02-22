# screen-shifter

# Installation

# Screen Shifter

### First Time Installation:
```sh
if [ ! -f "/usr/bin/screen-shifter" ]; then
    if [ ! -d "screen-shifter" ]; then 
        git clone 'https://github.com/electrodragon/screen-shifter.git'
        sudo mv screen-shifter/screen-shifter /usr/bin/screen-shifter
        sudo chmod +x /usr/bin/screen-shifter
        rm -rf screen-shifter
    else
        echo ":: A directory named 'screen-shifter' already exist in current working directory"
        echo ":: Try running the command in some other dir or remove existing screen-shifter dir"
    fi
else
    echo "screen-shifter Already Installed at /usr/bin/screen-shifter"
    echo ":: Please remove it and try again"
fi
```

### Update screen-shifter:
```sh
if [ ! -d "screen-shifter" ]; then 
    git clone 'https://github.com/electrodragon/screen-shifter.git'
    sudo mv screen-shifter/screen-shifter /usr/bin/screen-shifter
    sudo chmod +x /usr/bin/screen-shifter
    rm -rf screen-shifter
else
    echo ":: A directory named 'screen-shifter' already exist in current working directory"
    echo ":: Try running the command in some other dir or remove existing screen-shifter dir"
fi
```
