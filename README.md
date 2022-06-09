### Setting your slack status using keywords in Alfred

**NOTE:** For this to work you need the Powerpack Licence as we are going to use the **workflow** feature.

#### Create a Slack App

1. Go to [https://api.slack.com/apps](https://api.slack.com/apps) and create a new Slack App. ![Monosnap Slack API: Applications | Slack - Vivaldi 2022-06-09 11-38-51](https://user-images.githubusercontent.com/634734/172838511-bf3c00f7-fee5-4d5e-919e-74abebac1c0c.png)
2. Select "From Scratch", give your app a descriptive name and choose the workspace it is supposed to interact with (yes, this only works for one workspace).
3. Now jump straight to "OAuth & Permissions"![Monosnap Slack API: Applications | Ladefuchs Slack - Vivaldi 2022-06-09 14-58-43](https://user-images.githubusercontent.com/634734/172852641-44922734-760e-42f0-8765-41bbff0bce2d.png)
4. Scroll down to Scopes and add the following User Token Scopes: *chat:write, users.profile:read, users.profile:write, users:write*
![Monosnap Slack API: Applications | Happybrush Slack - Vivaldi 2022-06-09 14-59-58](https://user-images.githubusercontent.com/634734/172852917-35b58f91-1978-400d-ba3e-f998a4c0de60.png)
5. Now install the App to your workspace 
![Monosnap Slack API: Applications | Ladefuchs Slack - Vivaldi 2022-06-09 15-02-02](https://user-images.githubusercontent.com/634734/172853320-1c3f5b60-09ad-4da7-9695-1051bcd85eca.png)
6. Grab the User OAuth Token continue to the Workflow installation in Alfred.
![Monosnap Slack API: Applications | Ladefuchs Slack - Vivaldi 2022-06-09 15-02-46](https://user-images.githubusercontent.com/634734/172853688-71b09286-9d43-487f-8fc9-1144605eead2.png)


#### How to install and use it?

1. Download the attached file and double click to install it
2. Open Alfred preferences -> Workflows -> Click on the "Slack status" workflow -> Click on the second icon in the right corner -> In the Workflow Environment Variables box enter your User OAuth Token for the App you created beforehand and finally save and close Alfred
3. Run search
4. Type in "s" keyword
5. You will see 4 default statuses (Available, Remote, Meeting, Vacationing), choose one or enter your custom status by first entering the emoji (without colons) followed by the text (separated with space) (e.g. poop What a lovely day)
6. Hit enter!
7. Navigate to your slack to check it out :)



## Default slack statuses

![slack statuses](https://cloud.githubusercontent.com/assets/2737390/25451697/51f6195e-2ac3-11e7-9d89-8347d338e3bc.png)



## Custom slack status

![custom slack status](https://cloud.githubusercontent.com/assets/2737390/25451749/78b599de-2ac3-11e7-8170-7c9b01f48c50.png)



## Workflow

![slack status workflow](https://cloud.githubusercontent.com/assets/2737390/25451806/a48860aa-2ac3-11e7-82f7-866d4a2ff500.png)

## Can I add my own status?

Of course, just right click in the workflow box and a new "Input keyword" and "Arg and Vars utility" which you will connect to the keyword and script, just inspect one of the defaults.

## Licence

[MIT Licence](https://gabskoro.mit-license.org/) © Gabrijel Škoro & Bastian Wölfle
