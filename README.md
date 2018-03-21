# asdf-java

![travis ci](https://travis-ci.org/Danny02/asdf-java.svg?branch=master)

[OpenJDK](http://jdk.java.net/) plugin for the [asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

After installing [asdf](https://github.com/asdf-vm/asdf),
you can add this plugin like this:

```bash
asdf plugin-add java https://github.com/Danny02/asdf-java
```

and install new versions like this:

```bash
asdf install java 10
```

and switch versions like this:

```bash
asdf global java 10
```

If you need Gradle or Maven, you can use asdf plugins for those, too.

```bash
asdf plugin-add maven https://github.com/skotchpine/asdf-maven
asdf plugin-add gradle https://github.com/rfrancis/asdf-gradle
```

## Obey

By using this software you agree to:

- [GNU General Public License, version 2, with the Classpath Exception](http://openjdk.java.net/legal/gplv2+ce.html)

## Reading

Read the [asdf readme](https://github.com/asdf-vm/asdf)
for instructions on how to install and manage versions of any language.

If you have trouble with any expected features,
have any feature requests or want to contribute,
please [do an issue](https://github.com/Danny02/asdf-java/issues).

## Homage

This is a fork of [skotchpine/asdf-java](https://github.com/skotchpine/asdf-java) which provides access to Oracle builds of the JDK.

This plugin wouldn't be possible without the current Java version managers.
Here's a list of repos with similar affects that were heavily referenced here:

- [jabba](https://github.com/hsyiko/jabba)
- [sdkman](https://github.com/sdkman/sdkman-cli)
- [Arch's JDK](https://aur.archlinux.org/packages/jdk/)

## Development

- asdf's [creating-plugins.md](https://github.com/asdf-vm/asdf/blob/master/docs/creating-plugins.md)
- [Bash Hackers Wiki](http://wiki.bash-hackers.org/)
