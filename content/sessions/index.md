---
title: "Sessions 🗓️"
date: 2022-01-13T20:43:22+01:00

---

<!--Currently, sessions are not yet published for Azure Bootcamp Switzerland 2023. Check out our past events in [the event archive]({{< ref "/archive/_index.md" >}}) for a glimpse of past agendas and sessions. If you are interested in speaking at Azure Bootcamp Switzerland 2023 please let us know.

{{< alert "circle-info" >}}
🎙 Call for speakers for is now open. [Submit your session](https://sessionize.com/azure-bootcamp-switzerland-2023/) and be part of the Azure Bootcamp Switzerland 2023! Whether it's a deep dive session on a specific service or a case study on using Azure in your business, we'd love to hear from you!
{{< /alert >}}

{{< figure src="keynote2022.jpg" alt="Picture of the presenters and audience at the keynote session of Azure Bootcamp Switzerland 2022" >}}
-->

We are very happy to be able to offer you once again an exciting lineup including many new speakers, both from the local and international community, consisting of MVPs, Microsoft employees and industry leads, who will speak about specific use cases in the industry as well as the latest developments around services in Azure. Be it **real life use cases from Pax insurance, Axpo, Georg Fischer, and Liiva**, a kickstart with **FinOps on Azure, Azure Quantum Compute or PowerBI** or **deep dives on Azure networking** - these sessions will provide you with insights around Azure and the opportunity to connect with peers and speakers.

The schedule is still subject to change.

| **Time** | **DevOps** </br> Room 3.54 | **Infrastructure** </br> Room 3.53 | **Future Tech** </br> Room 3.14 |
| - | - | - | - | - |
| 0800 | ⏰ Registration |||
| 0910 <td colspan="3">⭐ [How we Build Data Clean Rooms on Azure Confidential Computing at Decentriq](#decentriq) <br /> 🙂 [DAVID STURZENEGGER](https://www.linkedin.com/in/david-sturzenegger/) <br /> 🙂 [PRIMO AMREIN](https://www.linkedin.com/in/primo-amrein-12a336/) </td>
| 1010 <td colspan="3"> ☕ Coffee Break</td>
| 1040 | ⭐ [Kubernetes @ PAX - DevOps at a Swiss Insurance](#paxdevops) <br /> 🙂 [SASCHA SPREITZER](https://www.linkedin.com/in/sspreitzer/) <br /> 🙂 [ESRA DOERKSEN](https://www.linkedin.com/in/esra-doerksen-560a9b177/)| ⭐ [Building a Lakehouse Platform on Azure with Databricks](#lakehouse) <br /> 🙂 [HANSJÖRG WINGEIER](https://www.linkedin.com/in/hansjoerg-wingeier) <br /> 🙂 [NIK WOLFGRAMM](https://www.linkedin.com/in/nikwol/)| ⭐ [Azure FinOps: The Quiz](#cloudcost) <br /> 🙂 [ROLAND KRUMMENACHER](https://linkedin.com/in/rolandkrummenacher/) <br /> 🙂 [STEFAN DENK](https://www.linkedin.com/in/stefandenk/)|
| 1135 | ⭐  [Axpo DevOps Dojo](#axpodevops) <br /> 🙂 [ARINDAM MITRA](https://www.linkedin.com/in/arindam-mitra-28981095/) | ⭐ [The immutable laws of security](#lawsofsecurity) <br /> 🙂 [ALAIN SCHNEITER](https://www.linkedin.com/in/alain-schneiter-430280166) <br /> 🙂 [MICHAEL RÜEFLI](https://www.linkedin.com/in/drmiru/)| ⭐ [God really plays dice - Introduction to quantum computing with Q#](#quantum) <br /> 🙂 [FILIP WOJCIESZYN](https://www.strathweb.com/) |
| 1220 | 🍕 Lunch Break |||
| 1330 | ⭐ [Pushing Azure (DevOps) @ Georg Fischer](#pushingazure) <br /> 🙂 [MARTIN STANEK](https://www.linkedin.com/in/awitec/) | ⭐ [Azure Networking vNext - How to build modern connectivity for IaaS, PaaS and SaaS](#networkingvnext) <br /> 🙂 [ERIC BERG](https://linkedin.com/in/ericbergde) | ⭐ [How can Microsoft Azure help with sustainability? Methods to estimate your cloud’s carbon footprint](#sustainability) <br /> 🙂 [WIBKE SUDHOLT](https://ch.linkedin.com/in/wibkesudholt) |
| 1425 | ⭐ [Push your Azure tenant to the next level with Power BI](#powerbi) <br /> 🙂 [DENIS SELIMOVIC](https://www.linkedin.com/in/denis-selimovic/) | ⭐ [Azure PaaS, but as private as possible...](#azurepaas) <br /> 🙂 [STEPHAN GRABER](https://linkedin.com/in/stephan-graber-945324178/) | ⭐ [Use the power of OpenAI to leverage your business application](#openai) <br /> 🙂 [DAVID SCHNEIDER](https://www.linkedin.com/in/david-schneider/) |
| 1510 <td colspan="3"> ☕ Coffee Break</td>
| 1540 | ⭐ [Securing web applications using Azure AD](#securingapps) <br /> 🙂 [DAMIEN BOWDEN](https://www.linkedin.com/in/damien-bowden-42a450176/) | ⭐ [Azure Virtual Network Manager: The future of network management?](#avnm) <br /> 🙂 [MARCEL ZEHNER](https://www.linkedin.com/in/marcelzehner) | ⭐ [Eventdriven systems on Azure done right](#eventdriven) <br /> 🙂 [ROBIN KONRAD](https://www.linkedin.com/in/robin-konrad) |
| 1635 | ⭐ [Fully automated & cloud-native data platform](#dataplatform) <br /> 🙂 [TIM GIGER](https://www.linkedin.com/in/tim-giger-265412b5/) | ⭐ [Building a bank in the cloud](#buildingbank) <br /> 🙂 [MATTHEW KEY](https://www.linkedin.com/in/matthewselkirkkey/) | ⭐ [Develop for inclusion using cognitive services: an Azure story](#inclusion) <br /> 🙂 [ANDRÉ MELANCIA](https://linkedin.com/in/AndreMelancia) |
| 1720 <td colspan="3"> 🍻 Networking Apéro sponsored by isolutions </td>
| | | | | |


### <a name="decentriq"></a> ⭐️ How we Build Data Clean Rooms on Azure Confidential Computing at Decentriq
[Decentriq](https://www.decentriq.com/) is a Zurich based startup developing leading-edge data privacy products for sensitive industries. They have been awarded the startup of the year 2022 award by Microsoft.
This presentation will open with an overview of Microsoft’s confidential computing strategy and Azure's Confidential Compute offering. Decentriq will then present their confidential computing-based data collaboration platform, a deeper dive into the technology as well as use-cases of their customers ranging from banks to pharmaceutical companies.
In many cases it would be desirable to combine sensitive datasets from multiple sources to compute anonymous statistics. Examples range from healthcare research to customer analytics to anti-money laundering and marketing. However, the fact that data comes from multiple sources means that at least one party has to disclose sensitve data to another. In practice this usually means that such use-cases are blocked either for legal or lack-of-trust reasons.
Confidential computing is a CPU-rooted privacy technology that enables the processing of data while keeping the data inaccessible to all parties - including all participants, the SaaS platform and infrastructure providers. Encryption in-use enables data to stay encrypted also in memory and prevent access by the operating system. Remote attestation enables users to remotely verify that a server indeed runs in confidential computing and even what code it is running.   
🙂 [DAVID STURZENEGGER](https://www.linkedin.com/in/david-sturzenegger/) ⚡️ Head of Product @ Decentriq  
🙂 [PRIMO AMREIN](https://www.linkedin.com/in/primo-amrein-12a336/) ⚡️ Cloud Lead @ Microsoft Switzerland 

### <a name="paxdevops"></a> ⭐️ Kubernetes @ PAX - DevOps at a Swiss Insurance
Listen to the experience of a DevOps journey in the insurance industry with Azure Kubernetes Service and Aveniq DevOps Service. In this session, you will see how [PAX](https://www.pax.ch/) is leveraging the benefits of DevOps and Kubernetes to streamline their software development process and shift their business logic to a self-healing, auto scalable and highly available microservices platform. Experience how Azure Kubernetes Service can enable developers, shorten Time to Market and continuously deliver updated products and services to business partners and end customers without interruption.   
🙂 [SASCHA SPREITZER](https://www.linkedin.com/in/sspreitzer/) ⚡️ Tech Lead Container Platform & DevSecOps @ Aveniq  
🙂 [ESRA DOERKSEN](https://www.linkedin.com/in/esra-doerksen-560a9b177/) ⚡️ Software Engineer @ Pax Versicherung

### <a name="lakehouse"></a> ⭐️ Building a Lakehouse Platform on Azure with Databricks
In this talk, we will introduce Hadron, a project that involves building a new platform for die Mobiliar to run all BI, ML, Analytics, and AI workloads. The platform is built on the Lakehouse architecture from Databricks and hosted on Azure. We use multiple Databricks Workspaces and UnityCatalog from Databricks. Our project needs to adhere to the pre-defined cloud architecture for application deployment on Azure within our company. The data on the platform is organized using the DataMesh/DataProduct approach. We began the project in February 2022 and have made significant progress in building the infrastructure, allowing for large-scale data products to be deployed on the platform.

Our talk will cover the following topics:
1. Introduction: We'll discuss our goals for the new platform and why we chose the Databricks Lakehouse approach.
2. The key components of the Lakehouse architecture: Unity Catalog, Databricks Workspaces, and how access control is managed.
3. Overview of the cloud architecture within our company and how it informs the infrastructure of the platform.
4. Infrastructure overview: how we organize Databricks Workspaces, Azure Data Lake Storages, and how the storage is networked with the workspaces to ensure secure access.
5. Automation: We'll explain how we use GitLab Pipelines and Terraform, as well as Databricks APIs, to automate the deployment of resources and manage access controls.
6. Key decisions made during the architecture design and why they were important.
7. Challenges we encountered during the project and how we overcame them.
8. Current status of the infrastructure: what data is available and who is currently using the platform.
9. Next steps: where we plan to go from here.

🙂 [HANSJÖRG WINGEIER](https://www.linkedin.com/in/hansjoerg-wingeier) ⚡️ IT Architect @ Die Mobiliar  
🙂 [NIK WOLFGRAMM](https://www.linkedin.com/in/nikwol/) ⚡️ IT Architect @ Die Mobiliar

### <a name="cloudcost"></a> ⭐️ Azure FinOps: The Quiz
Are you looking for ways to save money on your Azure bill? Join us for a fun and interactive quiz-based session on Azure cost optimization. As experienced Azure FinOps consultants, we've seen it all when it comes to inefficient resource usage, unexpected cost spikes, and other common Azure cost pitfalls. In this session, we'll present several real-life scenarios that we've encountered in our daily work and challenge the audience to come up with cost-saving solutions.

You'll learn:
* How to identify wasteful spending in your Azure environment
* Best practices for optimizing Azure costs
* Tips and tricks for reducing your Azure bill without sacrificing performance

Whether you're an Azure newcomer or an experienced user, this session will give you a fresh perspective on cost optimization and help you save money on your Azure bill. Join us for an engaging and informative session, and put your Azure cost-saving skills to the test!   
🙂 [ROLAND KRUMMENACHER](https://linkedin.com/in/rolandkrummenacher/) ⚡️ FinOps Consultant @ Swisscom  
🙂 [STEFAN DENK](https://www.linkedin.com/in/stefandenk/) ⚡️ FinOps Consultant @ Swisscom

### <a name="axpodevops"></a> ⭐️ Axpo DevOps Dojo
Axpo Solutions Journey to DevOps.   
🙂 [ARINDAM MITRA](https://www.linkedin.com/in/arindam-mitra-28981095/) ⚡️ 
Senior IT Infrastructure Specialist @ Axpo | Microsoft Azure MVP  

### <a name="lawsofsecurity"></a> ⭐️ The immutable laws of security
Since the original immutable laws, information security has grown from a technical discipline into a cybersecurity risk management discipline that includes cloud, IoT and OT devices. Now security is part of the fabric of our daily lives, business risk discussions, elections, and more.
This session will cover the 10 laws of cybersecurity risks and show, how you can prevent against attackt during your daily job. A small extract of a few of this laws are:
"Cybersecurity is a team sport", "your network isn’t as trustworthy as you think it is" and "technology doesn't solve people and process problems". We will cover 7 more.   
🙂 [ALAIN SCHNEITER](https://www.linkedin.com/in/alain-schneiter-430280166) ⚡️ Solutions Architect @ scopewyse | Microsoft Security MVP  
🙂 [MICHAEL RÜEFLI](https://www.linkedin.com/in/drmiru/) ⚡️ Solutions Architect @ scopewyse | Microsoft Azure MVP

### <a name="quantum"></a> ⭐️ God really plays dice - Introduction to quantum computing with Q#
Quantum mechanics is one of the fundamental theories of physics, and has been tremendously successful at describing the behavior of subatomic particles. However, its counter-intuitive probabilistic nature, bizarre rules and confusing epistemology have troubled some of the greatest physicists of the 20th century, prompting Albert Einstein to remark “God doesn’t play dice”.
Today, we are at the dawn of the quantum computing age, a multidisciplinary field that sits at the intersection of physics, computer science, mathematics and chemistry and may revolutionize the technological world. In this talk, we will dive into the bizarre quantum world and explore the high-level mathematical foundations of quantum computing, quantum programming circuits and some basic ideas behind it using a new quantum programming language, Q#.   
🙂 [FILIP WOJCIESZYN](https://www.strathweb.com/) ⚡️ Cloud Architect @ Sonova | Microsoft Quantum MVP

### <a name="pushingazure"></a> ⭐️ Pushing Azure (DevOps) @ Georg Fischer
Tips and tricks how a small team at [Georg Fischer Machining Solutions](https://www.georgfischer.com/) can handle big infra and distributed system on scale.    
🙂 [MARTIN STANEK](https://www.linkedin.com/in/awitec/) ⚡️ Software Architect @ Georg Fischer Machining Solutions

### <a name="networkingvnext"></a> ⭐️ Azure Networking vNext - How to build modern connectivity for IaaS, PaaS and SaaS
When you are working with Microsoft Azure Services you will come across the topic of Network Integration. But is a classical VPN the right solution? Do I always need ExpressRoute? Should I adopt VirtualWAN? And what about my APIs in the Cloud?
This session will help you to understand the available options to build modern Azure Networks. We will figure out how a solution-design could look like and which limitations apply. Also we will have a look into services that do not have options to integrate into a classical network and how you could mitigate this. Let's figure out how to modernize networking in Azure!   
🙂 [ERIC BERG](https://linkedin.com/in/ericbergde) ⚡️ Vice President Consulting Expert @ CGI | Microsoft Azure MVP 

### <a name="sustainability"></a> ⭐️ How can Microsoft Azure help with sustainability? Methods to estimate your cloud’s carbon footprint
Climate change and the looming energy crisis increasingly also have an impact on IT. Apart from moral responsibility there are serious commercial forces connected to this, including rising costs and risks of business interruption as well as influences on corporate image and government regulations. Cloud computing is debated to be both a problem as well as an answer here. Therefore, it is important to consider the sustainability of Microsoft Azure.
Microsoft provides several tools to evaluate and drive sustainability aspects such as energy consumption and carbon footprint. This goes from a simple website to estimate the emission savings for Microsoft Cloud over the Emissions Impact Dashboard for Microsoft Azure in Power BI up to the Microsoft Sustainability Manager, an elaborated solution to record, report and reduce your environmental impact. Furthermore, there are external solutions such as the free and open source tool Cloud Carbon Footprint, which allows to estimate the energy consumption and carbon emissions of cloud usage across several hyperscalers.
This talk starts with a summary about what is publicly known regarding the sustainability of the Microsoft Azure cloud in general. We then look at the different tools that are available to estimate important metrics such as carbon emissions and what their capabilities and use cases are. I’ll also show limits, in particular the complexity to calculate sustainability indicators for on-premises data centers in comparison to cloud. Goal is to give you an overview at hand helping you to judge how well the Microsoft Azure cloud supports you on your way to a more sustainable future.   
🙂 [WIBKE SUDHOLT](https://ch.linkedin.com/in/wibkesudholt) ⚡️ Head of Biz Dev Cloud & DC @ SPIE ICS AG

### <a name="powerbi"></a> ⭐️ Push your Azure tenant to the next level with Power BI
You've already heard a lot about Microsoft Power BI, but you're not sure how you can use it?
In this session I will give you an introduction of what exactly is Power BI and what you can do with it. I will demonstrate what other companies already do with it and especially how you can use it, to get the most out of your Azure tenant!  
🙂 [DENIS SELIMOVIC](https://www.linkedin.com/in/denis-selimovic/) ⚡️ Principal Consultant @ b.telligent

### <a name="azurepaas"></a> ⭐️ Azure PaaS, but as private as possible...
Azure PaaS is a great option to modernize your environment, but what happens if everything needs to be secured and the services need to be as private as possible? What is possible and where are limitations? Are there best practices and when is it necessary to change the mindset?   
🙂 [STEPHAN GRABER](https://linkedin.com/in/stephan-graber-945324178/) ⚡️ Partner and Cloud Engineer @ GrabX Solutions

### <a name="openai"></a> ⭐️ Use the power of OpenAI to leverage your business application
In recent months, AI models have made huge strides. In this session, you'll learn how to make a business application fit for the future thanks to Azure OpenAI Services. We will discuss some uses on how you can empower your business application users with OpenAI.
However, the large language models must first build the company's knowledge. With embeddings, you can "teach" them domain knowledge. You will learn how to create and consume such embeddings but also get some ideas about how to integrate them in your application. There will be a lot of demos, but we won't go into the details.   
🙂 [DAVID SCHNEIDER](https://www.linkedin.com/in/david-schneider/) ⚡️ CTO @ isolutions | Microsoft M365 Apps and Services MVP

### <a name="securingapps"></a> ⭐️ Securing web applications using Azure AD
This developer session shows how authentication, authorization and security requirements can be implemented using Azure AD and Azure AD B2C as an identity provider. Some of the different approaches when implementing these in SPAs like Angular or Blazor, server rendered applications like ASP.NET Core Razor/MVC will be explained as well as the different OpenID Connect/OAuth flows which should be used or can be used for these types of solutions.  
🙂 [DAMIEN BOWDEN](https://www.linkedin.com/in/damien-bowden-42a450176/) ⚡️ Consultant @ isolutions | Microsoft Developer Technologies MVP

### <a name="avnm"></a> ⭐️ Azure Virtual Network Manager: The future of network management?
Having control over you hybrid network is key because many services require rock-solid and secure connectivity. There are multiple options available today to deploy, maintain and extend your network environment. But which one is the best fit for you? The latest service that Microsoft released recently to address this is 'Azure Virtual Network Manager' (AVNM). In this session, Marcel introduces you to this new service and gives you a behind-the-scenes view so that you are weaponized to use it out in the wild.  
🙂 [MARCEL ZEHNER](https://www.linkedin.com/in/marcelzehner) ⚡️ Microsoft Cloud Champion @ SoftwareONE | Microsoft Regional Director & Azure MVP 

### <a name="eventdriven"></a> ⭐️ Eventdriven systems on Azure done right
Event-driven architectures (EDA) are becoming increasingly popular as a way to build scalable, responsive, and resilient systems.In this talk, we will explore the benefits of EDA and how to implement it on Azure. It will cover key concepts of EDA, such as Event Sourcing, CQRS, Event-based communication, event-driven data processing and its matching services on Azure (e.g. Event Grid, Event Hub, Service-Bus, Functions). Additionally, we will introduce best practices for designing, implementing and testing EDA on Azure. By the end of this talk, all attendees will have an overview of possibilities with EDAs on Azure, pitfalls and best practices related. Also they will ava a starting point to apply this knowledge to their own projects.  
🙂 [ROBIN KONRAD](https://www.linkedin.com/in/robin-konrad) ⚡️ Azure Architect @ Xpirit

### <a name="dataplatform"></a> ⭐️ Fully automated & cloud-native data platform
For a large insurer in Switzerland, we implemented a fully automated and cloud-native data platform using Azure and Bicep. Among other things, Azure DevOps, Azure Data Lake Storage, Azure Synapse and Databricks were used. Business stakeholders also have the ability to set up a 3-tier analytics workspace based on Azure Synapse and Azure DevOps at the click of a button and start exploring the data lake and implementing use cases. The data lake is loaded in real time via Kafka/Databricks and batch-oriented via Azure Data Factory - in total over 100 different data pipelines. These pipelines feed the core Data Warehouse, implemented with Azure Synapse.   
🙂 [TIM GIGER](https://www.linkedin.com/in/tim-giger-265412b5/) ⚡️ Senior Data & Analytics Consultant @ Swisscom

### <a name="buildingbank"></a> ⭐️ Building a bank in the cloud
Considerations when deploying a green field Financial Services Landing Zone in Azure. "Best practice" and gotchas.   
🙂 [MATTHEW KEY](https://www.linkedin.com/in/matthewselkirkkey/) ⚡️ Azure Architect @ Nordcloud

### <a name="inclusion"></a> ⭐️ Develop for inclusion using cognitive services: an Azure story
Disabilities are not limitations. Technology helps balance the scale.
This session shows some practical examples for real world usage, and you are encouraged to use these technologies to make your projects even more amazing and welcoming to everyone.   
🙂 [ANDRÉ MELANCIA](https://linkedin.com/in/AndreMelancia) ⚡️ Owner & Principal Consultant @ LunarCat.PT

