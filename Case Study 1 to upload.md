#Case Study of a Fintech company – Prosper Marketplace

Prosper was the first peer to peer lending business founded in 2005 by Chris Larsen and John Witchel.
It was founded as an unsecured loan service provider to individuals that traditional banks would ignore. Banks discouraged providing small loans less than $35,000 because it was cost prohibitive both in personnel required to assess the borrower and the proceeds (interest) that could be paid by the borrower. It measures its progress internally based on the volume of loans issued and the default rate of those loans.
Loans were originally used to consolidate credit card debt with a lower interest rate into fixed payments spread over 3 or 5 years. The company has since expanded both the kind of loans it provides and pool of investors. Today loans can be sought to tap home equity, make home improvements, or more specialized loans like financing elective surgeries. Initially investors were individuals but now encompasses institutional clients from hedge funds, family offices to pension funds. Today it’s investors are primarily institutional clients. 
Prosper uses several applications to compose its enterprise:
Application and Data: NGINX, Cloudfare, AngularjS, Ruby, Amazon CloudFront, Rails
Utilities: Google Analytics, Mandrill, Optimizely
Devops: New Relic, TrackJs
Business Tools: Zendesk
Its primary competitor was initially Lending Club but today includes SoFi, Avant, and Upstart. There are other smaller competitors, but they don’t generate as much loan volume or concentrate in other market segments. The leader in the field currently by loan origination is Lending Club. This is the metric that these companies are competing with each other the most. Since payments are passed onto investors the platforms only make money by collecting fees from new loans so issuing new loans is the primary driver. However in order to retain investors they need to ensure an allowable default rate. This loan screening is the secret sauce so to speak of these companies. It differentiates itself by charging slightly lower origination fees than Lending Club, slightly higher APR per borrower category and allowing a higher debt-to-income ratio (50%).

#Recommendations:
Prosper initially provided loans without strict standards and the result was many defaults. It subsequently relaunched itself and now excludes sub prime borrowers (FICO < 640). 
Given the potential for recessions and general longevity I recommend not relaxing lending standards. This should result in lower default rates that would exceed the benefit of a higher interest rate from a less qualified borrower. A slow and steady approach with more guaranteed returns would be better than a higher risk strategy. As opposed to LC they are not a public company so they have more flexibility in making changes to the platform.


#Resources:
https://digital.hbs.edu/platform-rctom/submission/prosper-marketplace-21st-century-e-peer-to-peer-and-institutional-e-lending/
https://www.ft.com/content/d9a696d8-ddec-11e4-8d14-00144feab7de
https://www.businesswire.com/news/home/20170525005863/en/Prosper-Closes-495-Million-Securitization-Transaction
https://en.wikipedia.org/wiki/Comparison_of_crowdfunding_services
https://stackshare.io/prosper-marketplace/prosper-marketplace
https://www.prosper.com/blog/
https://help.prosper.com/hc/en-us/articles/210013963-What-are-the-minimum-criteria-to-borrow-on-Prosper-
https://www.forbes.com/advisor/personal-loans/lendingclub-vs-prosper-personal-loans/
