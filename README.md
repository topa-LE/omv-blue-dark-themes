# OMV Blue Dark Theme
Alternative Theme for OpenMediaVault (OMV NAS) Admin GUI

## Usage / Installation
Connect to the server via SSH and create a new <code>theme-custom.css</code>:
<br>
<pre>
<code>nano /var/www/openmediavault/css/theme-custom.css</code>
</pre>
or
<pre>
<code>cd /var/www/openmediavault/css</code>
<code>nano theme-custom.css</code>
</pre>
<br>
Paste code content of <code>theme-custom.css</code>. Set permissions of the file to:
<br>
<br>
<pre>
<code>openmediavault-webgui</code>
</pre>

#### Set owner
<pre>
<code>chown openmediavault-webgui:openmediavault-webgui theme-custom.css</code>
</pre>

## Lazy one-liner Usage / Installation
ssh into omv with whatever application you like and paste the code into the terminal, let it do it's thing and you should have a fully functional darkthemed omv control pannel. I'll be it can have some refinements to be made but over pritty good, not complaining. Judging by the laziness you have to use a oneliner command instead of doing step by step, I dought you care about the little rough edges
<pre>
<code>cd /var/www/openmediavault/css/ && sudo wget https://raw.githubusercontent.com/topa-LE/omv_blue_dark_themes/main/theme-custom.css && sudo chown openmediavault-webgui:openmediavault-webgui theme-custom.css</code>
</pre>

#### Optional
Edit file **defaults.scss**. Adjust the <code>omv</code> default values at the end of the file:
<pre>
<code>
$omv-color-more-lighter: #b2c2cd;
$omv-color-lighter: #6897b6;
$omv-color-default: #1b5d88;
$omv-color-darker: #0b1625;
$omv-color-more-darker: #0b1625;
</code>
</pre>

##### The created Custom CSS currently works with OMV v5.
No guarantee can be given for older versions. Just try it out.
<br>
<br>
Have Fun ;-)
<br>
<br>
![Dark Theme OMV](https://raw.githubusercontent.com/topa-LE/omv_blue_dark_themes/main/Screenshots/img_omv_dark_blue_theme.jpg)
