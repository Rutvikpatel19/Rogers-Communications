# Network Command Reference For Nokia OLT

Below are some useful network commands. You can preview them and copy them using the buttons next to each command.

---

## Commands:

### 1. Show PON Interface Current Interval
<pre><code id="command1">show pon interface tc-layer current-interval 1/1/12/1</code></pre>
<button onclick="copyToClipboard('command1')">Copy</button>

### 2. Show PON Interface Previous Interval
<pre><code id="command2">show pon interface tc-layer previous-interval 1/1/12/1</code></pre>
<button onclick="copyToClipboard('command2')">Copy</button>

### 3. Show SFP Inventory for a Specific Interface
<pre><code id="command3">show pon sfp-inventory 1/1/12/1</code></pre>
<button onclick="copyToClipboard('command3')">Copy</button>

### 4. Show Optical Performance for PON Interface
<pre><code id="command4">show pon optics 1/1/12/1</code></pre>
<button onclick="copyToClipboard('command4')">Copy</button>

### 5. Show PON Diagnostics for Interface
<pre><code id="command5">show pon pon-diagnostics 1/1/12/1</code></pre>
<button onclick="copyToClipboard('command5')">Copy</button>

### 6. Show Transceiver Inventory
<pre><code id="command6">show equipment transceiver-inventory</code></pre>
<button onclick="copyToClipboard('command6')">Copy</button>

### 7. Show Detailed Transceiver Information for Specific Slot
<pre><code id="command7">show equipment transceiver-inventory lt:1/1/3:sfp:5 detail</code></pre>
<button onclick="copyToClipboard('command7')">Copy</button>

### 8. Show Equipment Diagnostics for SFP
<pre><code id="command8">show equipment diagnostics sfp detail</code></pre>
<button onclick="copyToClipboard('command8')">Copy</button>

### 9. Show Detailed Equipment Diagnostics for a Specific SFP
<pre><code id="command9">show equipment diagnostics sfp lt:1/1/12:sfp:1 detail</code></pre>
<button onclick="copyToClipboard('command9')">Copy</button>

### 10. Show SFP Threshold Diagnostics
<pre><code id="command10">show equipment diagnostics sfp-threshold lt:1/1/12:sfp:1 detail</code></pre>
<button onclick="copyToClipboard('command10')">Copy</button>

### 11. Show Equipment ONT Status (Exact Match)
<pre><code id="command11">show equipment ont status x-pon | match exact:1/1/1/4/</code></pre>
<button onclick="copyToClipboard('command11')">Copy</button>

### 12. Show Equipment Temperature
<pre><code id="command12">show equipment temperature</code></pre>
<button onclick="copyToClipboard('command12')">Copy</button>

### 13. Display Configuration for a Specific Context
<pre><code id="command13">A:agw07.mtwd# admin display-config | match VGHNON65OLT context all ignore-case</code></pre>
<button onclick="copyToClipboard('command13')">Copy</button>

### 14. Show Detailed SFP Diagnostics for Slot 1/1/3
<pre><code id="command14">show equipment diagnostics sfp lt:1/1/3:xfp:5 detail</code></pre>
<button onclick="copyToClipboard('command14')">Copy</button>

### 15. Show Port Description for a Specific AGW
<pre><code id="command15">show port description | match agw</code></pre>
<button onclick="copyToClipboard('command15')">Copy</button>

### 16. Show Active Subscribers for Specific Service Profile
<pre><code id="command16">show service active-subscribers hierarchy | match "ALCLF9D58E33" context all ignore-case</code></pre>
<button onclick="copyToClipboard('command16')">Copy</button>

### 17. Show Active Subscribers for a Different Profile
<pre><code id="command17">A:agw07.nbmn# show service active-subscribers hierarchy | match ""ALCLCBDDFD20"" context all ignore-case</code></pre>
<button onclick="copyToClipboard('command17')">Copy</button>

### 18. Show Port Description for SAP
<pre><code id="command18">sh int desc | match CDN</code></pre>
<button onclick="copyToClipboard('command18')">Copy</button>

### 19. Show ONT Status for Down Interfaces
<pre><code id="command19">show equipment ont status x-pon | match exact:down</code></pre>
<button onclick="copyToClipboard('command19')">Copy</button>

### 20. Show LAG Description for a Specific AGW
<pre><code id="command20">show lag description | match OKVMON91OLT</code></pre>
<button onclick="copyToClipboard('command20')">Copy</button>

### 21. Show Core Uptime
<pre><code id="command21">OKVMON91OLT:owen.yuen]#show core1-uptime</code></pre>
<button onclick="copyToClipboard('command21')">Copy</button>

### 22. Show Active Subscribers for ALCLCCC4211F Profile
<pre><code id="command22">show service active-subscribers hierarchy | match ALCLCCC4211F context all</code></pre>
<button onclick="copyToClipboard('command22')">Copy</button>

### 23. Ping a Specific IP Address
<pre><code id="command23">ping 173.35.202.74</code></pre>
<button onclick="copyToClipboard('command23')">Copy</button>

### 24. Clear Specific IPOE Session
<pre><code id="command24">clear service id 124 ipoe session sap lag-43:2318.1103</code></pre>
<button onclick="copyToClipboard('command24')">Copy</button>

### 25. Show Subscriber Management Errors for SAP
<pre><code id="command25">show subscriber-mgmt errors sap lag-55:2307.1101</code></pre>
<button onclick="copyToClipboard('command25')">Copy</button>
