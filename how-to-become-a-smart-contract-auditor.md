CHMICHEL - Top Smart Contract Auditor
HOW TO BECOME A SMART CONTRACT AUDITOR
(https://cmichel.io/how-to-become-a-smart-contract-auditor/)
---
From time to time, I receive messages asking me for advice on how to get started as a smart contract security auditor. While there are already articles written about this topic, most of them are just a collection of security-related articles which they throw at beginners, overwhelming them. I’ll provide a path that I would take if I had to do it all over again. This will be ETH specific (or more general EVM-specific) as most auditing work is currently still in this ecosystem. At the end, I'll go over frequently asked questions that are related to auditing and getting your first job.

# Who made me the Expert?
Who am I (chmichel) and why should you even listen to me?
I'm currently an independent security researcher who has worked at traditional auditing firms before, so I know both sides. You don't need to listen to me but if you reached out to me, you probably have your own reasons why you think my advice is valuable. At the time of writing, I'm currently ranked #1 auditor at Code4arena, how much weight you want to give to this ranking is again up to you.

# Learn Programming
I except that you already know how to code, any language is fine. If not, learning how to code should be your first step as auditing code requires being able to read it. In my opinion, being a developer is a prerequisite, otherwise, you're spending too much time trying to make sense of the syntax and the semantics of the individual instructions. It'd be like trying to read Nietzsche while being illiterate. Become literate first. This is definitely the step that takes the most time to learn, learning the security aspects happens a lot faster.
If you have no prior programming experience, be mentally prepared that it'll take you years before your reviews will be useful. I'd start with JavaScript, it's the most beginner-friendly and versatile language. If it turns out you don't actually like being an auditor, the transition to being a frontend, backend or smart contract developer is easy. The syntax of Solidity and JavaScript are also somewhat similar.

# Learn ETH blockchain & Solidity Basics
So you know how to code now but don't know anything about Ethereum and Solidity yet. The quickest way to learn a new language is by using it in practice, by writing code in it- reading only the docs does not make the knowledge stick (and for some reason, even after all these years I still find the Solidity docs confusing and unstructured). There's no better way to combine learning Solidity with learning about ETH security than solving CTFs. 
NOTE: CTFs (Capture The Flags/ War games) are security challenges where vulnerable code is presented and you need to write a smart contract to exploit the vulnerability.
These are the three CTFs I personally solved to learn Solidity and the language:
-> Damn Vulnerable DeFi
-> Ethernaut
-> Capture The Ether
The Ethernaut and Capture The Ether challenges often overlap and some vulnerabilities only apply to old Solidity versions. You won't see them in modern code anymore; be aware of that.
NOTE: These CTFs were originally made to be run against an Ethereum tenet for which it's hard to get any ETH funds and the development experience is very cumbersome. I recommend an alternative approach of using modern testing frameworks & forking to solve these challenges, it's described in my Ethernaut Solutions posts. You can clone my GitHub repo to start with the same setup.
There are also CTFs that are a lot harder, like Paradigm's CTF. Scoring well in these shows that you know what you're doing and they are great for getting hired, especially if you're unknown. All major auditing firms reached out to me after my solutions blog post with the call-to-action at the end.