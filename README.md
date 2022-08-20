# Power BI - Org Data UK Local Authorities
> This work is based on the data published and maintained by the [ONS](https://geoportal.statistics.gov.uk/) and public data sources published by [UK government departments](https://www.data.gov.uk/)
## About
This list of Local Authorities has being designed for use with Power BI to be published as a Organisational Data table as explained in [this blog post](https://drdataanalysis.github.io/blog/Organisational-Data/). 

The list is adapted from the Local Authority data provided by the ONS and incorporates historic changes to local authority districts and the historic codes used to identify local authories (from the early 2010's to date).

The intention is that this data set is robust enough to be able to match historic and current codes and Local Authority names to their current allocations within Excel after publishing via Power BI as a Organisational Data Set.

It should be noted that this data set is not particularly good as a Local Authority index within Power BI and without adaptation using Power Query would not be able to do the kind of matching that is possible in Excel within Power BI. There are trade offs and considerations which are detailed in the previously mentioned [blog post](https://drdataanalysis.github.io/blog/Organisational-Data/) that are good to know when considering other data sources that you may want to make available as organisational data in excel.
## Methodology
The key methodological consideration with this data set is that it is a reflection of the current makeup of Local Authority districts based on historical changes. This means that when Local Authorities have [merged over recent years](https://en.wikipedia.org/wiki/2019%E2%80%932023_structural_changes_to_local_government_in_England) the former local authority codes and names are included as data to match against for the current local authority.

Using North Northamptonshire as an example if you have a data set that is from before April 2021 the local authorites of Corby, East Northamptonshire, Ketering and Wellingborough will be listed independently and using this list as organisational data in excel would all be matched to North Northamptonshire as the Local Authority (either matched on historic codes or name). Your list would therefore likely list 3 local authories as "North Northamptonshire" so any data would need to be aggregated appropriately to provide the estimated figures for this new local authority based on the historic figures for the previous local authorites. This does provide oportunities for inaccuracies based on rounding and other factors that could affect the precision of estimations so please keep this in mind when using or promoting the use of this as organisational data.
## Future Changes and Contributing to this Project
I intend to keep this file up to data with upcoming changes to local authority districts and will add any further codes or names that I come across that will improve matches.

Please also feel free to contribute by submitting pull requests with proposed changes or by creating issues for any bugs or feature requests.
