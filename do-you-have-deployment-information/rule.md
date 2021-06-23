---
type: rule
archivedreason: []
title: do-you-have-deployment-information
guid: 7184d9cd-0403-45ec-9b5c-a1c3f99caf03
uri: do-you-have-deployment-information
created: 2021-06-23T05:06:33.0000000Z
authors: 

- title: Chris Briggs
  url : https://au.linkedin.com/in/chrisbriggsy
related: []

---

<!--endintro-->

Every page on a website should have a version number. We have found this is the best way to keep track of changes to the site. Display the version number at the bottom of the page. The version information should display the application version number, the database version number and optionally the date last updated.

The version number increase and display should be automated to avoid developer error, and the best way to do this is to use the Version component from SSW.Framework.MVC.

::: good
![Figure: Good example - Version information from SSW TimePRO](https://user-images.githubusercontent.com/86330564/123016650-6ee40500-d40e-11eb-9b2a-baf287e9afa6.png)
:::



::: good
![Figure: Better example - SSW Website displays Continuous Deployment information including date and changeset](https://user-images.githubusercontent.com/86330564/123016707-8de29700-d40e-11eb-81cb-3b1e3da18cae.png)
:::


