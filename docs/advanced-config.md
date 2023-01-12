[Back To Home](index.md)

# Advanced Configuration

### Obtaining a Google API Key

[Getting Started with Google Maps Platform](https://developers.google.com/maps/gmp-get-started)

[Get Google Maps API Key](https://developers.google.com/maps/documentation/geocoding/get-api-key)

#### Using Google API Key

Paste API key into the Google box in the Nearby Configuration screen
![Google API Key](/docs/images/google_api_key.png)

### Setting up Nearrby Custom Configurations

Nearby Custom Configurations are made up of 4 different parts.

**Nearby Search Configuration**

![Nearby Search Config](/docs/images/adv-config-ncc-nsc.png)

In this section you will need to do a few things to get the configuration started.

Salesforce Object Name: This is the first section you will need to set. This wills et the context for the rest of the configuration.

Options Display Name: This is the name that will show up in the Nearby Search Component. 

Latitude and Longitude Fields: In this section you will need to set three items. These will allow Nearby to know which of hte objects Address fields you want to use for to Lat and Long. 

- Geolocation Field: The Compound Address field or a Geolocation field that contains Lat and Long fields
- Geolocation Field Latitude API Name: The API name of the Address field that contains the Latitude.
- Geolocation Field Longitude API Name: The API name of the Address field that contains the Longitude.

Sort Order: The order you want to show this Configuration in the Nearby Search component if there are more than one configurations.

Record Filters: This allows you to create one or more filters you can reference when this Configuration is chosen in the Nearby Search component. It is made up of two parts. 

- Filter Label: What you want to call the filter and what will show up in the filter selection UI in the Nearby Search component.
- Filter Where Clause: Here you will need to put your filter criteria. It will be in the form of a SOQL Where clause, with out the Where in front. For more on SOQL please see this Salesforce Article.

https://developer.salesforce.com/docs/atlas.en-us.soql_sosl.meta/soql_sosl/sforce_api_calls_soql_select_conditionexpression.htm



### Using Custom Apex to Link to a Geocode Provider