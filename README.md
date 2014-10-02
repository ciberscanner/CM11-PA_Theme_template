##This is the theme template from tutorial !
link:(http://goo.gl/kWq9ea) !!

###Look at the official template:
link : https://github.com/CyanogenMod/android_packages_themes_Template

###Some Screen : 
<img style="max-width:px ;" src="https://raw.githubusercontent.com/AndyMon/CM11-PA_Theme_template/master/screen/lesson_3_wallpaper_pre.png">
<img style="max-width:px ;" src="https://raw.githubusercontent.com/AndyMon/CM11-PA_Theme_template/master/screen/lesson_3_wall.png">
<img style="max-width:px ;" src="https://raw.githubusercontent.com/AndyMon/CM11-PA_Theme_template/master/screen/lesson_3_lock.png">
<img style="max-width:px ;" src="https://raw.githubusercontent.com/AndyMon/CM11-PA_Theme_template/master/screen/lesson_2_icon_settings_edited.png">
<img style="max-width:px ;" src="https://raw.githubusercontent.com/AndyMon/CM11-PA_Theme_template/master/screen/lesson_4_botton.png">
<img style="max-width:px ;" src="https://raw.githubusercontent.com/AndyMon/CM11-PA_Theme_template/master/screen/lesson_4_radio_holo_blue_dark.png">
<img style="max-width:px ;" src="https://raw.githubusercontent.com/AndyMon/CM11-PA_Theme_template/master/screen/lesson_4_switch.png">
<a>NOTE: actually the style in the screen are from other theme, becasue at this moment we haven't make a tutorial how to edit it</a>
### Some documentations...
The directory structure looks like this:<br><pre>
AndroidManifest.xml<br>
src/<br>
res/<br>
assets/<br>
  boot-animation/<br>
  fonts/<br>
  icons/<br>
    res/ (note: same dir structure as res/ in trebuchet icon packs)<br>
  wallpapers/<br>
  ringtones/<br>
  notifications/<br>
  alarms/<br>
  overlays/<br>
      [target-pkg-name1]<br>
          res/<br>
           drawable/<br>
           drawable-hdpi/<br>
           ...<br>
           layouts/<br>
           xml/<br>
      [target-pkg-name2]<br>
          res/</pre><br>
      
A theme APK is identified by meta-value data in AndroidManifest.xml. Here is an example:<br>
<pre><div class="line" id="LC1"><span class="nt">&lt;manifest</span> <span class="na">xmlns:android=</span><span class="s">"http://schemas.android.com/apk/res/android"</span></div><div class="line" id="LC2">&nbsp;&nbsp;&nbsp;&nbsp;<span class="na">package=</span><span class="s">"com.botty.testcm11"</span><span class="nt">&gt;</span></div><div class="line" id="LC3"><br></div><div class="line" id="LC4">&nbsp;&nbsp;&nbsp;&nbsp;<span class="nt">&lt;uses-feature</span> <span class="na">android:name=</span><span class="s">"org.cyanogenmod.theme"</span> <span class="nt">/&gt;</span></div><div class="line" id="LC5">&nbsp;&nbsp;&nbsp;&nbsp;<span class="nt">&lt;meta-data</span> <span class="na">android:name=</span><span class="s">"org.cyanogenmod.theme.name"</span> <span class="na">android:value=</span><span class="s">"My Test Theme"</span><span class="nt">/&gt;</span></div><div class="line" id="LC6">&nbsp;&nbsp;&nbsp;&nbsp;<span class="nt">&lt;meta-data</span> <span class="na">android:name=</span><span class="s">"org.cyanogenmod.theme.author"</span> <span class="na">android:value=</span><span class="s">"Botty Ivan"</span> <span class="nt">/&gt;</span></div><div class="line" id="LC7"><br></div><div class="line" id="LC8">&nbsp;&nbsp;&nbsp;&nbsp;<span class="nt">&lt;application</span> <span class="na">android:allowBackup=</span><span class="s">"true"</span></div><div class="line" id="LC9">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="na">android:label=</span><span class="s">"@string/app_name"</span></div><div class="line" id="LC10">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="na">android:icon=</span><span class="s">"@drawable/ic_launcher"</span></div><div class="line" id="LC11">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="na">android:theme=</span><span class="s">"@style/AppTheme"</span><span class="nt">&gt;</span></div><div class="line" id="LC12"><br></div><div class="line" id="LC13">&nbsp;&nbsp;&nbsp;&nbsp;<span class="nt">&lt;/application&gt;</span></div><div class="line" id="LC14"><br></div><div class="line" id="LC15"><span class="nt">&lt;/manifest&gt;</span></div></pre>
Click <a href="http://review.cyanogenmod.org/#/c/62375/">here</a> to see the full documentation.

### Good theming guys !!

Check out my theme called *Blu Sky* : https://play.google.com/store/apps/details?id=com.botty.theme.next.skyblue

Check out my theme called *NEXT BLUE* : https://play.google.com/store/apps/details?id=com.botty.theme.next.blue

Check out my theme called *Holo Gray Next* : https://play.google.com/store/apps/details?id=com.botty.theme.next

Follow me on : <br>
<b>Google +</b> : <a href="google.com/+IvanBotty">google.com/+IvanBotty</a><br>
<b>Twitter</b> : <a href="twitter.com/bottyivan">twitter.com/bottyivan</a>
