# Collect_data_in_compliance_with_RGPD_standards

<h1>I. Context</h1>

I did a consulting mission like BI Analyst in **Dev'Immediat**, an automobile insurance broker company.

This firm, whose job is to do business development and margin on contracts sells, needs help to process their requests of automobile insurance.

In fact, their data protection had some troubles. Following a customer complaint, they risked a sanction from the CNIL (the qualified autority in personnal data protection).

So, they needed to put themselves in compliance with RGPD standards.

<h1>II. Methodology</h1>
  <h2>1. Frame definition</h2>
    <li>Get informed about RGPD compiance rules</li>
    <li>Identify data protection rules needed to apply depending of their data</li>
    <li>Identify the main contact of the organisation to contact about data confidentiality (DPO = Data Protection Officer)</li>
    <li>To connect to their Customer Relationship Management (CRM) database and examine the data contained with SQLite</li>
    <li>Write at least 5 recommendations on management rules to implement on the CRM data to comply with RGPD standards</li>

  <h2>2. Data recovery</h2>
    <li>Data extraction using SQL, for current year and for customers who had a fully file</li>
    <li>Select only strictly required data</li>
    
  <h2>3. Dataset cleaning</h2>
    <li>Preparing the dataset so that it is compatible with the main principles of RGPD. Using Power Query to adapt the dataset so that we         cannot cross the information to go back to the user ( for example, replace annual income by an interval, replace number of       children by a binary value to show their presence or not, replace customer ID by a random index</li>
    <li>Preparing the dataset to respect the rules about pricing data</li>
    <li>To note the recommendations to be made for the principles which would not be immediately applicable to the data</li>

  <h2>4. Documentation of data processing and writing recommendations for the management department</h2>
    <li>Demonstrate in a report (template provided by the DPO) the respect of quality process applied and recommended in the collect and the preparation of data</li>

  <h2>5. Presentation to the general manager</h2>
    <li>Make sure the general manager be familiar with technical terms</li>
    <li>Limit and explain the specific vocabulary used</li>
    <li>Use a reassuring tone</li>
