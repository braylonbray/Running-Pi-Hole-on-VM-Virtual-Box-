<p align="center">
  <img src="https://raw.githubusercontent.com/pi-hole/graphics/refs/heads/master/Vortex/vortex_with_text.svg" alt="Pi-hole website" width="168" height="270">
  <br>

</p>
<p><strong> Instructions on how I ran Pi-Hole as my local DNS server using Virtual Box. Benefits of running Pi-Hole is the ability to Block Ads, trackers and Telemetry by intercepting DNS queries  that are known malicious domains.</strong></p>

<h2>**Step One**: Configuring VM Machine for Pi-Hole. (Virtual Box Method)</h2> 
<p></p>
 Create Virtual Machine: <ul style="list-style-type✏️"> 
        <li>In Virutal Box click "Machine" and click "New" or 'CRTL+N'</li>
        <li>Name the VM "Raspberry Pi-Hole"</li>
        <li>Type: Linux</li>
        <li>Subtype: Debian</li>
        <li>Version: Debian (32-bit)</li>
</ul>
Hardware Section:
    <ul style="list-style-type✏️">
        <li>Base Memory: 1024MB</li>
        <LI>Processors: 2 CPUs</LI>
    </ul>
<p></p>
 Hard Disk Section:
    <ul style="list-style-type✏️">
        <li>Create a Virtual Hard Disk Now</li>
        <li>12-16gb of storage should be good but i decided to go with 24gb</li>
    </ul>
    <P><h3>**Click Finish and now lets go into the Settings of the VM we just created**</h3></P>
    <p></p>
  Display:
    <ul style="list-style-type✏️">
        <li>Video Memory: 128MB</li>
    </ul>
  Storage:
   <ul style="list-style-type✏️">
       <li><a href=https://download.raspberrypi.org/rpd_x86_latest">Download Raspberry Pi ISO</a></li>
       <li>In the Controller section, Click on the CD-ROM Icon and to the right under "Atrributes" Click the CD-ROM Icon and Click "Choose a Disk File" and select the <a href=https://download.raspberrypi.org/rpd_x86_latest">ISO File</a> </li>
   </ul>
<p></p>
 Network:
 <ul style="list-style-type✏️">
     <li>Switch Netwwork from NAT to Bridge Adapter</li>
 </ul>
<p><h4>PRESS OKAY AND START VM (Normal Start)</h4></p>

<h2>**Step Two: Configure Operating System**</h2>
 <p></p>
   <ul style="list-style-type✏️">
     <li>Graphical Install</li>
     <li>American English</li>
     <li>Guided - use entire disk</li>
     <li>Select Virtual Disk</li>
     <li>All files in one partition</li>
     <li>Finish Partitioning and write changes to disk</li>
     <li>Write the changes to disk? Yes</li>
     <li>Install the GRUB boot loader to your primary drive? Yes</li>
     <li>Select Virtual Disk</li>
   </ul>
  <p>Installation is now Completed. Continue to Reboot VM</p>
  
 <h2>**Step Three: Configure Raspberry Pi Desktop</h2>
   <ul style="list-style-type✏️">
     <li>Country: United States</li>
     <li>Language: American English</li>
     <li>Timezone: Central</li>
     <li>Check: Use US Keyboard</li>
     <li>Username: *choose your own*</li>
     <li>Password: *Practice using strong passwords*</li>
     <li>Update Software & Restart</li>
   </ul>
<p><h2>**Step Four: Install Pi-Hole</h2></p>
  <ul style="list-style-type✏️">
    <li>See <a href=https://github.com/braylonbray/Running-Pi-Hole-on-VM-Virtual-Box-/blob/4881e835a6cabd035c50e8687e38a16bee371ab8/Install-command.md>Install-Command.md</a> for Installation and Command used in Terminal</li>

    ## 📜 License



- **This guide and original content**: Licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

- **Any original code or scripts**: Licensed under the [MIT License](./LICENSE).

- **Pi-hole software**: Not included in this repository. Refer to the [Pi-hole GitHub repository](https://github.com/pi-hole/pi-hole) for licensing and installation files.
     

    
   
