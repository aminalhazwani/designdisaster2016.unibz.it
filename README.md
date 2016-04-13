# designdisaster2016.unibz.it

Website for the conference on design and communication for eco-social transitions.

### Configuration

**Clone the repository**

```shell
$ git clone git@github.com:aminalhazwani/designdisaster2016.unibz.it.git
```

or [download the .zip](https://github.com/aminalhazwani/designdisaster2016.unibz.it/archive/master.zip). In this case remember to unzip the file before going to the next step.

**Go to the project folder with Terminal.app**

```shell
$ cd path/designdisaster2016.unibz.it
```

**Install Jekyll**

```shell
$ gem install jekyll
```

### Run Jekyll

```shell
$ jekyll serve --config _config.yml,_config_dev.yml
```

and open this url `http://127.0.0.1:4000/` in your browser.

### Build the website for production

In order to prepare the website for deployment simply run this command.

```shell
$ jekyll build
```

The resulting code will be placed in `_site` in the project folder.