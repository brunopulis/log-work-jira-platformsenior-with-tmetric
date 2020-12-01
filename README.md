# log-work-jira-platformsenior-with-tmetric
- Install npm modules and dependencies on project 'RegistroHoras' (npm i)
- Configure environment variables - RegistroHoras/cypress.json
  - baseUrlJira
  - userJira
  - passwordJira
  - accountId - TMetric - "The easiest way to find your workspace ID and user ID is to generate a Team Summary report and copy these values from the browser address bar."
    - Example: https://app.tmetric.com/#/reports/ ![#f03c15](405350) `#f03c15` /projects?range=thisweek&user=current,323780
  - userProfileId - TMetric - The same way from accountId
    - Example: https://app.tmetric.com/#/reports/405350/projects?range=thisweek&user=current, ![#f03c15](323780) `#f03c15`
  - tokenTMetric - To get a TMetric API token, on app.tmetric.com: 
    - Click your name in the left bottom corner.
    - Select My Profile in the drop-down list.  
    - On the My Profile page, click the Get new API token link.
    - however, keep a word "Bearer " at the beginning
  - loginSenior and passwordSenior - Change if you need to punch the clock in platform senior
- execute files .bat
