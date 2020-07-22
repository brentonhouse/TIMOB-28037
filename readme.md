
# TIMOB-28037

Test project for https://jira.appcelerator.org/browse/TIMOB-28037

Running the project on iOS and Android should result in an alert dialog showing "hello".

On Android, this works but is broken on iOS.

Issue is related to relative path require statements inside node_modules directories.

> Look at `/app/vendor/node_modules/test`