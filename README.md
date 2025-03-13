# macOS  on Honor Magicbook X15 2022 
<p align="center">
<img src="Wiki/Images/magicbook-x15-sequoia.png" alt="Huawei macOS Sequoia" width="450" />
</p>
<p align="center">
<a href="https://www.honor.com/my/support/laptop/honor-magicbook-x15/" target="_blank"><img src="https://img.shields.io/badge/Model-BBR_WA19-orange.svg" /></a>
<a href="https://www.honor.com/my/support/laptop/honor-magicbook-x15/" target="_blank"><img src="https://img.shields.io/badge/BIOS-3.16-red.svg" /></a>
<a href="https://github.com/DC4114/Magicbook-X15-2022/releases" target="_blank"><img src="https://img.shields.io/badge/Download-Releases-blue.svg" /></a>
<a href="https://github.com/DC4114/Magicbook-X15-2022/wiki" target="_blank"><img src="https://img.shields.io/badge/Support-Wiki-green.svg" /></a>
</p>

<div align="center">


|    macOS    |   |   Status   |
| :--- | :--- | :--- |
|   <img src="Wiki/Images/assets_sequoia.png" width=25 hspace=2 /> <a href="https://developer.apple.com/documentation/macos-release-notes/" target="_blank"><img src="https://img.shields.io/badge/macOS-Sequoia-brightgreen.svg" /></a>    |   `Stable` Version 15.3.1 (24D70)  »  latest |   `Current version`   |
|   <img src="Wiki/Images/assets_sonoma.png" width=25 hspace=2 /> <a href="https://developer.apple.com/documentation/macos-release-notes/" target="_blank"><img src="https://img.shields.io/badge/macOS-Sonoma-red.svg" /></a>    |   `Stable` 14.3.1 (23D60)  »  latest |   `Compatible`   |
|   <img src="Wiki/Images/assets_ventura.png" width=25 hspace=2 /> <a href="https://developer.apple.com/documentation/macos-release-notes/" target="_blank"><img src="https://img.shields.io/badge/macOS-Ventura-red.svg" /></a>    |   `Stable` 13 (22A380)  »  13.6.6 (22G630) |   `Compatible`   |
|   <img src="Wiki/Images/assets_monterey.png" width=25 hspace=2 /> <a href="https://developer.apple.com/documentation/macos-release-notes/" target="_blank"><img src="https://img.shields.io/badge/macOS-Monterey-red.svg" /></a>   |   `Stable` 12.0.1 (21A559)  »  12.5.1 (21G83) |   `Compatible`   |
|   <img src="Wiki/Images/assets_big_sur.png" width=25 hspace=2 /> <a href="https://developer.apple.com/documentation/macos-release-notes/" target="_blank"><img src="https://img.shields.io/badge/macOS-Big_Sur-red.svg" /></a>    |   `Stable` 11.0.1 (20B29)  »  11.6.8 (20G730) |   `Compatible`   |
<div/>

<br>
<div align="left">

## <strong>🖥️ Configuration</strong>

</div>


</p>
<div align="left">
  
| Specifications      | Details                                          |
| :--- | :--- |
| Computer model      | Honor Magicbook X15 Space Gray                   |
| Processor           | Intel Core i3-10110U Processor @ 2.6 GHz         |
| Memory              | 8 GB DDR4x2 2400 MHz [Sk Hynix]                  |
| Hard Disk           | SSSTC M.2 NVMe 256 GB [CL1-8D256]                |
| Integrated Graphics | Intel(R) UHD Graphics 620                        |
| Screen              | BOE NV15 Display @ 1920 x 1080 (15.6 inch)       |
| Sound Card          | Realtek ALC256                                   |
| Wireless Card       | Intel Dual Band Wireless-AC 8265/8275            |
| Bluetooth Card      | Intel Bluetooth 8265/8275                        |
<div/> 



<br>
<div align="left">

## <strong> 🔧 Status</strong>

</div>


</p>
<div align="left">

| Function       | Status       |
|---------------|-------------|
| Intel UHD 620         | ✅ Working  |
| Audio      | ✅ Working  |
| Headphones    | ✅ Working  |
| Touchpad      | ✅ Working  |
| Wi-Fi         | ⚠️ Working  |
| Bluetooth         | ✅ Working  |
| Sleep Mode         | ✅ Working  |
| HDMI output         | ✅ Working  |
| USB      | ✅ Working  |
| brightness control     | ✅ Working  |
| Camera   | ❌ Not Working |
| Fingerprint Sensor | ❌ Not Working |

</div> 
<br>
<div align="left">

## <strong> 📌 Notes</strong>

</div>

</p>
<ul>
  <li><strong>⚠️warning: This EFI is meant to be used as a starting points</strong>.</li>
  <li><strong>⚠️warning: You should create your own EFI from scratch to ensure stability and compatability with your device.</strong></li>
  <li>Change MLB, ROM,etc.. using MacBookAir9,1 SMBIOS.</li>
  <li>OpenCore and Kexts are up to date. [Feb 10 2025] </li>
  <li>⚠️ Currently, Wi-Fi only works with Heliport.</li>
  <li>Audio works via <code>AppleALC.kext</code> and <code>layout-id 21</code></li>
  <li>Camera isn't working on my model <code>[ov9734_azurewave_camera]</code>, but it might work on other models.</li>
</ul>

</div> 
<br>
<div align="left">
<details>
<summary><strong>📊 Benchmarks</strong></summary>

 ![](Wiki/Images/geekbench_1.jpeg) 
 ![](Wiki/Images/geekbench_MC.jpeg) 
 ![](Wiki/Images/geekbench_SC.jpeg) 

</div>

<br>
<div align="left">

## <strong> ⚙️ Changelog</strong>

</div>

</p>

<li>Updated <code>Opencore 1.0.3</code> and Kexts to the latest Version</li>
