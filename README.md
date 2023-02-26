# Nautilus Tips
Tips and tricks for running Linux on my Chromebook (codename: nautilus)

# Disabling touchscreen in Xournal++
Palm rejection wasn't working under Wayland, but through some googling I managed to cobble together this solution. Using the evtest tool with the `--grab` arguent I route input from the touchscreen to `/dev/null` whenever the stylus is detected by Xournal++.

![image](https://user-images.githubusercontent.com/22671761/221425874-2485ad26-7c7c-4b76-b1eb-996aac74ad6f.png)

