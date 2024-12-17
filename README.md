
# How to create a Manga-cli in linux 

- you need to type this command to clone the repository and open to that direction:

```php
git clone https://github.com/stl3/manga-cli && cd manga-cli
```

- then once it success you need to install python to have a convert to img to pdf once it run for linux

```php
sudo apt update
sudo apt install python3

```

- then once it success install the python you now install the pip for installing the library in python

```php
sudo apt install python3-pip
```

- then it success you need to install now the venv for virtual machine :

```php

sudo apt install python3-venv

```

- then type this command for creating a virtual
```php
python3 -m venv venv

```

- to activate just type this command
```php
source venv/bin/activate

```

-and install it using this command and deactivate
```php
pip install img2pdf
deactivate
```

## to ensure it perfectly run just type this command

```php
sudo apt update
sudo apt install zathura
sudo apt update
sudo apt install img2pdf


```


- then once it sucess to install you now type this command to open it in cli
```php
./manga-cli
```

enjoy!!~~


