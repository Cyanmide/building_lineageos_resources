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

#### **Step 1: Identify the correct branch**
Take a look at the repository branch, as shown in the example image below:

![Branch Example](branch.jpeg)

In this example, the branch is `cm-14.1`. Replace `[BRANCH]` in the example file with the actual branch name for the repository you’re using. Keep in mind that the branch names may differ for the device, vendor, and kernel repositories.
#### **Step 2: Set up folder titles**

- Replace `[MANUFACTURER_in_lowercase]` with the name of the device manufacturer in lowercase.
  - **Examples:**
    - Samsung → `samsung`
    - LG → `lge`
    - OnePlus → `oneplus`
  - This will be used as the name of the manufacturer folder.

- Replace `[DEVICE_CODENAME_in_lowercase]` with your device's codename in lowercase.
  - This is typically the same name as the repository for your device.

- Replace `[GIT_USERNAME]` with the username or group of who created the repository.
- Replace `[GIT_REPO]` with the repository name.

**Example:**
For the repository `sixito007/android_vendor_samsung_goyave3g`:
- `GIT_USERNAME`: `sixito007`
- `GIT_RE

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
