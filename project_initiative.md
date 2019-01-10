# Dearwave
Dearwave is an open-source software to enable a decentralized scientific publishing and evaluating process. Dearwave uses blockchain technology as the backend infrastructure to ensure its transparency, fidelity and decentralized operation mode. 

# Blockwave
Blockwave is the project name of Dearwave’s blockchain backend framework, which enables fast development of a dearwave-like smart contract with the following building blocks.

Blockwave is developed by a joined team from [moac.io]() and [dearwave.org]().

### Objects/entities/concepts:

* Science document (SciDoc): A digital object that deliver scientific discoveries or engineering innovations. SciDoc can be digitized in various file format: including but not limited to pdf, multimedia, txt, datafile, coding snippet, script, code, meta-data, etc., and any combination of aforementioned files as well. Each SciDoc has a unique SciDoc ID to identify and traceback. Each and every SciDoc is considered as a finalized formal documentation that is in its final version and ready to be read and reviewed. So, SciDoc does not need file versioning. 

* Reviewer (also called “reader”): Everyone on the network, it can even include the author(s) of the SciDoc. 

* Endorsement: A process that reviewers can transfer credits or points to a SciDoc submitted by others based on their own judgements of the importance of the SciDoc. Endorsement power/strength are measured by numeric variables. Endorsement power is the total points/credits a review has, so it is always >=0. Endorsement strength is a number of points a review decide to transfer to a SciDoc. Endorsement strength’s value can be positive or negative.

* Node: Both reviewer and SciDoc submitters are considered as unique nodes in the network. Each node has a unique node ID to identify and traceback.

* Node ranking: A vector calculated based on overall quality of a node’s activities on the network. 

* SciDoc ranking: A vector to determine how much visibility a SciDoc deserves. It is calculated based on the endorsement points that are accumulated on the SciDoc.

### Feature requirements:

* Assign each SciDoc a unique SciDoc ID.
* Assign each node a unique node ID.
* Submit SciDoc to a chain; add to the chain; add to sub-chains.
* Randomly select reviewers for a given SciDoc with configurable selection criteria (e.g., based on a threshold of the ranking of a node).
* Append/link new SciDoc to any existing SciDoc. Retrieve depth of a given SciDoc with respect to its root SciDoc.
* Initiate an endorsement by a reviewer; reviewer choose a endorsement strength to support a given SciDoc; transition endorsement strength from a reviewer to a SciDoc; deduct absolute value of the endorsement strength from the reviewer;  append the endorsement as a SciDoc to the one being reviewed.
* Option for reviewers to choose to hide their names on specific endorsements.
* Grant points to a node by the platform.

### Email-list:
To receive release notes, community news and development updates by sending an email (with title: "blockwave is awesome") to: [wave@dearwave.org]()



