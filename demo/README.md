# Set up

[Pandoc](https://github.com/jgm/pandoc/releases/tag/2.0.5)


## Install Pandoc

```
yum install pandoc
```

```
wget pandoc
sudo ln -s /home/nathan/bin/pandoc /usr/local/bin/
```

## Install `rmarkdown` from Github

```
> devtools::install_github('rstudio/rmarkdown@feature/powerpoint')
```

## Install webshot

```
> install.packages("webshot")
> webshot::install_phantomjs()
```

