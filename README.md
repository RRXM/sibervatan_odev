"#sibervatan_odev" 

<h2>ilk</h2>
<p>
bcdedit /set {bootmgr} displaybootmenu yes
bcdedit /set {default} safeboot minimal
bcdedit /timeout 10
</p>

<h2>ikinci</h2>
<p>
bcdedit /deletevalue {default} safeboot
bcdedit /set {bootmgr} displaybootmenu no
</p>

