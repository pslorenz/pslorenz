# Hi, I'm Steven

I work in security for the SMB and MSP space, in my opinion a segment of the market that gets sold a tool for every problem (and even some made up problems) and almost rarely creates a coherent program.

Most security guidance assumes enterprise budgets, dedicated SOC teams, and mature governance. The organizations I work with typically don't have most of those. The projects in this profile are my attempt to translate good security practice into something that's actually achievable for small organizations, and also for the MSPs trying to deliver real outcomes for them without burning out.

The work is opinionated on purpose. SMB security doesn't fail because the frameworks are wrong, it fails because the frameworks are sized for someone else, and nobody bothers to right-size them.

---

## What's here

The repos collectively form a reference program for SMB and MSP security, organized roughly by what part of a program they support:

**Design - how the program is structured**
- [smb-security-reference-architecture](https://github.com/pslorenz/smb-security-reference-architecture) - A reference architecture for SMB security programs. The thing I wish existed when I started.

**Govern - the policies and controls that anchor the program**
- [Security-Policy-Templates](https://github.com/pslorenz/security-policy-templates)- A right-sized set of security policies for SMBs. Plain language, opinionated defaults, mapped to CIS. Designed to be adopted, not filed away for checkmarks.
- [Operationalizing-CIS-for-the-SMB-and-MSP](https://github.com/pslorenz/Operationalizing-CIS-for-the-SMB-and-MSP) - Course material on applying CIS Controls and device hardening in an SMB context, without pretending you have an enterprise team to do it. (Currently being re-written)

**Implement  the hands-on hardening work**
- [Windows-Endpoint-Hardening-Toolkit](https://github.com/pslorenz/Windows-Endpoint-Hardening-Toolkit) - PowerShell scripts for hardening Windows workstations.
- [AD-Hardening-Playbook](https://github.com/pslorenz/AD-Hardening-Playbook) - Common pentest findings and misconfigurations, with the remediations I've used over the years to actually fix them.

**Train - because tools don't think for you**
- [NotebookLM-for-tech-pros](https://github.com/pslorenz/NotebookLM-for-tech-pros) - A starter guide for using NotebookLM to learn faster, with a little Claude for guided self-checks.

---

## Coming soon

Active work, in roughly the order it'll land:


- **Hardening Essentials Tool** - A simpler, higher-level entry point to the hardening work for operators who need the 80/20 version fast.
- **AD Security Assessment Toolkit** - Pragmatic Active Directory assessment built for MSP workflows, with output a tech can actually hand to a customer.
- **M365 Security Assessment Toolkit** - Same idea, for Microsoft 365 environments. Sized for SMB realities, not federal compliance regimes.

---

## A note on philosophy

A lot of security writing treats the field as a closed set of properties to preserve and a checklist of controls to deploy. Real security work, especially in the SMB and MSP space, is messier than that. It's about understanding what an organization actually does, who would actually attack it, and what's actually achievable with the people and budget on hand.

The work here tries to reflect that. It's not the most comprehensive reference, and it's not trying to be. It's trying to be the *right* reference for organizations that have been left out of the conversation.

---

## Contact

GitHub Issues on any of these repos work. I'm happy to discuss, take suggestions, or hear what's missing.

---

## Support

This work is free because I believe the SMB security space needs better support, but if something here saved you time on a client engagement or your own environment, you can buy me a coffee:

[☕ buymeacoffee.com/pslorenz](https://buymeacoffee.com/pslorenz)

