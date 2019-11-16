# **JellyMap - Jelly Comb keyboard map**
### **AutoHotKey script that makes Jelly Comb WGJP-019B bluetooth keyboard fit for work under windows**

In itself it is a small and nice keyboard but it provides some cumbersome keymapping.  
The Fn has to be pressed for reaching escape and function keys, because the mostly  
uncommon used media keys have precedence.

To make things more complicated the special keys for select, copy, paste and delete are  
sending standard windows sequences CTRL-A, -C, -V, -X. If simply filtered out, those  
sequences would not work even when really pressing CTRL-A, -C, -V, -X. 

Luckily the keyboard can be switched to send standard IOS sequences instead.  
Those do not interfere with their windows counterparts and can be filtered without loss.  
So be sure to switch the keyboard to IOS when running the script (even when working under windows).

### OS-switching
- Fn-A -> Android  
- Fn-S -> Windows  
- Fn-D -> IOS  

Some other mappings are also necessary, see the script for details.

To add the script to autostart, press Win-R and enter  
`%appdata%\Microsoft\Windows\Start Menu\Programs\Startup`  
right click for context menu and add a link to your script

### **Versions**
\- 1.0 initial  

### **Links**
https://www.autohotkey.com/  
https://www.maketecheasier.com/schedule-autohotkey-startup-windows/

---

#### contact
[qrt@qland.de](mailto:qrt@qland.de)
