Searches Google's material-design-icons for a certain icon, finds a match, and copies the selected resource into the corresponding folders in your /res/ folder: 

drawable-mdpi, drawable-hdpi, drawable-xhdpi, drawable-xxhpdi, drawable-xxxhdpi

**Preparation:**

1. Clone copyicon.py in the same directory as your application folder.

2. Change resFolder variable to your app's /res/ folder path

**Example usage:**

Want the 24dp delete icon from material-design-icons in my app's drawable folders saved as "remove.png"

`python3 copyicon.py delete 24 remove`

This command will let you select which delete icon at 24dp, as there are several options like a white, grey, or black version and copy the one you want into the corresponding drawable folders, i.e. drawable-mdpi, etc.

Before, I had to find and copy them one by one into the proper drawable-dpi folders in /res/ since they were in separate drawable-dpi folders.
