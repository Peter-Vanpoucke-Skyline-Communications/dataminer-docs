# Installing DataMiner IDP

To install and set up DataMiner IDP:

1. Make sure the necessary prerequisites are available:

    - DataMiner version 10.0.0 CU9 or higher must be installed in your DMS.

    - If you want to use scheduled activities, DataMiner Indexing must be installed in your DMS.

    - If you want to use Process Automation, DataMiner SRM, Process Automation and Token activity must be installed. If you want to be able to repeat processes with a timer, you also need to install the Repeat Gateway.

2. Double-click the DataMiner IDP package.

3. In the upgrade window, click the *Upgrade* button. The installation will begin, and the installation progress will be displayed.

4. When the installation process has finished, the *Upgrade Summary* window will display information on any issues that have occurred. Click *Close* to go back to the main upgrade window.

5. Click the *Finished* button to close the upgrade window.

6. Connect to your DataMiner System using DataMiner Cube.

    > [!TIP]
    > See also:
    > [Opening DataMiner Cube](../../part_1/DataminerApplications/Opening_DataMiner_Cube.md)

7. In DataMiner Cube, go to *Apps* > *Automation*.

8. Select the script *IDP_SetupWizard* and click *Execute*.

9. On the first page, click the button *Execute Now*.

10. On the welcome page, click *Next*.

11. On the view selection page, specify which views should be used by DataMiner IDP:

    1. For each of the sections, either select *Create a new view* or select *Use existing view* and select the view in the drop-down list.

    2. In case you use an existing view that is not yet under the TOP view, select the option *Move existing views under TOP* view.

    3. Click *Confirm*.

12. On the confirmation page, click *Confirm*.

13. On the following page, specify whether a new or an existing user account will be used for internal IDP communication:

    1. If no suitable user account exists in your system yet, click *Yes*, *go ahead*. Otherwise, click *No*, *I would like to use an existing user* and select the account in the drop-down list.

    2. Specify the password for the user account in both the *Password* and *Confirm Password* boxes, and click *Confirm*.

    > [!NOTE]
    > - Do not specify a user account of which the password is subject to an expiration policy. We recommend to create a dedicated IDP account if no such account exists yet.
    > - If you run the setup wizard again after the initial setup, you can choose to specify different user credentials. However, by default the same user credentials will continue to be used, so you do not have to specify anything.

14. On the *IDP Extra Configurations* page, optionally customize the HTTP binding address, with the corresponding HTTP mode and port.

15. From IDP version 1.1.5 onwards, on the *IDP Extra Configurations* page, you can also specify the path and credentials for the configuration archive.

    > [!NOTE]
    > You can also configure these settings in the IDP app after the initial setup, via *Admin* > *Configuration* > *Network Share*.

16. Click *Next* until you reach the last page of the wizard.

17. On the last page of the wizard, click *Confirm*.

18. When the configuration of the IDP module has finished, which may take some time, click *Finish*, and on the next page, click *Close*.

> [!NOTE]
> To upgrade IDP if the app is already installed, follow the same procedure as detailed above. However, instead running the *IDP_SetupWizard* script from the Automation app, you can do so by going to *Admin* > *Settings* in the IDP app and clicking the button next to *Setup Wizard*.
>