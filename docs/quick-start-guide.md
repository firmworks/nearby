# Quick Start

### Activate 'Data Integration Rules'

- From Setup go to Data Integration Rules
- Enable the following
    - Geocodes for Account Billing Address
    - Geocodes for Account Shipping Address
    - Geocodes for Contact Mailing Address
    - Geocodes for Lead Address

![Data Integration Rules](/docs/images/data_integration_rules.png)

### Adding Components to a Lightning Page

NearBy has multiple components that can be used to facilitate showing users what they need to see.

#### Entity Locator 

![Entity Locator Component](/docs/images/qsg-entity-locator-image.png)

This component has all the other components in one; Nearby Search, Nearby List, Nearby Map. It is the best component to use when getting started. Just drop it and go.

For more information on then individual pieces please see below.

#### Nearby Search Component

![Entity Locator Component](/docs/images/qsg-nearby-search.png)

This component will let you reference various COnfigurations you have set up to search for addresses with in the chosen location.

**I am looking for** -  Her eyou will choose a configuration build by an admin to set the addresses you want to find.

**Filtered to** - This will allow you to reference filters that are part of that configuration.

**With in** -  Set a number and a distance unit for your search radius.

**Of** -  Enter an Address or use your current location. Note here if you are using the out of box US Census Geo Code data the address will need to be a full proper address, Iit cannot be address parts.

i.e. *111 N. Green St Wiltlen, CA 81919*. not *111 Green Street*

**Search** - This Button will initiate your search based on the above criteria. 

#### Nearby List

![Entity Locator Component](/docs/images/qsg-nearby-list.png)

#### Nearby Map

![Entity Locator Component](/docs/images/qsg-nearby-map.png)


#### Geo Configurator

![Entity Locator Component](/docs/images/qsg-geo-configurator.png)
