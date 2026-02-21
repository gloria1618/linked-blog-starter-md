PCI - Pmt Card Industry
DSS - Data Sec Standard

- fin institutions in PCI created PCI Sec Standards Council to enhance pmt security
- council created PCI DSS - framework for entities to apply in effort to promote data security when processing pmts
- Account data subj to PCI DSS
	- cardholder data
		- primary act # PAN, cardholder name, expiration date, service code
	- sensitive authentication data
		- full track data, card verification code, PIN
![[Pasted image 20260220165334.png]]
![[Pasted image 20260220171056.png]]
Diagram outlines typical card pmt processing networks in which these 12req must be applied
- process starts when customer makes purchase using either physical/virtual debit/credit card that is processed on 3rd party pmt processor's network (aka card network)
- transaction sent to business's bank (acquiring bank) using electronic gateway supplied by card network
- acquiring bank then submits pmt request to card network, which routes pmt from customer's bank (issuing bank) to acquiring bank
- note: seq steps of steps may vary depending on card network/pmt processor, w variation in method of authorization/transmission n encryption of data/tokenization to mask sensitive data, transaction settlement, and compliance practices 
![[Pasted image 20260220165429.png]]