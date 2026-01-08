# Shostack's Four Question Frame for Threat Modeling 


1. **What are we working on?**
2. **What can go wrong?**
3. **What are we going to do about it?**
4. **Did we do a good job?**

These questions are designed to help people build better systems. They work less well for end-users of technology. There's a [60 second video](https://youtu.be/Yt0PhyEdZXU) that introduces the questions. 

The questions have evolved since they were listed in *Threat Modeling Designing for Security*. The changes include:
* We has replaced you, to be inclusive and collaborative
* "are" has replaced "should" in question 3, to be more focused on action
* Simplified the wording.
* I'll regularly ask "did we do a good enough job?" The goal is not to do a good job at threat modeling, but to drive improvement to a system.
* "Working on" has replaced "building."

# In the real world

The Four Question Framework is widely adopted. Examples include:

* [How Google Does it: Threat modeling, from basics to AI](https://cloud.google.com/transform/how-google-does-it-threat-modeling-from-basics-to-ai)
* [Threat modeling your generative AI workload to evaluate security risk](https://aws.amazon.com/blogs/security/threat-modeling-your-generative-ai-workload-to-evaluate-security-risk/) (AWS Security blog)
* [CMS Threat Modeling Handbook](https://security.cms.gov/learn/cms-threat-modeling-handbook) from the US Government Centers for Medicare and Medicaid Services
* [The Threat Modeling Manifesto](https://threatmodelingmanifesto.org)


## Nuances
People will sometimes phrase the first question "what are we _building_" rather than _working on_. The "building" frame draws people towards a waterfall approach with the attendant problems.

In the Threat Modeling Manifesto, the team had a preference for adding the word "enough" to the 4th question: did we do a good *enough* job? I appreciate the lessened pressure, and miss the aspiration, and so keep the terse form here.

The logic behind the questions as they now stand is laid out in a 2024 whitepaper, "Understanding the Four Question Framework for Threat Modeling" at [shostack.org/whitepapers/](https://shostack.org/whitepapers)

### Legalese, citating.

I'm told some lawyers have been concerned about quoting a complete thing, and asserted that it pushes at the limits of fair use to use all 23 of these words as a unit. If you need a license, please treat it as CC-BY. Please call it "Shostack's Four Question Frame for Threat Modeling," or "Shostack's Four Question Framework." 

If you want the earliest form that's appropriate for a computer science citation, *Threat Modeling: Designing for Security*. 
MLA formatted cite is: Shostack, Adam. *Threat Modeling: Designing For Security*. John Wiley & Sons, 2014.

If you want to refer to the current form, the whitepaper is best.



