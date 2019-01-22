# [Guide to Attribute Based Access Control (ABAC) Definition and Considerations](https://github.com/danphilpott/fismapedia-files) (NIST SP 800-162)

> ABAC is a logical access control model that is distinguishable because it controls access to objects by evaluating rules against the attributes of entities (subject and object), operations, and the environment relevant to a request. ABAC systems are capable of enforcing both Discretionary Access Control (DAC) and Mandatory Access Control (MAC) concepts. ABAC enables precise access control, which allows for a higher number of discrete inputs into an access control decision, providing a bigger set of possible combinations of those variables to reflect a larger and more definitive set of possible rules to express policies. 

### Definitions
Object/Resource: entity to be protected from unauth use
Subject/Requestor: the entity request to perform action on the object. Generally the *user*
Non-person entity/NPE: progromatic/application requestor. Essentially a *service acount*
Attributes: characteristics of the subject. (name, DOB, training record, job function) 
Privledges: authorized behavior of a subject. Definted by an authority and embodied in policy.
Persona: cross-classification of a subject and job function. Ie Person A is working as a gate guard during the weekend. So the persona is person-A + gate-guard. 
Authentication: the act of verifing that the subject has been authorized to use the presented identifier by a trusted IP org. 
Access control/athorization: the decision to permit or deny a subject access to objects
Environment conditions: Dynamic factors that can be used to influence an access decision. Essentially temporal/dynamic attributes.
Policy/rules/relationships: govern allowable behavior within organization. 
Object attributes/resources attributes: Subject attributes but for objects. 

Access Control Mechanism/ACM: The logical component that serves to recieve the access request from the subject, to ddecide and to enforce the access decision.  
Policy Devision Point/PDP: renders the ACM decision
Policy Enforcement Point/PEP: enforces the decision



