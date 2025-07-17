
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)





---

## 1. Secure Permissions

```sh
sudo chmod 0644 /var/www/html/osticket/include/ost-config.php
sudo rm -rf /var/www/html/osticket/setup/
```

---

## 2. Log in to the Admin Panel

- Open your browser and go to:  
  `http://<your-server-ip-or-domain>/osticket/scp`
- Use the admin credentials you set during installation.

---

## 3. Change Default Admin Email and Name

1. In the osTicket admin panel, go to **Admin Panel** > **Staff** > **Manage Staff**.
2. Edit the main admin account.
3. Set a secure email and display name.
4. Save Changes.

---

## 4. Configure System Email

1. Go to **Admin Panel** > **Emails** > **Emails**.
2. Click **Add New Email** or edit the existing default email.
3. Enter the email address your helpdesk should use to send/receive tickets.
4. Set up SMTP (for sending) and IMAP/POP (for fetching), if required.
5. Save Changes.

---

## 5. Set Up Departments

1. Go to **Admin Panel** > **Staff** > **Departments**.
2. Click **Add New Department**.
3. Name the department (e.g., Support, Sales).
4. Assign Department Manager and email.
5. Save Changes.

---

## 6. Add Staff Members

1. Go to **Admin Panel** > **Staff** > **Staff Members**.
2. Click **Add New Staff Member**.
3. Fill in name, email, and assign a department and role.
4. Save Changes.

---

## 7. Configure Help Topics

1. Go to **Admin Panel** > **Manage** > **Help Topics**.
2. Click **Add New Help Topic**.
3. Name your topic (e.g., Technical Support, Billing).
4. Save Changes.

---

## 8. Set Up Ticket Auto-Response

1. Go to **Admin Panel** > **Settings** > **Tickets**.
2. Enable or disable auto-response for new tickets and messages as needed.
3. Save Changes.

---

## 9. Customize Ticket Forms

1. Go to **Admin Panel** > **Manage** > **Forms**.
2. Edit the **Ticket Details** form to add/remove fields as needed.
3. Save Changes.

---

## 10. Configure Alerts & Notices

1. Go to **Admin Panel** > **Settings** > **Alerts & Notices**.
2. Adjust notifications for new tickets, ticket assignments, replies, etc.
3. Save Changes.

---

## 11. Set Time Zone and Date/Time Format

1. Go to **Admin Panel** > **Settings** > **System**.
2. Set your correct time zone and preferred date/time format.
3. Save Changes.

---

## 12. Enable CAPTCHA (Optional, for security)

1. Go to **Admin Panel** > **Settings** > **Users**.
2. Scroll to **Human Verification**.
3. Enable CAPTCHA for web forms if desired.
4. Save Changes.

---

## 13. Test Your System

- Create a test ticket as a user.
- Ensure staff receive notifications and can respond.
- Test email piping/fetching if configured.

---

## 14. Backup Your Configuration

- Regularly back up your osTicket database and configuration files.

---

**References:**
- [osTicket Admin Guide](https://docs.osticket.com/en/latest/Admin/Getting%20Started.html)
- [osTicket Forum](https://forum.osticket.com/)

---
You have now completed the essential post-install configuration for osTicket!
<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
