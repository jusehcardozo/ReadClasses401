Jose Cardozo
02/06/2023

Anatomy of a Cloud Breach: How 100 Million Credit Card Numbers Were Exposed.

The US-Based major financial institute data breach two years ago, which exposed the personal data of more
than 100,000 customers, was one of the most devastating data breaches of all time. A trusted financial
services brand, has been a leader in digital transformation within the banking industry and a sophisticated
user of cloud infrastructure. Careful analysis of this breach gives helpful insight into prevention methods that
will benefit organizations storing confidential information in the cloud.
Soon after the breach was reported, unwarranted speculation spread on the internet, including suggestions
that a single product or a set of professional services could have prevented such an attack. Taking advantage
of information that has since become available, Zscaler has updated this research note with a technical
illustration of the attack and possible ways to prevent such data breaches.
On July 29, 2019, the FBI arrested Paige A. Thompson (also known by the alias “erratic”) for allegedly hacking
into Financial Institution databases and stealing the data1
. Financial Institute disclosed that the event
affected approximately 100 million individuals in the United States and approximately 6 million in Canada.
It also includes data loss of approximately 1 million Social Insurance Numbers of Canadian credit card
customers, about 140,000 Social Security numbers, and 80,000 linked bank account numbers of the credit
card customers2
.
AWS provided their assessment of the incident: “Financial Institution outlined in their public announcement,
the attack occurred due to a misconfiguration error at the application layer of a firewall installed by Financial
Institution, exacerbated by permissions set by Financial Institution that were likely broader than intended.
After gaining access through the misconfigured firewall and having broader permission to access resources,
we believe an SSRF attack was used (which is one of several ways an attacker could have potentially gotten
access to data once they got in through the misconfigured firewall).”

