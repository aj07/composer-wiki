Meeting to be held at 4pm UTC (4pm UK, 12pm ET, 9am PT) on the 16th March 2017.
The meeting is scheduled to be 1 hour long, although it may end earlier.

Dial in details:
* Phone number:
  * 0800-368-0638 (UK)
  * 215-861-6239 (US, caller paid)
  * 888-426-6840 (US, toll free)
  * For other countries see: [AT&T Global Conference Access Numbers](https://www.teleconference.att.com/servlet/glbAccess?process=1&accessCode=16199578&accessNumber=08003680638&brand=att&lang=English)
* Participant code: 16199578

Online meeting details:
* Link: https://apps.na.collabserv.com/meetings/join?id=9528-6421
* Password: composer

Current agenda for this meeting:

* Introductions - who are the Fabric Composer team?
* What's new - what work has gone in recently, a "show and tell" of what we have achieved:
  * End-to-end demo showing the work on the Composer Playground.
  * Tools demo showing Protocol Buffer to Composer conversion, as well as Atom/VSCode plugin support.
  * LoopBack and REST API improvements.
  * Hyperledger Fabric v1.0 port status.
  * Website improvements.
* Retrospective - what has been going well, or not so well, and how can we improve?
* What's coming - what are we planning to do next, review designs for future work, etc:
  * Design roadmap, review latest designs and plans.

Meeting notes:

* Introductions from the Fabric Composer team and other attendees:
  * Fabric Composer: Simon S, Mark C, Dave K, Daniel S, Ed M, Caroline C
  * Guests: Murdo A, Sumerian, Mike Z, Andrea T, Vipin B, Allan, Georg S, Mihai G, Ivan S, James W, Jeff G, Takuya A, Allan T, Jon D
* Ed led a review of latest lo-fi designs for connection profile support here:
  * Can view online here: https://xd.adobe.com/view/84d4145a-2828-4e96-b1e0-17345c44ba02
  * What are connection profiles
  * How we are enabling participants to invite other participants to their business networks
  * Connection profiles are participant-neutral (no identities in the connection profile) and can be shared around.
* Caroline demonstrated the latest playground features.
* Dave discussed the progress with supporting Hyperledger Fabric v1.0:
  * Good progress; code up and running with latest updates!
* Simon demonstrated editor plugins for Atom and VSCode.

Questions asked:

The connection profile is an identity?
You do have some kind of certificate or certificate path?
In the model window is there some kind of secret?
You are inviting someone else to be a part of your business network?
How is that bootstrapped on to the fabric? The idea is to use the playground to deploy a business network.
Their interaction with fabric how does the credential get established from composer?
Ability to connect in different profiles
If I have 1,000 people I don’t want to generate each profile separately or can this be done separately? Composer will allow you to generate ID’s without generating connection profiles.
Starting to log into the composer playground getting a data error? 
New UI looks nice... Any thoughts on generating / displaying forms based on the json instead of direct editing? (with the option to view / direct edit as well)?
Is editor support something they would like to see? Has anyone built any editor plug ins before?
I’m new to this product and new to fabric in general. For the playground if you are using an editor is there a way to package up what you have done in the editor and export it? Yes there is an import and export button.
The way the connection profiles stored? How exactly are the stored on disk. Can they be seen is it clear parts of it in the clear and parts of it.
Interested in how you make the rules for this network? Access control language discussion. 
How do you input test data into the playground?
