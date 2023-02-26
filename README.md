# Nautilus Tips
Tips and tricks for running Linux on my Chromebook (codename: nautilus)

# Dsabling touchscreen in Xournal++
Palm rejection wasn't working under Wayland, but through some googling I managed to cobble together this solution. Using the evtest tool with the `--grab` arguent I route input from the touchscreen to `/dev/null` whenever the stylus is detected by Xournal++.
![image](https://user-images.githubusercontent.com/22671761/221425752-a047f110-35f3-478d-8735-05f89144e041.png)
