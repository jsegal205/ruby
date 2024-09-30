# Ruby Projects

A playground to tinker with Ruby on Rails

All subdirectories should run independent of each other. View the README.md in each folder for more information

## New project setup

### asdf

These projects are managed with asdf. Follow their installation guide: [https://asdf-vm.com/guide/getting-started.html](https://asdf-vm.com/guide/getting-started.html) first.

### install ruby version

Version set with local [.tool-versions](./.tool-versions) file. Projects are likely to have different Ruby versions. Check project README.md for more information.

```sh
asdf install
```

### install rails

```sh
gem install rails
```

### create new project

```sh
rails new app_name
```

## troubleshooting

Ensure that you have `.gem` directory for the current ruby version added to your path:

```sh
export PATH="/path/to/.gem/ruby/{{ruby-version}}/bin:$PATH"
```
