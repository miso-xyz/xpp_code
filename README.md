# X++ Code Samples
Random code sample you might want to play around with (all code samples present here are by me)

will upload here from time to time

# Requirements
- Vyper IDE 8.0 (Minimum) (use `vyper --v` to get your current version, to update do `vyper --up "ide, rt" %version%`
- Chara (dm me to request a client)
- Chara.XPPRuntimeHandler

Note: if you don't want to install chara you can try to convert the code to something like C#, idk if i wanna make a code translator for x++ though

# Building
`> vyper --build %file%`

# Getting X++ Runtime Handler
if you don't have it for some reason you can just use the following commands
<pre>
;; you'll need to allow UAC & DRM, you can also use the GUI to download the package directly from the page

> chara(instance) uac allow 
> chara(instance) drm allow pkg-install
> chara get-pkg "xppRH"
> chara install-pkg "xppRH"
</pre>
