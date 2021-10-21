# OMV Blue Dark Theme
Alternative Theme for OpenMediaVault (OMV NAS) Admin GUI

## Usage / Installation
Connect to the server via SSH and create a <code>theme-custom.css</code>:
<br>
<pre>
<code>nano /var/www/openmediavault/css/themes-custom.css</code>
</pre>
<br>
Paste code content of <code>theme-custom.css</code>. Set permissions of the file to:
<br>
<br>
<pre>
<code>openmediavault-webgui</code>
</pre>
<br>
<br> Edit file ** defaults.scss **. Adjust the omv default values at the end of the file:
<pre>
<code>
$omv-color-more-lighter: #b2c2cd;
$omv-color-lighter: #6897b6;
$omv-color-default: #1b5d88;
$omv-color-darker: #0b1625;
$omv-color-more-darker: #0b1625;
</code>
</pre>
<br>
<br>
## The created Custom CSS currently works with OMV v5. No guarantee can be given for older versions. Just try it out.
<br><br>
Have Fun ;-)
