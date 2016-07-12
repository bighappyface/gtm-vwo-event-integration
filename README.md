# gtm-vwo-event-integration
GTM container export of event-based tracking of VWO campaigns


## Installation / Container Import

1. Download the file 'gtm-vwo-event-integration.json' from this repository.
2. In Google Tag Manager, navigate to the **Admin** tab.
3. Under the **Container** column, select **Import Container**.
4. Click **Choose Container File** and select the 'gtm-vwo-event-integration.json' file you downloaded.
5. Select **Merge** from the radio selector beneath the Choose Container File button.
6. Select **Rename** from the radio selector that appears beneath the Merge selector.
7. Click Continue, then Confirm.
8. Navigate to the Variables interface - select the tag imported variable named _VWO - GA Property ID_.
9. Change the value _UA-12345678-1_ to your Google Analytics Tracking ID (a.k.a. UA Number).

Once you publish your next container VWO tracking will begin working immediately.
