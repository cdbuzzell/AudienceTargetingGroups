# AudienceTargetingGroups
Power App (and Power Automate flows) to enable users to self-service join and leave Entra ID Security Groups that are used for Audience Targeting in SharePoint

1. Create a SharePoint Online custom, blank list titled "Audience Targeting Groups"
2. Add a Text column titled "GroupId"
3. Populate the list with names and IDs of Entra ID Security Groups that are used for audience targeting
4. Import the Power Platform solution above
5. Change the connection reference to point to your list and use a service account user for adding/removing group members
