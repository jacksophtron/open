# Using Private KYC Verifiable Credentials to Allow Small Deposits
With the adoption of Bitcoin many services are exploring user experiences that require users to have a small
amount of bitcoin. 
While things like the lightning network make payments instant the effort required to on-board a user
to obtain their own self custody lightning wallet is still high.
And since many of these user experiences do not require users to have more than $10 or $20 in their wallet
any effort to obtain higher security seems like waisted effort.

In those cases a custodial bitcoin wallet is an attractive option. For example one social media site
is using [Message Bonds](https://github.com/jacksophtron/published/blob/main/private-kyc.md) to prevent spam. 
Message Bonds are tiny amounts of bitcoin (less than a dime usually)
that are attached to a message that is posted. If the moderators remove the message because it is spam
or it violates the terms of service than that tiny amount of bitcoin is forfeit.

This is a very interesting solution and does not require any user have a significant amount of bitcoin 
deposited into their account so the security concerns are very limited. And when it comes to performance
and ease of use nothing beats a custodial bitcoin wallet.

Unfortunately custodial bitcoin wallets come with a lot of hassle for both the user and the service that is hosting them.
The service needs to comply with KYC/AML laws and this often means that the user needs to provide
identity verification and go through the same onerous on boarding process that is required when opening a brokerage account.

There is some hope that regulators will see a $10 account that stores bitcoin to prevent spam on message boards differently
from a brokerage account, but if users are able to write a script to open thousands of accounts the argument that each account only stores $10
might not be very convincing.

## Private KYC Limits the Number of Accounts 
This is where the Private KYC Verifiable Credential can come in handy. In less than 30 seconds
users can obtain and present a Verifiable Credential
that proves that they are a human that posses a bank or utility account,
but shares nothing about that account and shares nothing else about the person (not even their first name).

This eliminates the concern that thousands of accounts could be created and used for any improper financial activity
without harming user privacy. If someone wanted to create thousands of accounts
they would need to have access to thousands of bank accounts or utility accounts
and these type of accounts are so much hassle and effort to create that the work involved for each
is too significant if the only payoff is the ability to store a few dollars in a custodial bitcoin service. 


## Streamline On Boarding
Combining Private KYC Verifiable Credentials with Message Bonds also means that you can on board new users 
without requiring them to first purchase a small amount of bitcoin (a significant on boarding hassle in itself)
in order to try a social media site that the user isn't already convinced is worth the effort.

Fortunately if you know that a user is very likely a unique human you can give them a small bitcoin credit that can only
be used on the site (you don't need to allow it to be withdrawn)
so that users can immediately being posting content.
And since the new user knows that they can't create a new account with the same Verifiable Credential
once their initial credit is used up they will have a tendency to experiment with the social media account
without abusing it.
If they do post spam their initial credit it will run out quickly and they will need fund their account
with real bitcoin.

## Conclusion
Combining Private KYC Verifiable Credentials with Message Bonds eliminates concerns about money laundering
and regulatory compliance for small custodial bitcoin wallets and creates a streamlined on boarding process
that is not possible with Message Bonds alone.
