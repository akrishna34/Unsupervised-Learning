This is one of the classification example using unsupervised lerning.

From Coursera Course Task

Task:

Subb's Mart is a retail chain which covers a significant part of the city. It has a presence
across a varied set of locations involving different classes and segments of customers. The
merchandise presented in the store aisles and the spending capacity varies based on these
locations.
Subb's Mart is known as a retailer with good technological adaptation. Being one of the
prominent retailers in the city, Subb's Mart wants to engage with their customers in order to
provide a better experience for them. Given the advent of Machine learning is in the spree,
Subb's Mart wants to adopt better understanding their customers and provide what they need
the most and give them a good set of options for an enriching shopping experience.

Attached is the bills for a different set of customers, product masters. Try avoiding any pre-
existing boxed algorithms.

Inputs provided (Attached zip has the following datasets)
1. Articles - Master of items with name and item code for each stores
2. Stores - Store identifier and name
3. Article Hierarchy - Categorisation
4. Customers - Customer name, tel by store
5. Bills - 3 months bills by store
What do we expect? (Solve any one of the below)
A. Find the common monthly basket across customers. (Hint: is this a basket of specific items
or a basket of groups?). Monthly baskets are the one time large baskets that people tend to
buy at the start of the month(but not strictly in that period)
B. Find the items that can be sold in combo and the reason for these items to coexist in the
combo.
How should it be presented?
1. For A, Constituents on the monthly basket and for B, List of top combo items, its purpose
and reach. Both output should be served over HTTP as JSON using a web-server and boot up
should be fast, for both challenges, think of how you would present the common monthly
basket and the combo suggestions to the owner of Subb’s mart and structure JSON based on
that (no UI required).
2. The code that is used to build this. We will try validating it with different set of data which
we internally have. The code quality, levers identified are specially considered more than the
actual output.
Hint: We are not looking for one solution as there can be multiple ideal solutions that can be
picked from the list of possibilities, your approach narrow down on an ideal set of options
along with the reasoning is what will get us interested
Tech stack
Use any language that you like, you code should be buildable and runnable on Linux - no
proprietary stacks.