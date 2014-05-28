cloudfoundry-sticky-session
===========================

Simple Java web app that prints Cloud Foundry environment variables and cookies and is useful to showcase sticky sessions.

It also lets you test the HealthManager by sending a "http://host/?shutdown=true" request.

You should be able to push it to a Cloud Foundry environment by using `cf push` from the root directory that has the `manifest.yml` file.

Maybe you have to change the host in the 'manifest.yml' file because it is already in use.