<div align="center">
  <a href="#">
  	<img src="https://i.imgur.com/i5BD9DX.png" alt="Lineage logo" height="250" />
  </a>
  <br>
  <p>
    <b>Welcome!</b>
  </p>
  <p>
     <i>This is a repository that will hopefully aid people who want to build LineageOS for their unsupported device.</i>
  </p>
  <p>


I actually have a 'Building LineageOS for Unsupported Device' guide over on XDA Forums. Check it out <a href="https://xdaforums.com/t/how-to-actually-build-lineageos-for-an-unsupported-device-for-real-this-time.4686073/">here!
<div align="left">
<br>

## Finding your repository links
--WIP--
  
## Creating your manifest file
Download the [example.xml](https://github.com/kingkwahli/building_lineageos_resources/blob/main/example.xml) and open it in a text editor.  
  

#### **What it all means:**​

What it all means:​

BRANCH
[Take a peek at this:
branch.jpeg
See how it says cm-14.1?
Whatever it says there for the repository(s) you've found replaces BRANCH. Remember that each different repository for the device, vendor, and kernel will not always have the same branch name.

MANUFACTURER_in_lowercase
and
DEVICE_CODENAME_in_lowercase
Let's start with the MANUFACTURER_in_lowercase:
This one is simply the device manufacturer. Samsung devices are samsung, LG Electronics are lge, and so on. Whatever the manufacturer is, goes here, but in all lowercase. This can be adjusted, this will just be the name of the manufacturer folder.

Now, the DEVICE_CODENAME_in_lowercase:
Self-explanatory. Your device's codename, again in lowercase. You should already know this, as this is the key to finding the correct repo links.

GIT_USERNAME/GIT_REPO

Easy. GIT_USERNAME would be the username of the person/group who created the repository. For example, in sixito007/android_vendor_samsung_goyave3g, sixito007 would be the GIT_USERNAME.
GIT_REPO follows similar directions. In that same example, android_vendor_samsung_goyave3g would be the GIT_REPO

After that’s all done, save the file to ~/android/lineage/.repo/local_manifests/devicecodename.xml (create local_manifests folder if it doesn’t exist)
<br>  
Obviously devicecodename would be your device’s codename, in my case goyave3g.xml
##  The best system to build on
<b>OS:</b> The best system to use would be Ubuntu, or anything Ubuntu-based. Pretty  anything on <tr><td align="center"><a href="https://monovm.com/blog/ubuntu-based-distros/">this page</a> is usable. I recommend  <tr><td align="center"><a href="https://linuxmint.com/">Linux Mint Cinnamon</a>, if you are only using it for building, but if you want a good, daily driver, full Linux install, I recommend <tr><td align="center"><a href="https://zorin.com/os/">Zorin OS</a>.
</tr> 
<b>Specs:</b> At least 16GB of RAM is a must. 20GB and you're smooth sailing. For GPU, it doesn't really matter, as long as it works. CPU, a Zen 2 CPU or i3 or later is perfectly good.

## Other helpful links
  <tr>
    <td align="center"><a href="https://xdaforums.com/"><b>XDA Developer Forums</b> 
 </a>
  </tr>
<br>
This is a great place to look for more information about previous builds for your device, and if you're stuck on something, XDA is full of helpful people.
<br>
<br>
  <tr>
    <td align="center"><a href="https://www.reddit.com/r/LineageOS/"><b>Reddit</b> 
    </a>
</tr>
<br>
Reddit, especially the LineageOS subreddit, is another great place to attempt to resolve errors.
<br>
<br>
  <tr>
    <td align="center"><a href="https://www.gsmarena.com/"><b>GSMArena</b> 
</a>
</tr>
<br>
This is where you should look up your device to find out it's hardware and it's last supported Android version.
<br> <br>
<tr>
    <td align="center"><a href="https://https://wiki.lineageos.org/devices"><b>LineageOS</b> 
 </a>
  </tr>
<br>
After looking through your specs on GSMArena, see if you can find a build guide for a device with similar hardware to yours.


## Credits/Thanks
Huge thank-you to @popiee, @amarithetopg, and @parrots_ on XDA Forums!!!
Credits for part of the example.xml go to daltonfury42 on GitHub.
