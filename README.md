Flatpak builder: GNOME Runtime and SDK
======================================

!["Prompt"](https://raw.githubusercontent.com/gbraad/assets/gh-pages/icons/prompt-icon-64.png)


Build container for flatpak with pre-installed GNOME 3.20 Runtime and SDK.


Usage
-----

```
$ alias flatpak-builder-gnome='docker run -it --rm -v $PWD:/workspace registry.gitlab.com/gbraad/flatpak-builder-gnome bash'
$ flatpak-builder-gnome
[root@655f34f18fb5 workspace]# 
```


Authors
-------

| [!["Gerard Braad"](http://gravatar.com/avatar/e466994eea3c2a1672564e45aca844d0.png?s=60)](http://gbraad.nl "Gerard Braad <me@gbraad.nl>") |
|---|
| [@gbraad](https://twitter.com/gbraad)  |
