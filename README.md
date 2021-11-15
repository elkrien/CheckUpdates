# CheckUpdates
Script for checking updates in Arch Linux and notify by dunst - created during learning Python

### Dependancies:
```
pip3 install prettytable
```

### How to build:
```
pip3 install pyinstaller
pyinstaller check_updates.py --onefile
```

### Run:
Without build:
```
python3 check_updates.py
```
When built:
```
cd dist/
./check_updates
```
