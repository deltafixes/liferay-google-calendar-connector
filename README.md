# Liferay Google Calendar Connector

With the help of this plugin user can sync their Liferay's calendar with google calendar. This plugin is shipped with multiple synchronization options as below. 

- One-way Sync -> Liferay to Google only
- One-way Sync -> Google to Liferay only
- Two-way (Bi-directional) Sync 

In any of the above option, user can seamlessly able to see and manage events. Also user can configure sync interval and sync direction (One or Two way) as well hence events are regularly propagated on each side by configurable periodic background process.

## Environment
1. Liferay 7.0 DXP
2. Liferay 7.0 CE-GA5 +
3. Liferay 7.1 CE-GA1 +

## Features
1. Each user can synchronize their personal Liferay's calendar with google calendar
2. Different Synchronization option
3. User can set Synchronization frequency
4. Delete event
5. New event creation
6. Update event

## How to use
1. Download and install plugin after your server start. Make sure plugin is properly deployed on server.

2. Create Google application in Google developer Console with calendar API by following given [steps](https://docs.gibbonedu.org/administrators/getting-started/installing-gibbon/google-oauth/ "Google Calendar App") .

3. Set Google Calendar authentication credentials (Control Panel &rarr; Instance Settings &rarr; Authentication &rarr; Google Calendar).

![01_instance_setting](https://user-images.githubusercontent.com/27973508/68382502-cf5ef980-0179-11ea-8dcc-b64d0301b305.png)

4. Create public page name as 'Calendar'.

![02_create_calendar_page](https://user-images.githubusercontent.com/27973508/68382504-cf5ef980-0179-11ea-87a2-96e90653a90a.png)

5. You can set page permission as you want, so that only intended user can have access to this page.

6. Put Liferay's Calendar Portlet on 'Calendar' page.

![03_put_calendar](https://user-images.githubusercontent.com/27973508/68382495-ce2dcc80-0179-11ea-8a70-50d025abf6a9.png)

7. To use Google Calendar Sync feature, Go to Service tab and login with your google account and provide required permission by clicking on Enable button

![04_service_enable](https://user-images.githubusercontent.com/27973508/68382496-ce2dcc80-0179-11ea-9863-0987154de45d.png)
![05_google_login](https://user-images.githubusercontent.com/27973508/68382498-cec66300-0179-11ea-8a97-8e213eca00b3.png)

8. After successfully connecting with Google account, user will be able to see list of available Calendar(s). Then user can Sync individual calendar by clicking on "Synchronize" button. By Default On-way [Liferay to Google] option is ON.

![06_service_page_calendar_view](https://user-images.githubusercontent.com/27973508/68382499-cec66300-0179-11ea-9da3-02a6c90b25f2.png)

9. After Synchronizing calendar user will have below options available ("Synchronize Now", "Setting" and "Stop Synchronize") against already Synchronized calendar as shown in below screen.

![view_action_button](https://user-images.githubusercontent.com/24852574/69322040-28df2200-0c6a-11ea-8c08-e1007c3e2401.png) 

By Clicking on "Setting" button, user can select Sync option and Sync interval for individual Calendar. (please refer next step)
By clicking on "Stop Synchronize", it will stop Sync process between two calendars (Liferay and Google).
To Synchronize calendar on demand click on "Synchronize Now" button. This button is only available when user has selected One-way [Liferay to Google] or Two-way [Both] Sync option.

10. Upon clicking on "Setting" below screen will be shown.

![calendar_setting](https://user-images.githubusercontent.com/24852574/69322025-2086e700-0c6a-11ea-8f94-88aa7ae9aaf2.png)

11. Below are the screenshot how calendars (Google and Liferay) look like after doing Synchronization.

![07_liferay_calendar](https://user-images.githubusercontent.com/27973508/68382500-cec66300-0179-11ea-9c2f-c07509451e55.png)
![08_google_calendar](https://user-images.githubusercontent.com/27973508/68382501-cf5ef980-0179-11ea-97ee-631c27ff38eb.png)

Note : "Admin Calendar" can only be sync by Single Admin.

## Support
   Please feel free to contact us on info@deltafixes.com for any issue/suggestions.
