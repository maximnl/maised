MAISED configuration prescribes how any data is imported into the time serie format. MAISED uses MAIS SQL engine to process the data. For definitions and technical details of import please check [MAIS configuration](https://github.com/maximnl/mais/blob/main/docs/configuration.md). Here we will describe grafical part of configuration.

## Dimensions
### Activity 
Activity is a dimension that gives a business name (reporting name) to one or more time series. 

Activity dimension describes time series with extra attributes. Attributes have generic meaning such that business users can agree what is the exact meaning and values of the attributes. Activity attributes can be used to find activities, slice/dice time series data etc. Activities can be compared with accounts. 

<img width="925" alt="image" src="https://user-images.githubusercontent.com/33482502/164970878-4b212960-a57c-42b3-87b5-a482b6a223a6.png">


Activity name - reporting name of the activity
Activity code - a short name version or code to be used to filter or pull data
Activity set  - activities are organized in collections of similar activities
Template - numeric fields description 
Sort order - processing order or order on charts


Activity metafields
Generic fields can be used to search framework but also to enable slicing and grouping activities in the dashboards. These fields are free text fields which benefit from a consistent naming within the organization.

# Forecast
Forecast describes versioning of numeric data. 

 
