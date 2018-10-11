# project-overview

The Stakeholders:

1. Special Purpose Vehicle

2. Lenders

3. Security Trustee (Our Team)

4. Contractor

5. Off takers

6. Shareholder 1

7. Shareholder 2


Our objective is to create a CorDapp to replicate the actions of the Security Trustee.  The functions of a security trustee are to act as a custodian for the following:


Loan Agreement (From the Lenders)

Security Agreements (from the SPV)  Note: - Security Structure is another term frquently used

Direct Agreements (from Off Taker and Contractor)



From the diagram on the wiki, it would appear that we are not actually ‘producing’ any documents at all, the docs/certificates above are supplied to us from other stakeholders, we simply acts as a custodian for the loan agreement, security agreements and direct agreements.

However we did agree to take on the security agreements, so we should attempt to replicate a security agreement but as a smart contract + legal prose.  That contract would be sent from the SPV to us as the security trustee.


What is a Security Trustee?

A security trustee is the entity holding the various security interests created on trust for the various creditors, such as banks or bondholders. This structure avoids granting security separately to all creditors which would be costly and impractical.


How does project finance work?

Project financing is a loan structure that relies primarily on the project's cash flow for repayment, with the project's assets, rights and interests held as secondary collateral. 


What is Limited recourse debt?

Limited recourse debt means the borrowers and shareholders of the borrower have no personal liability in the event of monetary default.  Hence the use of an SPV, if there is a default the Lender takes control of the SPV in effect.



Im still trying to get my head around the entire concept so please bear with me!

Some questions we should all think about before the next meetup:

1. What will be the scope of this project, in terms of functionality? 

2. What exactly is our "CorDapp" going to do? And how?

3. What are the REQUIRMENTS? And what are our responsibilities? (Look at industry examples)

4. Can we replicate the following contracts/agreements as smart contracts:
    -    Loan Agreement
    -    Security Agreement (Our responsibility)
    -    Direct Agreement(s)

5. How can we prevent a “double spend” scenario for these assets? E.g Trust deeds etc - Can we treat them like the IOU example here: https://docs.corda.net/tutorial-cordapp.html#creating-an-iou-via-the-endpoint



Essentially we will be recieving inputs from the SPV, Contractor and Offtakers (governement or end buyer)
These inputs will be the loan agreement, security agreement and direct agreements (2).  As the security trustee we will be responsible for securing the ownership of the entire project, a very big responisibility (in a real world scenario).

Useful links:

http://wiki.designcomputation.org/home/index.php/Project_Finance (CBC WIKI - MOST MATERIAL IS ON HERE)


https://www.youtube.com/watch?v=D7nSTAhK7_g (AN INTERESTING VIDEO ABOUT TRUSTS AND HOW THEY ALLOCATE TRUST UNITS - QUITE LONG)

https://www.youtube.com/watch?v=8sKjMygDl84 (VERY GOOD VIDEO ABOUT PROJECT INFRASTRUCTURE FINANCE - A MUST WATCH BUT LONG)




http://moorishdirectory.com/wp-content/uploads/2015/06/Trustee_Handbook_1.pdf (HOW DO TRUSTS WORK?)
