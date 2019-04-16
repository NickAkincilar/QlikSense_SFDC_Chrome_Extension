
Do you have Salesforce customers that would like to embed Qlik in to SFDC but haven't done so because they think it is too complex or they don't want to mess with SFDC configurations? This simple Chrome Extension will allow any SFDC user to be able to embed upto 4 charts from any app directly in to SFDC Account & Opportunity pages. No admin or configuration required on the Salesforce side. All you need is QlikSense App(s) that contains SFDC Account and/or Opportunity Id values within the data model so the extension can properly filter the data.

This extension works by extracting Acct & Opp ID values from the rendered SFDC page and then injecting dynamic QS Iframe links in to standard SFDC pages directly in to the page's HTML code.

  

## HOW TO INSTALL

1.  Download & Unzip the following file. **[QlikPopUps_Chrome_Extension.zip](https://confluence.qliktech.com/download/attachments/156501595/QlikPopUps_Chrome_Extension.zip?version=1&modificationDate=1555360077237&api=v2)**
2.  Open chrome browser and navigate to this link: chrome://extensions/
3.  Enable **Developer Mode**
    
    ![](https://github.com/NickAkincilar/QlikSense_SFDC_Chrome_Extension/blob/master/DeveloperMode.jpg?raw=true)
    
4.  Click on **LOAD UNPACKED** and choose the **folder** that you unzipped the extension.
    
    ![](https://github.com/NickAkincilar/QlikSense_SFDC_Chrome_Extension/blob/master/LoadUnpacked.jpg?raw=true)
    
5.  You can now **DISABLE** the **DEVELOPER MODE**
    
6.  That's it. You should now see a SFDC/Qlik Icon that you can use to configure your embedded Charts in to standard Salesforce pages !!  
    ![](https://github.com/NickAkincilar/QlikSense_SFDC_Chrome_Extension/blob/master/Options.jpg?raw=true)
    

  

## HOW TO CONFIGURE


1.  Enter the Qliksense server name & virtual proxy name (if any)
2.  Enter the root URL of the SFDC site so it does not inject charts in to other instances.
3.  Fill in the App & ChartID values for Account and/or Opportunity Sections where you can obtain via Devhub \ Single Configurator.
4.  Account & Opportunity FieldNames are the actual field names used within the Qlik Apps that contain the SFDC Account & Opp id values for proper filtering of the charts.
5.  Click  **SAVE**  button. (_Saving the configuration will update the Settings JSON string that you can send others to share_)
6.  That's it!  
      
 ![](https://github.com/NickAkincilar/QlikSense_SFDC_Chrome_Extension/blob/master/Settings.jpg?raw=true)    

You can also **import or export an existing configuration**  using  **Import Settings**  button. Just paste the configuration JSON string in to the box and click on  **IMPORT**  &  **SAVE**. It will preconfigure all the fields for you. 

If you manually configure all the settings, you can hit the **SAVE** button which will overwrite the JSON string in the settings textbox. You can copy this JSON string and share with others to replicate the same configuration where they can paste & import it.

