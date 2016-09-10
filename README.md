# TrustMeNot (subject to change)

Version 1: Prototype
 - Enter a domain name/ provide an excel sheet(for multiple domains)  -> Make an API call to URLVoid and VirusTotal to check for reputation. 
 - Parse the response and filter required elements. (e.g. 2/50 sources identify this as malicious)
 - Display results/ Update the excel sheet.  

Version 1.1: Efficiency 
 - Check if the input fits the domain name format (regex).
 - Add one more column to the excel sheet displaying net results.
  - Compare the sources from both the websites.
  - Filter unique sources and display the efficient results. 
 - If domain not analyzed/ info not available, make a html request and parse the response. 
  
Version 1.2: Scalability
 - Filter domain names from different type of documents. (e.g. word, pdf) 
 - Copy those domains to an excel sheet and check reputation.

