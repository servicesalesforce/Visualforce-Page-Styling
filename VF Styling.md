# Salesforce Style

<apex:page standardController="Account" tabStyle="Account">
    <!-- To display the record detail Page-->
    <apex:detail />
    <!-- With Related List -->
     <apex:detail relatedList="true"/> 
    <!-- Wihtout Related List -->
     <apex:detail relatedList="false"/> 

    <!-- Wihtout Specfic Related List -->
    <apex:relatedList list="Contacts"/>
    
    
     <!-- To Identify the Relationship use the workbench  -->
    <!-- https://workbench.developerforce.com-->
  
</apex:page>
