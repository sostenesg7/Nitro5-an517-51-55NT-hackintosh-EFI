<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
</head>

<body>

<div>

<h2>Nitro 5 an517-51-55NT Hackintosh</h2>
<h3>- Opencore 0.7.4</h3>
<h3>- Big Sur 11.6 <a href="https://drive.google.com/file/d/1ZcCYR50zWWtis6dxxKn3AInfBgs7ia6E/view">I used this ISO</a></h3>

<br>
<h4>This UEFI is initial made from: <a href="https://github.com/SaeedHaidar/Nitro-5-an517-51-Hackintosh">
SaeedHaidar
</a>
, and updated to latest openCore by me. Thanks SaeedHaidar, u are my hero!!
</h4>
<br>

</div>

<details>  
<summary><strong>Images</strong></summary>
<br>
<img width="70%" src="images/1.png" alt="main">
<br>
<br>
<img width="70%" src="images/2.png" alt="bluetooth">
<br>
<br>
<img width="70%" src="images/3.png" alt="sound">
<br>
<br>
<img width="70%" src="images/4.png" alt="battery">
<br>
<br>
<img width="70%" src="images/5.png" alt="wifi">

<br>

</details>

<details>  
<summary><strong>What's working </strong></summary>
<br>
<table border="1px">

<tr>
<td>
<p> WiFi + Bluetooth + Airdrop + Universal Clipboard + Handoff + Continuity Camera + iPhone Cellular Calls (DW1820a) </p>
</td>

</tr>

<tr>
<td>
<p>Power Managment is very stable most of the time cpu Fan will not load but it depends on what you are doing </p>
</td>
</tr>

<tr>
<td>
<p>TouchPad + all gestures Finally after month of researching </p>
</td>
</tr>

<tr>
<td>
<p> Fully Functional QE/CI Enabled Graphics </p>
</td>
</tr>

<tr>
<td>
<p> intel bluetooth and WiFi on AX200 card </p>
</td>
</tr>

<tr>
<td>
<p> Display brightness with hot keys </p>
</td>
</tr>

<tr>
<td>
<p> FaceTime, Messages, etc... </p>
</td>
</tr>

<tr>
<td>
<p> iGPU with disabled dGPU </p>
</td>
</tr>

<tr>
<td>
<p>Audio & headphone jack </p>
</td>
</tr>

<tr>
<td>
<p>Battery Management  </p>
</td>
</tr>

<tr>
<td>
<p> All USB ports</p>
</td>
</tr>

<tr>
<td>
<p>WebCam  </p>
</td>
</tr>

<tr>
<td>
<p> Ethernet </p>
</td>
</tr>

<tr>
<td>
<p>Sidecar</p>
</td>
</tr>

<tr>
<td>
<p> <a style="text-decoration:none" href="https://dortania.github.io/OpenCore-Post-Install/universal/sleep.html">Sleep (Preparations section)</a></p>
</td>
</tr>

</table>
</details>

<details>

<summary><strong>Disabled Devices </strong></summary>
<br>

<p>GTX 1650 </p>

</details>

<details>

<summary><strong>Bios Settings </strong></summary>
<br>

<table border="1px">
<tr>
<td>
<p>Main → click on (calt+s) a new setting will appear to change SATA type to AHCI otherwise you will not be able to see you drive when installing hackintosh </p>
</td>
</tr>

<tr>
<td>
<p>Security → Set supervisor password (to disable secure boot)</p>
</td>
</tr>

<tr>
<td>
<p>Security → Password on boot → Disable</p>
</td>
</tr>

<tr>
<td>
<p>Boot → Secure Boot → Disable</p>
</td>
</tr>

</table>

</details>

<details>

<summary><strong>Not Working </strong></summary>
<br>

<p>HDMI (Nvidia Optimus is hardwire to HDMI)</p>

</details>

<details>
<summary><strong>Info</strong></summary>
<br>

<table border="1px">
<tr>
<td>
<p>When you switch SATA type to AHCI you might not be able to boot to windows again but do not worry here is a guide i found to switch without getting any issue <a href="https://support.thinkcritical.com/kb/articles/switch-windows-10-from-raid-ide-to-ahci">Here</a></p>
</td>
</tr>

<tr>
<td>
<p>You need to disable SystemProfilerMemoryFixup.kext if you wanna enter recovery mode or you will get kernel panic</p>
</td>
</tr>

<tr>
<td>
<p>To get right click to work go to touchpad settings in (Secondary click) choose (click in bottom right corner)</p>
</td>
</tr>

<tr>
<td>
<p>If apple Continuity did not worked try logout and login again on all your devices your hackintosh too</p>
</td>
</tr>

<tr>
<td>
<p>OpenCore Guide <a href="https://dortania.github.io/OpenCore-Install-Guide/">Here</a></p>
</td>
</tr>

</table>

</details>

<details>

<summary><strong>Updates</strong></summary>

</details>

</body>

</html>
