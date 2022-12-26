

## Web5 - A non-technical overview


[Web5](https://developer.tbd.website/blog/what-is-web5) is instead an obvious evolution of the technology and standards that have been steadily improving
and are now reaching a milestone worth a label.

The recent establishment of the Decentralized Identity (DID) and Verifiable Credentials (VC) is the culmination of decades of work that can be traced back to the earliest days of encryption on the 
web. This article is an attempt to provide a high level and non-technical overview of web5 and it's implications and to demonstrate that
early adopters of web5 will enjoy rewards similar to early adopters of the Internet. 
And late adopters of web5 will struggle to remain competitive until they adapt or are replaced. 

### Identity
Identity is far more than your photograph and name on a driver's license. It is also your bank statement, your utility bill, your social media followers and everything else
that makes you, you, on the Internet. Web5 gives users control over this data so that they are not "unpersoned" when they decide to delete their account on a website.
This works by allowing corporations, governments and applications to issue digital documents (called Verifiable Credentials) that can't be forged and are 
stored in multiple places so they are not lost.

### Data Storage
To make it easier for users to store their own data safely web5 relies on Decentralized Web Nodes (DWNs). DWNs intelligently replicate data across multiple
service providers and user devices such as laptops and phones. This model is more like a Dropbox than Google Docs. With Dropbox
your data is usually in two places (your laptop and the Dropbox servers) so that if you lose your laptop or you stop paying for Dropbox you haven't lost
access to your most important documents. Google Docs on the other hand is usually used through your browser and the data is not stored on your laptop, but only in
Google's servers. One advantage to the Google Docs approach is that you never run out of space on your laptop, but with more intelligent replication
algorithms we get the best of both worlds. If you have space on your laptop it can be used for redundancy, but you also have multiple servers 
keeping copies. In web5 multiple companies will host a copy of your data and what you use most often on your phone and laptop is also stored on those devices. 

Note: I have oversimplified Dropbox and Google Docs to illustrate the point. In reality both services have been steadily evolving to look more like Web5 data storage, 
but so far it has been with closed source and proprietary methods that don't interoperate together.

### Untangle Data and Applications 
With Web5 your data is owned and controlled by you, but you still need software applications to do anything with that data. Again the Dropbox and Google Docs analogy is helpful.
Google Docs is both a way to store data on the Google servers and a suite of applications, such as a word processor and spreadsheet application, bundled together into a seamless
user experience. Dropbox on the other hand stores your data, but if you want to edit a Word document you access that data (the file with a .docx extension) using Microsoft Word
that you have installed on your laptop. So in the Dropbox model even if your license for Word expires you still have access to the data (you can open it with another 
application like (Open Office), but if you lose access to Google Docs you have lost access to your data.

With web5 your data and applications separate so that you never loose access, but with Progressive Web Applications and intelligent replication of your data 
you can start editing a document in your browser that is immediately updated on a server shared with others, switch to editing that document on your laptop when your
internet access went offline, and have those changes automatically pushed back up to the server the moment your connection is re-established
without noticing or caring that your connection went down.

### Privacy
Since the early 90s it was clear that encryption is the key to allowing users to enjoy a similar degree of privacy and security on the Internet as they have 
always had in real life. And this is not just important for people to feel safe communicating their feelings to their loved ones, but also for 
more utilitarian matters such as keeping their bank account balance private. Unfortunately until the recent adoption of bitcoin and other digital tokens
encryption had a major hole - users could not take possession of their own encryption keys reliably. This meant that encryption was limited to situations
where application providers could hold your keys and users would be expected to remember a password. 

Since the fundamental concept of encryption is that only you can see the data because only you have the private keys introducing a third party eliminated most of 
the security and privacy value of encryption. And this has been the primary reason normal people remain more comfortable with the confidentiality of paperwork in a safe than
data stored on their laptop. This gaping hole in the Internet, that has significantly stunted it's growth and the value of applications build upon it, is fixed with web5.

Now normal Internet users are storing significant portions of their wealth by holding "private keys" that give them access to their bitcoin
by simply writing down 24 words or by keeping a special purpose USB device in their safe. Block (Square) will soon be releasing a hardware device
that looks like a small rock that will make storing private keys even easier. 

Web5 takes advantage of this fundamental shift in how users protect private data so that, for the first time in history, normal people will be able to safely store their
critical financial records with more confidence than physical copies.

### Informed Consent
Informed Consent is the idea that you must get someones permission and that they must understand what they are signing up for. 
This is both an ethical standard and a legal obligation that comes up often in the Internet. 
A classic example of informed consent is when your doctor explains the risks involved with a surgery and ensures that you understand them.
This is particularly challenging for financial applications that use your data to earn money in ways that are not obvious.
For example the SEC recently charged Robinhood, [and they agreed to pay 65 million dollars in fines](https://www.sec.gov/news/press-release/2020-321)
for failing to explain to customers how their service used "payment for order flow."

As with many long standing technical challenges on the Internet the real problem is not a technical one, but one of conflicts of interest.
When a financial application is being optimized the streamlining of the on boarding process and making the user feel safe is at the very top of the list of goals for developers.
They don't intentionally deceive users, but with those incentives it is not surprising that the current version of informed consent is a tiny checkbox
and a link to a 20 paged legal document that no one can be expected to read or understand.

To solve this web5 uses open source clients for high security applications such as financial wallets. The TBDex network being developed by Block (Square) 
for example uses a wallet that is open source to explain financial services and their terms and obtain consent from users.
This segregation eliminates the conflict of interest so that financial services companies can focus on creating things users want to use
and the open source community can focus on creating a trusted user agent that educates users through well designed interfaces.

### Data Integrity
Today when you download your bank statement or take a photo of your utility bill it is trivial to use Photoshop to change the content
yet these are commonly used when applying for loans to prove identity and income. And this helps explain why the amount of financial fraud on the Internet is so high. 
The new Verifiable Credentials web standard fixes this because they are digitally signed by the data provider and can't be modified
without invalidating that signature.	

Users that obtain a drivers license or bank statement from a Web5 enabled company or government agency can use the data multiple times 
and anyone that receives this data can verify that it is accurate even if the data provider is offline or goes out of business.

To put this in perspective, before web5, there was no standard that allowed people to obtain their data without also obtaining the ability to forge it 
into something else. In some ways it is more astonishing the web has been successful at all without these standards and gives us a glimpse
into the exploding of value we should expect to see with these improvements. 

### Data Interoperability
Verifiable Credentials also encourage the establishment of standardized data formats and this is critical to have any meaningful ownership of your data.
For example imagine if your phone camera took pictures in a proprietary data format instead of .png or .jpg and you could only view your photos
using an application created by the company that makes your phone. The value to you of photos taken on that phone would be significantly less because you would 
feel less like you "own" those photos and more like the company that makes your phone owns them.

Fortunately the steady trend on the Internet has been to establish data formats for files of all types so that many applications can view the data.
Web5 accelerates this with Verifiable Credentials as a standard for all data that requires digital signatures and because it
assumes users will take possession of all of their data.

### Open Source
One of the lessons learned over the past decades is that for any high security task the code performing the task must be open source.
This is because it allows everyone to find flaws and earn credit for helping get them fixed.
It also allows everyone to identify and malicious changes that are made to the code from hackers or disgruntled employees before it is 
included in a release. In the 80s closed source encryption algorithms were common. Today none exist and the idea of a close source
cryptocurrency wallet would impossible to get off the ground.

Web5 takes this lesson and applies it to things like financial services so that users can delegate tasks, such as "get me an auto loan",
or "sell my bitcoin", or "find me a mortgage lender with an excellent privacy policy", to software that is trustworthy 
to execute tasks based solely on the users preferences.

### Ethical Data and AI
Many Internet businesses rely on access to large amounts of user data. AI can be thought of as nothing more than algorithms 
that can only work with very large amounts of data. But without informed consent from users (something that is not really possible
without an open source user agent) all of these businesses are facing ethical and legal liabilities.

Web5 fixes this by placing data in the physical possession of users and using open source wallets to obtain informed consent before data is shared
and revoke that consent when it is no longer in the users best interest. The amount of data that is provided without informed consent will drop dramatically,
but the amount of user data that is available with the ethical requirement of informed consent will explode in availability.

### Resiliency
Originally the Internet was designed to allow nationwide communication throughout a nuclear attack, 
but today if you don't have a good cell phone connection you might not be able to view a map.
Web5 fixes this with more intelligent data caching and storage. Progressive Web Applications (a pillar of web5) look and behave like
any other web app except they primarily use local data on the device. When this data is replicated for redundancy and sharing
your Internet connection can be down for hours without impacting your user experience.

### Performance
While Internet bandwidth has increased dramatically the speed of light remains a barrier we don't expect to break anytime soon.
This means that no matter how many fiber optic cables we run, or low earth orbit satellites we enable, accessing a website on
the other side of the country or the other side of the planet will seem sluggish. So far this has been addressed with the hacky solution 
of large web applications establishing servers in every region of the planet and replicating data in the background.
While this works (with incredible expense and effort) it is not something anyone would have designed as a native part of the web and is a design band aid at best.

With web5 data is replicated all the way to the users device so that in most cases applications have the latency of centimeters instead
of mega meters.

### Conclusion
Web5 is a natural progression of web technologies, the result of brand new Internet standards that have been in development for many years and changes in user
behaviour and capabilities created by bitcoin. Web5 will result in seismic changes that may disrupt and make
as many companies as the Internet itself and all of these changes empower users and will result in a more capable and trustworthy web.

Each of the technologies involved in web5 are obviously useful and obviously sound technological improvements
in isolation, but combined create a significant step improvement for user experience, privacy, security, compliance and the overall trustworthiness and 
fun of using the web. 

