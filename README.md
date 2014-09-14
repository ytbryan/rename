#Rename

A simple ruby script to sync your iOS resources/directories with project name.

`**NOTE: It's probably a good idea to backup your project first.**`

#### How to run the script?

1. drop the rename script at the same level as your .xcodeproj file.
2. run the following:
``` ruby
update install
./rename
```

#### What it does?

- It detects the name of _.xcodeproj and compare with its resources name.
- It then changes the name of directories and its resources by searching and replacing the old names.

#### CONTACT
[@ytbryan](http://twitter.com/ytbryan)

#### LICENSE
[MIT](http://opensource.org/licenses/MIT)
