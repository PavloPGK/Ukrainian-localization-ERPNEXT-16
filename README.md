**Ukrainian localization ERPNEXT 16** <br>
Українська локалізація ERPNEXT 16 <br>
 <br>
**Installation option 1: via file uk.po** <br>
sudo cp /mnt/myusb1/uk.po /home/[user]/frappe-bench/apps/erpnext/erpnext/locale/ <br>
cd /home/[user]/frappe-bench/apps/erpnext/erpnext/locale/<br>
sudo chown [user]:[user] uk.po<br>
chmod 644 uk.po<br>
cd /home/[user]/frappe-bench/<br>
bench --site site1.local migrate<br>
bench --site site1.local clear-cache<br>
<br>

<br>
**Installation option 1: via file uk.csv** <br>
sudo mkdir -p /home/[user]/frappe-bench/apps/erpnext/erpnext/translations<br>

sudo cp /mnt/myusb1/uk.csv /home/[user]/frappe-bench/apps/erpnext/erpnext/translations/<br>
sudo chown -R [user]:[user] /home/ufrap16/frappe-bench/apps/erpnext/erpnext/translations<br>
cd /home/[user]/frappe-bench/<br>
bench --site site1.local import-translations uk apps/erpnext/erpnext/translations/<br>


<img width="1607" height="1342" alt="Screen 2026-05-07 18-08-32" src="https://github.com/user-attachments/assets/05fa64f7-49a4-449a-be29-f6fec91ebb6b" />





