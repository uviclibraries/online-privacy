---
layout: default
title: 1-Disable App Tracking 
nav_order: 3
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---
<img src="images/tinkercad-keychain-01.png" style="float:right;width:200px;height:200px;" alt="tinkercad logo"> 

# Activity 1: Kill the “Social Graph” (App Tracking)

In this activity, you'll reduce the amount of information that apps can collect about you by disabling cross-app tracking. This helps limit the creation of a detailed advertising profile and makes it harder for companies to connect your activity across different apps.

If you have any questions or get stuck, please ask the instructor for assistance.

### Why are we doing this?

Many popular apps collect information about your activity and share it with advertising networks. Turning off app tracking reduces this data sharing and helps protect your privacy.

---

### iPhone

1. Open the **Settings** app.
   
3. Scroll down and tap **Privacy & Security**.
   ![Privacy & Security menu](images/privacy-tracking-02.png)

4. Tap **Tracking**.
   ![Tracking menu](images/privacy-tracking-03.png)

5. Toggle off **Allow Apps to Request to Track**.
   ![Disable app tracking](images/privacy-tracking-04.png)

6. This prevents apps from accessing your device's unique Advertising ID (IDFA), making it much more difficult for advertisers to track your activity across different apps and websites.


### Android

1. Open the **Settings** app.

2. Tap **Privacy**

3. Select **Ads**

4. Tap **Delete Advertising ID**.

5. Confirm that you want to delete your Advertising ID

This makes it significantly more difficult for advertisers and data brokers to link your activity across different apps.

### Discussion

After completing this activity, consider the following questions:

---

Congratulations! You've taken an important step toward protecting your digital privacy.




<img src="images/tinkercad-keychain-03b.png" style="float:right;width:400px" alt="visual example"> 


    <button onclick="toggle('gif1')">Show/Hide Animation</button>
    <div id="gif1">
    <img src="images/tinkercad-keychain-04.gif">
    </div>

<script>  

    function toggle(input) {
        var x = document.getElementById(input);
        if (x.style.display === "none") {
            x.style.display = "block";
        } else {
            x.style.display = "none";
        }
    }
</script>

[NEXT STEP: Downloading Shielded Browser](2-shielded-browser.html){: .btn .btn-blue }
