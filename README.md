🌌 <h1>Cosmic Occasions – User & Event Manager</h1>
A Linux-based shell script that helps manage system users along with their event bookings through a simple whiptail-based interactive UI.
📁 Project Type: Linux Shell Scripting
🎓 Submitted for: Project Evaluation

📋 Features
This script allows root users to:

👤 Add a new Linux user and book an event for them

❌ Delete a user and their associated bookings

✏️ Modify existing usernames

📄 View all system users

📅 List upcoming event bookings

📜 View and clear the activity log

All actions are logged in a dedicated log file for tracking and auditing purposes.

🛠️ Requirements
Make sure the following packages/tools are available:

bash (default shell)

whiptail (for GUI dialog boxes)

Run as root or via sudo for user management

🚀 How to Run
✅ Step-by-Step Instructions
Open Terminal (Ctrl + Alt + T)

Switch to Root User
If you're not root already:

sudo su
Download or Place the Script
Make sure your script is saved as:

/root/user_event_manager.sh
Make the Script Executable

chmod +x /root/user_event_manager.sh
Run the Script
./user_event_manager.sh
Navigate the Menu
You'll see a friendly interface like this:

-------------------------------
|      Cosmic Occasions       |
-------------------------------
| 1. Add User + Event Booking |
| 2. Delete User + Booking    |
| 3. Modify User Name         |
| 4. List All Users           |
| 5. View Log File            |
| 6. View All Bookings        |
| 7. Clear Log File           |
| 0. Exit                     |
-------------------------------
🔐 Password Handling
When you choose "Add User + Event Booking":
![image](https://github.com/user-attachments/assets/45eea4f1-82cd-43af-ac70-323146152e01)

The script prompts for a new username.

You'll be asked to set a password for the new user.

You'll then input:

🎉 Event Name
![image](https://github.com/user-attachments/assets/0ec436ff-5bad-48b7-8cb9-24f7256170d6)
![image](https://github.com/user-attachments/assets/cd4529d3-9f61-4df9-968a-d9899527af0e)
![image](https://github.com/user-attachments/assets/7b4cf3f5-52a8-41ae-99ce-f093fe7d1ab8)

📆 Event Date (must be in the future – format YYYY-MM-DD)
![image](https://github.com/user-attachments/assets/c01abb2b-26af-4b09-9d0e-7dc923ade081)

📍 Venue Name
![image](https://github.com/user-attachments/assets/b9e2f1de-2e15-4a92-8cef-05f0f5353179)
![image](https://github.com/user-attachments/assets/64308ca6-463f-42f7-8d28-2305bbb35a1e)
![image](https://github.com/user-attachments/assets/45aa2858-7c2a-4989-bcb0-369c7af4e90d)

If the date or venue conflicts with an existing booking, you’ll be alerted, and the user will not be created.
![image](https://github.com/user-attachments/assets/219c0fda-0289-48de-92aa-8a85df195c54)

All this is securely logged in the system for future reference.
![image](https://github.com/user-attachments/assets/e4d02f8d-075b-462c-bb9d-5a732d3fb3b4)
![image](https://github.com/user-attachments/assets/b07e39fd-44ab-4e93-ac90-cf61da67eb16)

📁 Data & Logs
✅ Booking Data:
Stored in: /root/event_bookings.csv
Format: username,event_name,date,venue

📝 Action Logs:
Stored in: /root/user_management.log
Automatically trimmed if size exceeds 5MB.

🧪 Testing Tips
You can test the script on any Linux distro with bash.
Best viewed on full terminal screen for better dialog presentation.



🏁 Exit Message
When done, select option 0 to safely exit.
You'll be greeted with a message:

Thanks for using the User Manager!
🤝 Contribution
Team Members:

👩‍💻 Priyanka Chaurasia

👩‍💻 Mehak

👩‍💻 Mahi

👩‍💻 Komal

Proudly created as part of our Linux System Administration Project. 🎓

