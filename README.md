# SCoDA – Simple Code Deference Agreement

This is a work-in-progress alpha version of a SCoDA, or Simple Code Deference Agreement. It is designed to provide a model for the type of legal or ‘wet’ contract that may be entered into by two parties who wish to otherwise agree that ‘code is law’ with respect to a certain arrangement between them. In this case, the ‘code’ is a smart contract deployed to Ethereum. 

The SCoDA provides that, after the parties sign the SCoDA, they will deposit a certain number of specified blockchain tokens into the specified smart contract. The results of operation of the smart contract will be binding upon and non-appealable by the parties with respect to the deposited tokens and any proceeds thereof, subject to certain (narrow) exceptions. 

The SCoDA embodies a “qualified code deference” (QDC) approach to smart contracting. As compared to competing approaches to smart contracting (such as the ‘Ricardian’ approach or the unqualified ‘code is law’ approach): 

* QDC does not try to describe or summarize a contractual arrangement the code is supposed to perform;

* QDC does not try to make the code itself a written text intended to express a legal agreement; 

* QDC does not try to make a ‘machine-readable’ version of a natural language contract; and 

* QDC does not provide that the results of operating code are binding in absolutely all cases.

Rather, QDC contemplates that the SCoDA is designed to be a legally binding contract whereby the parties agree that, EXCEPT in certain narrow circumstances, they will DEFER to (i.e., refrain from disputing in a legal proceeding) the results of operation of a smart contract. While a detailed explanation of the motivations for, and pros and cons of, the QDC approach is pending, a cursory explanation of the approach can be found here: 
https://twitter.com/lex_node/status/1028727470210437120 
and here: https://twitter.com/lex_node/status/1019819161298456577

The exceptional circumstances under which the parties are not required to defer to the smart contract are captured under the concept of a “Material Adverse Exception Event.” These circumstances are basically the blockchain equivalent of ‘force majeure’ events—e.g., a 51% attack that causes a double-spend somehow affecting the smart contract. Although, under such a narrow definition, Material Adverse Exception Events should be incredibly rare, the SCoDA provides a standstill provision and a set of negotiation and arbitration procedures designed to drive the parties toward a resolution of how to handle one if it occurs. Of course, parties in the wild may opt for an even narrower version, or a broader version, of “Material Adverse Exception Event,” depending on their particular preferences.

Additionally, like any contract, the SCoDA contains fundamental representations and warranties from the parties to the effect that they have the capacity and authority to enter into the Agreement, as well as slightly more specialized representations whereby each party represents that it is sophisticated or has been advised by someone sophisticated in reviewing code and thus has thoroughly evaluated the code of the smart contract. 

The SCoDA also binds the parties to narrow contractual covenants intended to bolster the intended code deference, such as that the parties shall not bring legal proceedings to contest the results of the smart contract (unless there is a Material Adverse Exception Event) and shall not grant any liens on or purport to sell or transfer any of the tokens held in the smart contract. 

If any of the representations and warranties or covenants of a party is breached, the non-breaching party would have the right to bring an indemnification claim against the breaching party for any damages of the non-breaching party arising from such breach. In the current version of the SCoDA, this would mean initiating a meatspace claims process culminating in an arbitration. 

It must be emphasized that this is an ALPHA release of a MODEL form. Thus: 

* it is very much a work in progress

* it likely has various glitches, bugs and imperfections; and 

* even in its final version, it will not be intended to be a contract that actually can be signed-- ‘off-the-shelf,’ as it were-- by parties who wish to do a deal. 

Among other lacunae in the contract, there is no ‘Exhibit A’ setting forth the arbitration procedures, since presumably these will vary quite a bit depending on the parties’ preferences. 

Improvements that may be added to future versions of the SCoDA include: 

* adding a hardfork-related exception to the definition of "Material Adverse Exception Event";

* general clean-up and drafting improvements;

* adding a decentralized alternative to traditional arbitration-based dispute resolution for Material Adverse Exception Events and indemnification claims;

* adding a court-litigation alternative for those who don't prefer confidential arbitration;

* adding some recitals to contextualize why parties would defer to code;

* adding blockchain-related evidentiary and signature provisions, such as a provision providing for the SCoDA to be hashed to the blockchain as part of the signature process; 

* provision-by-provision commentary from the author and/or future contributors, explaining the particular drafting choices made in the model and referring to possible alternatives 

## Contributors / Contributions Welcome

If you are an attorney, software developer, or both, your comments would be welcome. You can propose changes through GitHub or can contact me through other channels. A word version of the SCoDA can also be made available upon request for those who do not wish to comment through GitHub. 

Many thanks to these contributors: 
* Ross Campbell (https://about.me/r_ross_campbell)
* Matthew Cantor (https://www.fenwick.com/professionals/Pages/matthewcantor.aspx, https://twitter.com/MattCantor)

## About the Author

Gabriel Shapiro is a U.S.-based corporate law attorney at the firm DLx Law. More about him/by him may be found at the below links: 

https://about.me/gabriel_shapiro/

https://www.linkedin.com/in/gabriel-shapiro-29616651/

https://twitter.com/lex_node


## License

This project is licensed under the Creative Commons Attribution-ShareAlike 4.0 International Public License - see the [LICENSE.md](LICENSE.md) file for details

