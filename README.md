# 4cat
Sinar Project's public server to try out [4cat](https://github.com/digitalmethodsinitiative/4cat), a research tool to collect and analyse social media data, now available for limited usage. If interested, please email team@sinarproject.org to be added as a user on the server. 

This tool would need to be used together with https://tools.digitalmethods.net/zeeschuimer, which is only available only as a Firefox browser plugin.

This version can support the collection of data from these sources:
- TikTok (posts)
- TikTok (comments)
- Instagram (posts & reels)
- LinkedIn
- 9GAG
- Imgur
- X/Twitter
- Douyin
- Gab
- Truth Social
- Threads
- Pinterest
- RedNote/Xiaohongshu
- RedNote (comments)

## Basic use of data crawling from social media

**What you will need:**
- Firefox browser https://www.firefox.com/en-US/
- Social media account from one of the sources above (logged in where you can see the posts in the browser)
- Firefox plugin https://tools.digitalmethods.net/zeeschuimer (just click on the link and it will be downloaded to your computer)
- Login credentials to https://try4cat.sinarproject.org/

**Steps**
1. When you get the login token link, open the URL in your Firefox browser and reset your password. Then log in using the password you set.
   
2. Then, in the same browser, navigate to the menu (3-line button at the top right, underneath the X button) and go to Extensions and Themes.

<img width="426" height="1017" alt="Screenshot from 2026-05-26 13-31-07" src="https://github.com/user-attachments/assets/78923cec-5d98-4fb3-9bbc-f094a5e45832" />


3. Go to the Extensions menu (choose the Puzzle symbol from one of the options on the left)

<img width="861" height="322" alt="image" src="https://github.com/user-attachments/assets/ae0e20e9-545d-43f1-b6b5-258cfc662995" />

4. From the Settings button choose "Install Add-on from File"

<img width="861" height="322" alt="image" src="https://github.com/user-attachments/assets/6782af9f-b0e2-498e-9c54-8433ad9d3a65" />


5. On the window popped out, navigate to your Downloads folder and look for the file "zeeschuimer-1.13.6.xpi"

6. A window will pop up on your Firefox browser like this. Click "Add"

<img width="595" height="378" alt="image" src="https://github.com/user-attachments/assets/3dbe468b-e173-413b-b5a0-8302bcc89e30" />

7. Check "Pin extension to toolbar" and click OK

<img width="603" height="204" alt="image" src="https://github.com/user-attachments/assets/2bb27dda-3092-4ccf-9cbd-222b0e0c811f" />

8. In browser header, add a new tab and open your social media website. Here we use TikTok (https://www.tiktok.com/), which is possible to crawl data without any login.

9. In another tab, click the new "Z" button in your browser. This will open the Zeeschuimer plugin.
<img width="202" height="55" alt="image" src="https://github.com/user-attachments/assets/eebe1383-51c9-43a5-80ff-caf3f6ba66e2" />

10. Turn on Active for TikTok (posts) and input the 4CAT server URL here i.e. https://try4cat.sinarproject.org/ (make sure you have logged in here)

<img width="819" height="964" alt="image" src="https://github.com/user-attachments/assets/747625b0-6338-43b8-99ef-d9f1f6a4f488" />

11. Now that the plugin is enabled, it will start crawling data. Go back to the tab with TikTok and start scrolling down. As you scroll the plugin will collect data.
  
12. After a few posts, notice that the "Items" in the Zeeschuimer tab had increased from 0, showing that there is data. Under Actions, click "to 4CAT" to upload the data to 4CAT.
<img width="819" height="964" alt="image" src="https://github.com/user-attachments/assets/aa0ed1f4-8e8e-49f2-bcbd-21598854b107" />

13. Go back to the 4CAT tab and navigate to "Datasets". You will now have a CSV dataset from TikTok! 

<img width="825" height="648" alt="image" src="https://github.com/user-attachments/assets/8e3fdf63-6e6f-412f-b15a-7fd34cea0f54" />

## Examples of datasets collected
https://drive.google.com/drive/folders/1tFbL4aq7YG4ByzRSOjOBokbMYAXOcP_d?usp=drive_link 

## Other resources
https://slides.degeling.com/tiktok-research-methods/

