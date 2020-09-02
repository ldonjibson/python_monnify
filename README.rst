=====
Python Monnify
=====

This library makes it easy to connect with Monnify API (To create reserve accounts)

It will be updated and maintained as needed

Detailed documentation is in the "docs" directory.

Quick start
-----------
1. pip install requests python_monnify

2. To use from monnify import Monnify

3. method includes 
	> generateToken: Method generate Token to be used in the subsequent calls
	
	> createReserveAccount: Creates reserve accounts and returns value from monnify's API
	
	> createHashFromWebhook: Generate hash as described on monnify's documentation to compare with transactionsHash
4. #=========== USAGE ==========
	x = Monnify("apiKey", "clientSecretKey")
	
	print(x.generateToken())
	
	print(x.createReserveAccount())