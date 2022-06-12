# Applications Quality

- App must be the same as the given design.
- App must be tested by the developer before it’s delivered to the tester and each part of the app must be working as it’s developed to work.
- For cross-platform apps (`React Native`, ...etc.), design must be reviewed, and app must be tested as mentioned on the above two points on both `Android` and `iOS` before it’s delivered to the tester.

## Applications network related operations

- Any page that load data must has a loading indicator appearing till the data loaded successfully.
- If load data operation failed or had some exception, a message must be displayed to the user to notify him that there is a problem in loading data.
- If the data is empty, a message must be displayed to the user to notify him that there is no data available.
- Any operation that require a network call (login, signup, ...etc.) must have a loading indicator while it’s in progress.
- Any network related button (login, signup, ...etc.) must be clickable only once till the operation is finished. You must not leave the user click the button many times while operation is still running.
- If the operation failed or had some exception, a message must be displayed to the user to notify him that there is a problem in doing that operation.
