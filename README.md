"#sibervatan_odev" 

<h2>ilk</h2>
<p>bcdedit /set {bootmgr} displaybootmenu yes</p>
<p>bcdedit /set {default} safeboot minimal</p>
<p>bcdedit /timeout 10</p>
</p>

<h2>ikinci</h2>
<p>bcdedit /deletevalue {default} safeboot</p>
<p>bcdedit /set {bootmgr} displaybootmenu no </p>

