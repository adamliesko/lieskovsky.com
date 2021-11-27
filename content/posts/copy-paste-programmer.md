---
title: "Copy paste programmer and mediocricity"
date: 2021-11-27T11:39:33+01:00
draft: false
categories:
- Software Engineering
# weight: 1
# aliases: ["/first"]
tags: ["software engineering", "programming"]
author: "Adam Lieskovsky"
showToc: true
TocOpen: false
hidemeta: false
comments: false
description: "Is being a Stackoverflow copy and paste programmer good enough? Also, on being average and mediocre in life."
disableShare: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/adamliesko/lieskovsky.com/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---

### What prompted to write about this

Hating [@DHH][1] has become woke over the last year. While certainly justifiable due to some of his and [Basecamp's actions][2] or posts, I don’t understand the criticism around his recent blog post titled [Programmers should stop celebrating incompetence][3] in isolation. Am I the one reading it wrong? 

{{< tweet user="dhh" id="1463822670131351555" >}}

I certainly don't stand by all of David's opinions and actions, but in this case it just feels like the Internet has grabbed the post by the wrong end and is adding fire to a popular hate target. I 'd like to explain my takeaway and opinion on the topic of copy-paste programmer and generalize the thoughts more broadly about being average.

### I am 100% a copy-paste programmer myself

The [criticism on Twitter][4] goes like "I am staff/principal engineer and yet I search Google or SO for everything." "When I learned Rust, I just copied code from all over till it worked. I Had no idea and understanding of how it internally worked at all". These are actually very accomplished and successful people, writing their words in order to disprove DHH's take. It almost feels ignorant of them forgetting that they have gone through a learning process themselves and aren't the same individuals as when they started. While the metrics of # of copy-pastes per day might not have changed, the real world software development is just much more nuanced that. These individuals are hell of a lot smarter nowadays. It doesn't feel right to present it in a way that they made it so far only by copy pasting code all day long.

I share the same experience of `cmd+c` and `cmd+v` every single day. I am gonna give you a non-trivial example of how it may look like. Non-trivial in a way which highlights that this copy-paste pattern doesn’t only apply on the level of a code snippet, such as reversing a string. Thinking about this, I would probably Google for this in Java unless IntelliJ auto-complete gives me an answer, which I don't think is the case for Java (hey, Ruby 🙂). 

Before re-inventing the wheel and writing another module responsible for caching responses of a specific central service, I might search Github (internal or public) for the terms I am trying to solve "eg: {DOMAIN_SERVICE}Cache" or find discussion in Issues or PRs, to find pre-existing work. Or maybe I will look into Wiki, Quips or Slack. I might do this because of an impostor syndrome, as I assume I am not the first one to have a need for it and some other clever people have probably already figured it out and have been running it in production for months. But I also do this because in general I trust and respect the colleagues and predecessors and assume they are upholding a certain bar and they acted in their best intention. Since the code has already been vetted by a PR review process, serving requests in real environments and time it gives you a baseline confidence.

Do I just blindly take the first thing I see? No way. One needs to contextualize the found artefact to their needs, evaluate the quality and consider how well it fits to the local environment. Would I be a better engineer have I written it from the scratch? Nope. I'm sure I would just loose a day and couple of hours more in the future, in order to identify the unforeseen edge cases. I consider the ability to decide when to pickup and existing solution (or a code snippt) vs. come up with new one from scratch a valuable skill, which can be learned and improved by experience and time.

Am I proud or sad about this? I probably feel positive about it, but not overwhelmingly. It's just one of techniques of how to get the work done. Can I even call myself a programmer? I actually tend to prefer to describe myself Software Engineer by which I feel certain level of self-worthiness, rather then using words such as coder, programmer or developer. Please note, I am explicitly not adding any Junior/Senior/Staff etc. levels in here, that's just detrimental for the team dynamics and support the tech bro-ism in the field. And this is directly to the of OP's take. In my mind, calling yourself a programmer is in a way putting yourself down. I sure am a programmer, even though most of us are officially educated in the field of Software Engineering. While certainly not a requirement, it still might be true in most cases these days. We have the titles of a Software Engineer so there is no need for artifically getting rid of it.  

Also, where is the threshold of something being stupid and the other thing being clever? Why is copy-pasting lines of code considered dumb, but following software patterns or pre-existing architectural structures is acknowledged by all as intelligent and smart thing to do? We all recognize [GoF design patterns], even though the acadamic nature has had them probably reduced in practice.

### Is DHH a dick for expecting and demanding more of people?

Nowhere is DHH saying that established engineers don't copy-paste code on a daily basis or that they should steer clear of doing it. I am reading his post as that one shouldn't aim to end there. One should have drive and ambition to become a competent individual instead throwing themselves and the whole profession down in a attempt to level themselves with peer or less-experienced individuals. Downplaying team or individual achievements, experience and skill is acknowledged as humbleness and seems to be valued in the community. Fostering welcoming environment is so important to attract and retain new individuals into the profession, but in my opinion this isn't the ideal or only approach. We shouldn't end there and shouldn't take it to the extreme. What I am reading isn't portraying Software Engineers who copy paste code as incapable. Do you really all think that Google L4s (Google's terminal level) just get by by copying code forever? There is certainly more to it and it's not only politics. It's only right to admit that it takes an effort to be a productive member of the organization.

### Mediocricity in our lives

This week I am reading two different but widely accepted popular books. James' [Atomic Habits] and Richard Hamming's [The Art of Doing Science and Engineering]. While it's not the main theme or message of these books at all and people might call it cherry-picking, they both briefly agree that one shouldn't strive to become this "average" or mediocre (I don't mean or think the word mediocre in a bad way) member of society and should have higher ambitions to become the best version of themselves. It might not be in their work life. It might come out in their hobbies such as art or sport, family life or helping the local society over the weekend. I just don't believe that if you can find the spark in subset of of your life, you would be content with letting the rest rot. Now, when DHH takes the same side, do we all just hate on it, because he is a popular target?

Statement around mediocricity remind me of [Socrates' quote][5] about shaming men who don't become physically strong and capable (there are some variations on the internet of it, but the messaging is consistent). It doesn't age well given the advance of our society and productivity, but the analogy with the current world and our capabilities is still there. 

> No man has the right to be an amateur in the matter of physical training. It is a shame for a man to grow old without seeing the beauty and strength of which his body is capable.
>
> -- Socrates

In programming profession we shouldn't get satisfied just by being able to glue and patch snippet of code together. Otherwise, we might find ourselves one day being just a stellar, but soul-less version of [Github CoPilot][https://copilot.github.com/] in what has so far based on past and present been very creative domain. If you had the choice, would you rather be treated by the local health center or go to Mayo Clinic? Would you rather study at MIT or attent a university in Slovakia (n.b. Slovakia 1 University in top 500, i.e. Comenius Univeristy at ~ 400)? Would you rather work with a Software Engineer who takes pride in mastering his craft or the average Joe?

Some people tend to think of overly ambitious and motivated people as being selfish or narcisstic. It can certainly be taken to the extreme, such that it is damaging for the people around them and individual themselves. But having a healthy level of ambition for your life is essential. One of the things I have been scared in my life is becoming a mediocre person.

> I would have been the world's greatest at whatever I did. If I were a garbage man, I'd be the world's greatest garbage man! I'd pick up more garbage and faster than anyone has ever seen. To tell you the truth, I would have been the greatest at whatever I'd done!
>
> -- Muhamad Ali

### On creating welcoming environment in Software Engineers

So you probably figured out, that I am not the biggest fan of "celebrating incompetence" and downplaying the knowledge in order to facilitate a welcoming environment for new team members. In order to actually provide some value here, what are things we can do as a community or an organization to create and maintain a welcoming experience for new (or experienced folks being new to the organization or domain) Software Engineers? 

#### Invest into the onboarding process and documentation

Onboarding new team members is an extension of the already very complex and expensive hiring process. Why would you let it fail at the end of the process, or rather at the start of a follow-up process?

- Provide opinionated guidelines around learning, formal and structured trainings instead of relying on ad-hoc knowledge transfer and varying individual learning efforts, performed outside of working hours.
- Document design decisions and patterns instead of relying on tribal knowledge.
- Pair up individuals with mentors or buddies who don't have a formal evaluation power of the new organization member performance.
- Familiarize individuals with the organization Culture and help them calibrate and align towards it.

#### Integrate remote and distributed individuals into the organization

Once your team becomes distributed across multiple time zones, you can't just keep on scheduling weekly company updates for Friday evenings PST time. You need to provide fair opportunities to all individuals and allow them to be involved without additional effort on their side. The weekly company update can start in the mornings and can scheduled on Thursdays instead of Fridays. The great benefit which is only redeemable for US employees is worthless for the APAC members. Are you providing a sufficient replacement for them?

#### Allow them to experience and own failures

There are the accepted sayings about smart people being able to learn from the mistakes of others. However, it's important to also go through the process of being the one responsible for the failure in the first place early on. This doesn't mean being the person who has introduced the root cause of the failure in the first place. It means being accountable and responsible for the failed unit. We can do so by handing off the a responsibility of a deliverable to the newcomers in full, while making sure to provide sufficient mentoring, advice and oversight as needed. It's an investment and it's an mechanism of how we can make sure the individuals on both ends can grow, i.e both the student and the teacher in the realtionship.

In order for this point to contribute a welcoming experience, the culture within the organization needs to be open and blameless.

[1]: https://twitter.com/dhh
[2]: https://www.theverge.com/2021/4/27/22406673/basecamp-political-speech-policy-controversy
[3]: https://world.hey.com/dhh/programmers-should-stop-celebrating-incompetence-de1a4725
[4]: https://twitter.com/dhh/status/1463822670131351555/retweets/with_comments
[5]: https://www.goodreads.com/quotes/607547
[Atomic Habits]: https://jamesclear.com/atomic-habits
[The Art of Doing Science and Engineering]: https://press.stripe.com/the-art-of-doing-science-and-engineering
[GoF design patterns]:https://en.wikipedia.org/wiki/Design_Patterns