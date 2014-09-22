#Rename

A simple ruby script to sync your iOS resources/directories with project name.

![rename](gif/test.gif)

`**NOTE: It's probably a good idea to backup your project first.**`

#### How to rename your ios xcode project

1. Tap lightly on the project name (ie. example) to change the name. (see gif above.)

2. A dialog box will appear. Click "Rename" will only rename the .xcodeproj and related resources.
![Image](images/3.png?raw=true)

3. But we will end up with this.
![Image](images/4.png?raw=true)

4. Run ./rename and follow the instructions.


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


#### You should place the script under the same level as your .xcodeproj file. See below:
![Image](images/1.png?raw=true)

#### remember to update the scheme
Go to manage scheme to change the name of your scheme

Change "example" to "newname"
![Image](images/5.png?raw=true)




#### CONTACT
[@ytbryan](http://twitter.com/ytbryan)

#### LICENSE
[MIT](http://opensource.org/licenses/MIT)
