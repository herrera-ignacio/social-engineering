# SE Pyramid:

- [SE Pyramid:](#se-pyramid)
  - [Phases](#phases)
    - [1. OSINT](#1-osint)
    - [2. Pretext Development](#2-pretext-development)
    - [3. Attack Plan (3Ws)](#3-attack-plan-3ws)
    - [4. Attack Launch](#4-attack-launch)
    - [5. Reporting](#5-reporting)
  - [Example](#example)

## Phases

### 1. OSINT

_Open Source Intelligence_, is the core of every social engineering engagement. It's also the piece that should have the most time spent on it.

How will you document, save, and catalog all the information you find is a key factor.

### 2. Pretext Development

Based on all the findings from the OSINT period, you start to develop your pretexts. You see what changes or additions need to be made to ensure success. This is also when it becomes clear what props and/or tools are needed.

### 3. Attack Plan (3Ws)

You need to plan out the _three W's: what, when, and who_.

### 4. Attack Launch

It is important to be prepared but not to be so scripted that you can't be dynamic. Instead of scripting, I suggest using an outline, which gives you a path to follow but allows for artistic freedom.

### 5. Reporting

Clients pay you to understand what they can do to fix the problem. For that reason, reporting phase is the very tip of the pyramid.

## Example

In 2015, Dark Reading reported on an attack that involved this very pyramid (_CareerBuilder Attack Sends Malware-Rigged Resumes to Businesses_).

1. The attackers investigated attacking a few targets and while working through their OSINT phase, they found out that their targets used a popular site called _CareerBuilder_.
2. After the OSINT phase, the attackers started on pretext development. This led them to plan a pretext as a job seeker, who was looking to get hired at whatever role their targets were offering. They realized the tools they needed would be some maliciously encoded files and some realistic-looking resumes.
3. They started to plan the attacks, by answering some of those W questions.
4. They then launched the attacks by uploading their malicious documents _not_ to the target but to the CareerBuilder website. The companies that posted the jobs would be notified by email that there was a new applicant, and that email would contain the attacker's uploaded attachments.
5. They did not follow through with any actionable reporting phase, but there is some actionable reporting on this attack thanks to some researchers at Proofpoint.
