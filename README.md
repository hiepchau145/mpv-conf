# mpv-conf for mypc
R5-2600 | B450 Tomahawk | 1050Ti | Windows 11


1. Open Windows PowerShell 
<code>Set-ExecutionPolicy RemoteSigned -Scope CurrentUser # Optional: Needed to run a remote script the first time</code>
<code>irm get.scoop.sh | iex</code>

2. Install git and add extras 
<code>scoop install git</code>
<code>scoop bucket add extras</code>

3. Install mpv
<code> scoop install mpv-git yt-dlp</code>

4. Download and extract to <code>C:\Users\hc\scoop\apps\mpv-git\current\portable_config</code>
