# Laravel Homestead PHP5 / PHP56
* Forked from https://github.com/laravel/homestead

### Back to Homstead With PHP 5.6

This is meant to run along side of your normal Homestead box (which may be on php7 now), so `bash init.sh` creates a new homestead directory at ~/.homestead-56/ So setup this box's Homestead file at ~/.homestead-56/Homestead.yaml

For more information on how to setup homestead official documentation [is located here](https://laravel.com/docs/5.2/homestead).

# Copy Sites From Original Homestead

```git clone https://github.com/dev-kang/homestead56.git ~/Homestead56```

```cd ~/Homestead56; cp -rv ~/.homestead/ ~/.homestead-56/; vagrant up```

## Or Setup Brand New Homestead56

 ```git clone https://github.com/dev-kang/homestead56.git ~/Homestead56```

```cd ~/Homestead56; bash init.sh; vagrant up```

## Other:
* Installing mongo? Run ```bash ~/Homestead56/other/install-mongo.sh```
* Something messed up? Completely reinstall by running ```bash ~/Homestead56/other/remove-box.sh``` then redo the install instructions from above.

### TODO:
* Change & test HHVM
* Change & test symfony2
* Change & test init.bat (Windows)
