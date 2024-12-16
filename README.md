a.	What is your security recommendation? Why did you choose it?

My security recommendation is about the app permissions. The app only requests the minimum set of permissions necessary because it enhances user privacy reduces risks of leaking data from users and isolates application-level features with minimal risk.

b.	Who does the recommendation benefit (end-user, developer, etc.)?

    + The end-user: They got benefits from this recommendation. It reduced risks from privacy data improved security and increate trust in the application.
    + Developer: It easily isolates features when the developers want to debug the application.

c.	If the recommendation was found somewhere other than the provided checklist, include a link to it. 

I just used the recommendation from the checklist. It’s enough for our application.

d.	When would the recommendation have to be implemented (based on how serious the security risk is)?

I think that we can consider implemented it from low level the security risk during the development of the application because we can easy control before release and after release the application. 

e.	Why do you think your project needs your recommendation?

Because I saw it in my android manifest files. It requirement some permission, but it may not be needed at the moment. For example as bellow

 <!-- OPTIONAL PERMISSIONS, REMOVE WHATEVER YOU DO NOT NEED ->
 <uses-permission android:name="android.permission.SYSTEM_ALERT_WINDOW"/>
  <uses-permission android:name="android.permission.VIBRATE"/>
  <!-- These require runtime permissions on M -->
 <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE"/>
 <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
  <!-- END OPTIONAL PERMISSIONS -->

f.	How do you think your recommendation could be applied?

I think it’s easy to apply for our application by removing some permission not needed and it doesn’t affect to our application.

g.	How feasible would the implementation be?

I think that it is feasible when we just request permission, such as location or Internet, to provide features for our application.


