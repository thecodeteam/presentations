# EMC {code}
![original](https://raw.githubusercontent.com/emccode/emccode.github.io/master/images/badge.png)

---

## {code} Acronyms

- Code Open. Deploy Everywhere == **motto**
- Community Onramp for Developer Enablement == **focus**
- EMC as {code} == **success**

^ The {code} team really started with code open and deploy everywhere. what you are going to find is that we do most of our activities outside of the firewall. Good citizens with the OSS community. communication openly. its a premier thing we hold. if you communicate with us. it's likely going to be outside of the EMC strong hold. the other is deploy everywehre. this is like infrastructure as a dot next perspective. we got through a lot fo customer of the virtualiztion journey but now there are terms and notions of platform3 or cloud-native applications. but with the ability to deploy everywhere means we are going to eliminate the barrier to adoption. this is how we embrace platform3 apps. break down the walls where we can take the workloads. 

^ The community on-ramp for developemnt is how do we look at the **new** customer for EMC. We would love to hear the feedback. but if you look at he bloggers and trends, the decision makers are shifting from ops based in our typical top-down approach to people who are creating the value which is the developers. our original charter really focused on how do we enable these new stakeholders to find EMC as a good technology partner. As we develop tools and glue between OSS technology and EMC, we are providiong a central place for them to look

^ This play well into the last part. We all started off with the pancake stack. IaaS, PaaS, SaaS, but we are moving into a more software-defined approach. Soft-ware defined storage, SD networking, SD-everything. the next iteration will be infrastructure as code, storage as code, compute as code, etc. In a software-defined world we are making new abstraction and the ability to consume things in new ways. the next step, is how do I implementing those technologies inside my application platform. how do i embed those capabilities more directly into the app itself? Our success as a team is when EMC II can be consumed as code, and the central place that customers turn to integrate EMC technology into their application platforms

---

# History & Charter

- 1 year :birthday:
- We are in ETD
- Discover
- Focus and Execute on charter

^ EMC {code} was formed about a year ago and was a strategic initiative funded by Jeremey Burton and lives in the ETD landscape. It makes sense because the customers that {code} can be relevant to are those customers that are looking at things in a new way. Those customers tend to be the hyper-scale customers, or the front-runners in adopting OSS technology. And those models are more aligned with our software-defined portfolio. That's not to say we aren't relevant to core because there are contributions there to keep core relevant in the new space. But our primary focus is going to be enabling the forward-thinking customers so we can keep EMC within those platforms.

^ If we look at the first part of last year, we went through a discovery phase of figuring out where can we focus. If you look a our github page, you will see we have a ton of different projects and take a look at the tags to see how it filters. At the end of the day, you will see that we have a bunch of stuff in a bunch of different places in regards to languages, solutions, and products. We tried to cover as many bases as we could. Really an iteration of fail fast. We wanted to go through the 2nd half of the year with focus areas and that helps us measure our success. 

^ look at the github page

^ we don't plan roadmaps past a quarter or twi in OSS so we adjust focus as see fit. We chose Docker as our first decision because it has a huge amount of virality in the community. If you are looking at driving EMC thought leadership, you want to choose a technology that pulls EMC II tech, like our storage. And you will want to choose because it's already wildly popular. 

^ The other choice we have is Mesos. Mesos is a different view of the world and represents something a bit more strategic to EMC that also covers the container world as well.

^ some of the things we do everyday is that at the earliest point we can share code, we open up the repository. We don't care if its GA code and thoroughy tested. We care more about brute fucntionality and documentation. All the other things come in time and we look for community involvement for ideas and participation. 

^ Slack is our vibrant community that we are focusing. We don't spend any time in email any more. more of our mesages happen through there.

^ the other pieces are there for projects. TravisCI is our choice for automated testing and deployments. Coveralls provides us information about how we adhere to standards. Read The Docs is there for documentation to make it all polished.

^ Go to roadmap and charter

^ Our goal is to help EMC II relevant in OSS communities. We think about bringing EMC II's "area of focus", ie storage, into OSS projects. As we are trying to be good citizens in the OSS world, we don't push the EMC agenda. No open source product is successful if it's focus is on a specific product. Popular projects keep an abstract view of the world that drive an 'open capability'. So as we keep an open view, it leaves an avenue to eventually bring EMC II technologies to the table. 

^ creating thought leading applications. Such as a focus project, RackHD. It's a different and more comprehensive approach the deploying and automating bare metal server and will branch out to networking and storage. It's completely open source and EMC II and {code} is helping lead for success.

^ The next step of being open is to make it aware. Our team is responsible for writing blog posts, making youtube videos, submitting conference sessions and more to make others aware of what our team is doing.

^ Participating in community events like hack-a-thons, meetups etc. It's whatever it means to keep outside the firewall of EMC and reach further into the community. We don't do a ton of focus within the walls of EMC or even with customers.

^ Act in interest as a good citizen of the OSS world. We must lead by example and we must follow the lead of others before us. If we want to be successful and we want people inside of EMC brings through code, we have to stay highly focused on what the community likes to see vs what we see. For instance, using GitHub instead of Stash. Using TravisCI so everyone can see code coverage and build status. Act in the interest of using DevOps tools and methodologies. 

---

# Big Wins

- Becoming thought leaders within the focus communities
- 2 Press Releases
- 600+ community member
- 50 Blog posts
- 1500+ Twitter Followers
- 650 Email subscribers

^ If you follow the focus communities. You will see we have a lot Retweets from Docker and Mesos. The community managers for @Docker are retweeting us directly. our team is in the Docker weekly about every other week or so. We're being recognized by Docker and Mesos for the projects as well. We are driving open solutions for problems to solve. If you think about the competitve landscape, you don't see anything from other storage companies doing the same thing. We are easily a year ahead or more than any other storage company when it comes to building projects and driving adoption within our key focus areas

^ The press releases are really for internal marketing and news outlets. The latest press release focused on our important projects as first class citizens to the outside to say that "EMC does care about these thing". The first press release was about the mesos-module-dvdi and how Verizon is using it. 

---

# {code} 2016 Messaging
![original](https://raw.githubusercontent.com/emccode/emccode.github.io/master/images/badge.png)

---
# to {code} of EMC II, Containers != Cloud Native

- Two camps of P3
- We focus on the plumbing of cloud native infrastructure

^ You can take one approach of CNA and P3, that just means to re-design my application or i need to re-platform or make it 12-factor by re-writing it or bringing in development-firm to make it happen. It's a ton of work to get it to cloud-native. But when you talk to startups or people in OSS world, others look at containers in a different way. Virtual Machines provide the abstraction of storage, networking, and compute, but you can't provide the "deploy everywhere" approach because of hypervisor lock-in, cloud lock-in, etc. it doesn't make the VM portable at the end of the day. So if you're focused on the core aspect of infrastructure at the end of the day and not just applications, then there are better ways to do VMs and those are containers. It's really VM.next. So there's two camps. First one says I need to take my applications and re-write it to take advantage of these environments. Then the other camp says i can think of containers like VMs.next as an open source free thing. So you don't necessarily need to take you applications to the CN application architecture level, but you can embrace and use the CN infrastructure. You will see us talk about containers a lot, but not the applications that are ran inside of the containers because that's going to be more of a pivotal thing.

---
# Enterprise -- HA, Clustering, and Container Scheduling Layer

- Turn-Key solutions
- No more of "how do I run containers?"
- Google & Apple vs Everyone Else
- Enterprise features for containerize applications
- VMware.next vs re-design my app

^ If you think about the container space, Docker, Mesosphere, they are thinking about how to monetize OSS. One of the answers is obviously where we sit. We've mastered the turn-key solution or turn-key product that organization pay a dollar figure and it just works and we support it. The enterprise has expectations of what capabilities come out of the box for that solution under-the-hood. The next step is not "how i run my containers" like on Docker or Mesos, but how I use a scheduler and how I turn a container host into a cluster. The companies that build their platform to run containers like google or apple, and they've done containers the right way where its 12-factor the applications are abstracted from the infrastrucutre completely, but the enterprises that want to consume containers are going to care about the scheduling and clustering because they want something for their important workloads that aren't necessarily cloud-native, but can be containerized. So if my postgres or mysql database that is containerized lives on a host, and that host dies, we want to make sure that's restarted somewhere else. The focus we are seeing a ton in this scheduling layer because the enterprise is looking for a simple solution. It's really a VMware.next view for a new way to run infrastructure instead of re-design my app-view.

---
# The many modes of PaaS, with Persistence - an ideal PaaS Stack

- Cloud Foundry for stateless
- Mesos for persistent layers + Cloud Foundry
- Structured and Unstructured

^ The many modes of PaaS. Our focus of EMC II is to drive a federation message and that PaaS is via Cloud Foundry. The EMC {code} approach is to say "yeah, CF can be relevant for 12-factor apps and stateless apps", but there is a need to run stateful things inside of containers. There is some of that in CF roadmap, but nothing concrete is there today. THere are going to be approaches in combing a simple developer experience. THat's what PaaS is all about, just like cf push or heroku push. You will find us to start combining technologies of Mesos and Cloud Foundry. So Mesos provides a statful persistence instance while CF is for your stateless apps. A combination or a dedicated mesos stack
which includes a PaaS or persistence layer. so there will be a few different modes of PaaS. So if you understand what CF is all about, it's great for turn-key but there are other things that are only pieces of what customers are trying to do and that's where you get into the "un-structured PaaS". We feel that most "un-structured PaaS" will start to look more structured towards as it progresses. And vice-versa, the structured PaaS will start looking unstructured while in tries to adopt all these new things that pop up in the OSS world. but of course, that's a little bit harder to do. 

---
# Stepping down the stack

- Dell acquisition is good for this project
- What does a platform for containers look like on bare-metal
- How do you deploy and manage the life-cycle?

^ You will see us stepping down the stack with RackHD. When we merge with Dell this project will get some more legs. But The {code} team will be looking at what a Platform for containers looks like and what that looks like on top of bare-metal. How to deploy and manage the lifecycle of these things. Additioanlly, the bare-matel capabilities to deploy ScaleIO and ECS and other storage softwares so we can combine these to create a rapid way of hyper-scaling an environment that's fit for container usage.

---
# * as {code}

- continue to deliver EMC II technology that's friendly to developers
- new categories such as storage as code

^ Everything as code. EMC as code is another way to think about the {code} team delivering EMC technology as a way that's friendly to developers, which is code. You're going to see us start building a category of storage as code, and perhaps building out other ones. 

---
# Focused but also open to all container runtimes and schedulers

- Continue to build in open and abstract ways
- the container run-time battle is heating up

^ We've got a core project that we will talk about but when we are developing these core projects we don't want to write them in a way that they are hyper-focused and tied to a single entity. We have to build in open and abstract ways. The battle of what container run-time will win is happening right now. Of course, we all know about Docker but there are plenty of others out there trying to eat their lunch. We all know how fast they moved, someone else could move just as fast. In 3 years, we don't know. There may be other container run-times that use part of the Docker code. So we have to be open to the changing landscapes.

---

# Focused Projects
![original](https://raw.githubusercontent.com/emccode/emccode.github.io/master/images/badge.png)

---
# REX-Ray

- https://github.com/emccode/rexray
- Persistent Storage Access for Container Runtimes
- REX-Ray 0.3.1 released 12/30/15
    + VMAX, Isilon, GCE, Virtualbox
    + Pre-Emption Support

![right](https://raw.githubusercontent.com/emccode/emccode.github.io/master/images/items/rexray.png)

^ REX-Ray is all about storage persistence. Right now it is the glue between Docker and Mesos and EMC II and other Clouds. Think of it like the Vipr-C or Cinder of the container world. REX-ray is fundamental to our focus areas because it enables EMC II to be relevant in these new worlds so we talk about it a lot. We can bring EMC ideas and technology into projects through plugins and schedulers. We will show a demo of this a little bit later. REX-Ray a ton of EMC things. Outisde of EMC we support AWS, GCE, VirtualBox, and Cinder. Cinder opens the door for basically every OpenStack deployment that's out there and wants to utilize container technologies within those VMs. A major feature is pre-emption, which gets us further into HA and enterprise features. Without this, say a container scheduler restarts a container with a persistent volume on another host. The container will fail to persist data because the volume is locked and attached to the original host. Pre-emption support enables REX-ray to forcefully remove a volume from an existing host and bring it to the host that requested the volume. So in the case of HA or reschduleing, the container's data will follow it whereever it gets rescheduled. this is analgous to Vmware HA.

---

#mesos-module-dvdi

- https://github.com/emccode/mesos-module-dvdi
- enables existing Docker Volume Drivers to be used without Docker.
- mesos-module-dvdi 0.3
    + 0.23, 0.24, 0.25, 0.26
    + Mesos Containerization

![right](https://raw.githubusercontent.com/emccode/emccode.github.io/master/images/items/mesos-module-dvdi.png)

^ The next major release was 0.3 for mesos-module-dvdi. This was a big deal because this brings support for mesos volumes. so if you are using any framework with mesos such as hadoop, cassandra, or any other scheudlers, you can specify the native mesos containerization to bring volumes to the workload. Because previously we only supported the docker volume driver. We also adapted it versions 23, 24, 25, 26 which hopefully supports many of the wider spread versions being ran in the community. 


---

# RackHD

- https://github.com/RackHD/RackHD 
- Bare-metal orchestration with a work flow engine
-  1.0

![right](https://raw.githubusercontent.com/emccode/emccode.github.io/master/images/items/rackhd.png)

^ RackHD 1.0 got released end of december. the early phase is about awareness and get hands-on. so you can get stated learning about the API and the uniqueness it brings to market. So we have a video and a blog post showcased. So any developer that wants to get started has an easy barrier to entry. You can go to the project and spin up a vagrant box to get started

---

# Roadmap Review

https://github.com/emccode/roadmap