Session storage is temporary storage in browser
deleted automatically when browser is closed
Keeps info until browser is open
Not accessable across browser tabs.
A form cannot create a session automatically, we need to create session manually
sessionStorage.setItem("key",value);
sessionStorage.getItem("key");
sessionStorage.removeItem("key");

sessionStorage is a browser indow object related memory

1. If session login not done and accessing dashboard directly then redirects to login page
2. Give Signout option to delete the session
3. setTimeout so that after specified time the session is logged out automatically displaying an alert and redirecting to login page

Ex: Bank webpage close browser then session terminates, signed out automatically