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
       <li>Download Raspberry Pi ISO</li>
       <li>In the Controller section, Click on the CDRom Icon and to the right under "Atrributes" Click the CD Drive Icon and Click "Choose a Disk File" </li>
    
   
