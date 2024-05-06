# Resume

Name: 		Leo Liu  
Gender: 	Male          
WeChat:	  15640096976  
Email:		280041640@qq.com  

Occupational Positions: Software Product Architect, Product Manager, Project Manager

Self-assessment
1.	Over 20 years of experience in designing and developing B/S application systems, familiar with the technology and products within the field.
2.	Strong object-oriented analysis skills, familiar with building and applying microservices architecture in Spring-Cloud technology stack. Proficient in using appropriate design patterns to architect software systems at different levels and applying mature best practices in design and development.
3.	Abstract system architecture requirements through personal experience, developing organizational structures and communication mechanisms for key software components.
4.	Proficient in applying mature data structures and algorithms to build high-performance, scalable, multi-threaded concurrent server systems.
5.	Strong coding skills, familiar with the features of Java, PHP, Python, C#, and Unity3D languages, capable of high-quality development.
6.	Deep understanding of microservices architecture, able to think in terms of microservices when abstracting systems, familiar with architectural standards.
7.	Experience in building architectures for large-scale websites, with a deep understanding of mainstream application server configurations.
8.	Able to independently complete work tasks, possessing strong communication skills to effectively communicate with individuals in different roles.
9.	Able to communicate via email, documents, and discussions in English.
10.	Experienced in multiple software product cycles, proficient in the theoretical specifications of software engineering RUP and object-oriented analysis/design (OOA/OOD) principles, and applying MDA to practical projects.
11.	Strong problem-solving skills, quick understanding of new technologies, and strong time management abilities.

Project Experience

Product Name: CIM 3D Data Visualization Platform
Product Description: The platform supports the integration of three-dimensional urban spatial models and urban information, providing comprehensive multidimensional spatiotemporal model support for the construction of digital twin cities. Based on a visualization-based intelligent data platform, it constructs a unified digital foundation for urban operation and management. It integrates multi-domain information systems and data resources to deepen government services and city operation management, supporting the efficient operation and rapid intelligent response to urban health and emergencies. It adapts to various mainstream smart transportation platforms and autonomous driving platform data standards, aggregating and modeling raw transportation data from multiple platforms, and providing specialized and thematic data layers and other business support capabilities. It provides data security for enhancing the intelligence of urban transportation operations. Meanwhile, in terms of enhancing the value of transportation data, it provides high-quality transportation data services for other functional departments by governing, confirming, and reorganizing aggregated data. It promotes the empowerment of urban safety development and operation with real-time transportation data in digital cities, gradually improving the management of transportation data assets and the construction of transportation data circulation systems.
System Description: The system is built in the form of SpringCloud microservices, integrating data middle platform, data aggregation, data assets, and other microservices. The development architecture is front-end and back-end separation, using ElementUI VUE3 version as the front-end development framework. It integrates GeoTools for spatial data parsing, uses Open3D to publish point cloud 3D mesh data, integrates multiple geographical data publishing APIs such as WMS and ArcGISRest to achieve multi-source data aggregation. Aggregated data is dynamically managed through the data asset module. Metadata and actual data are stored in a mixed relational and non-relational manner.
Operating Environment: Linux, MySQL, Nginx, Tomcat Middleware: Nacos, Redis, GeoServer, CesiumJS Development Environment: Eclipse, Maven, WebStorm, EditPlus;
Responsibilities: Requirement analysis and technical architecture design; Conversion and storage of multi-source data; Management of metadata and dynamic publishing of spatiotemporal data interfaces; Development of lineage analysis module code; Development of modules such as map publishing and 3D model management in the data aggregation module.

Product Name: Immersive Teaching Service Platform
Product Description: The Immersive Teaching Service Platform integrates the fully immersive experience of VR into education, innovates courseware content, and enables learners to deepen their understanding of knowledge and experience through multidimensional learning on a cloud service platform. The education categories will cover vocational skills, university education, K12 education, and life safety education, among others.
System Description: The platform is built on the SpringBoot framework as the development foundation. RabbitMQ is used for communication between client courseware and the server. The client uses QT development to convert VUE into a client-side mode for secondary packaging. VR courseware is developed using Unity3D, and is managed uniformly by the server-side courseware management module, which is then made available for download and use by the client. Courseware development utilizes a self-developed task engine, which triggers real-time transmission of the current user's operating status information back to the server, and receives scoring immediately after the courseware is completed.
Operating Environment: Linux, MySQL, Nginx, SpringBoot, iview Middleware: RabbitMQ, Redis Development Environment: Eclipse, WebStorm, Unity3D, EditPlus;
Responsibilities: Overall platform design and technical architecture development; Design and implementation of courseware task engine; Unity3D courseware development, C# script writing; Framework construction, development of server-side courseware resource management module; Development of server-side student exam management and skill assessment modules; Design and implementation of key software components; System performance tuning, capturing and tracking system performance metrics, adjusting application parameters to achieve optimal framework operation.

Product Name: Smart Emergency Management Platform
Product Description: The Smart Emergency Command and Dispatch Platform realizes the 1+M+N emergency command and dispatch mode, with "one database, one map, one terminal" as the core, forming a digital integration platform for emergency event processing, including rapid response, digitization of emergency plans, automation of emergency materials and force dispatch, intelligent convergence and assessment of video monitoring, and digitalization of command system.
System Description: The system is based on the SpringBoot open-source framework, with framework code automatically generated by a self-developed MDA tool. It adopts front-end and back-end separation technology, with SpringBoot+SpringMVC publishing services on the back end and Vue2's iview framework on the front end. Nginx is used as the WEB server, and Redis is used for database caching. Kafka is used to obtain data from the Internet of Vehicles, and a WebSocket channel is constructed to continuously retrieve and display multiple public transportation data to the front end in real time.
Operating Environment: Linux, MySQL, Nginx, SpringBoot, iview Middleware: Redis, Kafka, RabbitMQ, CesiumJS Development Environment: Eclipse, WebStorm, Maven, EditPlus;
Responsibilities: Emergency management command platform requirement analysis, design; Technical architecture design; Application service architecture design for platform subsystems; Development of core business logic; Development of logic code for vehicle arrival and video interface linkage; Development of dynamic scheduling logic code.
Product Name: DevOps Platform Based on Docker Container Technology
Product Description: The platform integrates various DevOps open-source products using Docker containers and encapsulates them into a unified DevOps engine externally. The platform interacts with the engine through APIs, allowing users to experience the DevOps development process without needing to understand the internal architecture.
System Description: The system is based on the Spring Boot open-source framework and integrates DevOps middleware such as Jenkins, Maven, Splunk, and Git using Docker for dynamic installation and configuration management.
Operating Environment: Linux, MySQL, Nginx, Docker Middleware: Jenkins, Maven, Splunk, Git, Velocity Development Environment: Eclipse, GitLab, SpringBoot, Tomcat; EditPlus, AE;
Responsibilities: Technical architecture validation and design; DevOps Docker environment setup, script writing; Saas platform analysis and design; DevOps module development.

Product Name: Yuxin Yicheng SocialEvertalk
Product Description: SocialEvertalk is a tool to help enterprises with social customer service. It integrates information from mainstream microblogging platforms, allowing enterprises to discover user feedback on social media, collaborate with multiple team members to handle feedback, and add approval and publishing functions for enterprises. It also provides a set of approval and publishing processes for official accounts. It provides performance and statistical reports for team members and official accounts.
System Description: The system is based on the Java open-source framework Struts2+Spring3+Hibernate with no configuration development. Framework code is automatically generated using a self-developed MDA tool, reducing the threshold for developers and improving development efficiency. Nginx+Tomcat is used as the WEB server, and Memcached is used for database caching.
Operating Environment: Linux, MySQL, Nginx, Tomcat Middleware: Memcached, Weibo API Development Environment: Eclipse, SVN, Ant, Tomcat; Axure, Edraw, EditPlus, Rose7, Struts2, Spring3, Hibernate;
Responsibilities: Java Technical Manager Technical architecture design; Network application service architecture design API interface specification and detailed design proposal; Framework construction, integration between various application platforms; Development of abstract business components for business logic extension; Design and implementation of key software components; System performance tuning, capturing and tracking system performance indicators, adjusting application parameters to achieve optimal framework operation;

Product Name: Yuxin Yicheng Belink Enterprise Community Application Platform
Product Description: Belink Enterprise Community Application Platform is a platform to help bank enterprises establish enterprise social network communities on social network platforms. Based on the ThinkPHP framework and Thinksns community open-source product, it helps bank enterprises establish their own enterprise social network communities. The core is to establish a strong interactive relationship between bank customer managers and bank customers, provide a platform for user interaction and communication based on the community, and provide a third-party application access framework to integrate social network resources.
System Description: The system is developed based on the PHP open-source MVC framework ThinkPHP and refers to the ThinkSNS open-source community product in the SNS model. Nginx is used as a reverse proxy and for dynamic/static separation, and Memcached is used for database caching. It establishes bank customer manager homepages, enterprise user homepages, and SNS follow, message, and dynamic functions, providing the basic framework and extension application interface for SNS enterprise communities.
Operating Environment: Linux, MySQL, Nginx, Apache Middleware: Memcache Development Environment: Eclipse, SVN, Ant, ZendDebug, PHP5.2; Axure, Edraw, EditPlus, Rose7;
Responsibilities: PHP Technical Manager Technical architecture design; Network application service architecture design API interface specification and detailed design proposal; Framework construction, integration between various application platforms; Development of abstract business components for business logic extension; Design and implementation of key software components; System performance tuning, capturing and tracking system performance indicators, adjusting application parameters to achieve optimal framework operation;

Product Name: bylife.com Enterprise Social Marketing Service Platform
Product Description: bylife Service Platform is a platform to help small and medium-sized bank enterprises conduct independent brand marketing on social network platforms. It currently relies on Sina and Tencent Weibo, helping enterprises establish friendly relationships with customers on the Weibo platform, anticipate potential crises, and develop the brand value of enterprises on Weibo.
System Description: The system is developed based on the PHP open-source MVC framework StatusNet. Nginx is used as a reverse proxy and for dynamic/static separation, and Memcache is used for database caching. OAuth is used to obtain third-party authentication. Communication with the outside world is done through OpenAPI, including backend tools in Java. The system uses Java programs as backend task managers and massive data collection tools for Weibo platforms. It also provides PHP invocation interfaces (OpenAPI) to compensate for PHP's deficiencies in this area.
Operating Environment: CentOS5.5, MySQL, Nginx, Tomcat, Apache Middleware: Memcache, OAuth Development Environment: Eclipse, SVN, Ant, ZendDebug, PHP5.2; Axure, Edraw, EditPlus, Rose7;
Responsibilities: Development Manager Technical architecture design; Network application service architecture design Product feature analysis and design; API interface specification and detailed design proposal; Framework construction, integration between various application platforms; System performance tuning, capturing and tracking system performance indicators, adjusting application parameters to achieve optimal framework operation;

Project Name: dapengwang.com - Dapeng Net
Product Description: Dapeng Net is a portal website focusing on flying sports, particularly paragliding. The website offers services such as industry news, event tracking, flying activities, product quotes, club inquiries, and venue searches, catering to enthusiasts of paragliding.
System Description: The system is built on the mainstream CMS open-source software Joomla as the development framework. It integrates front-end template plugin Smarty and data cache MemCache. The development process entirely relies on plugin construction to implement different business modules, which can be flexibly disassembled. The front-end adopts DIV+CSS layout for clear module loading and easy search engine optimization.
Operating Environment: IBM server, CentOS5.5, MySQL, Nginx, Apache Middleware: Memcache, Joomla, JQuery, Smarty Development Environment: Eclipse, EditPlus, SVN, ZendDebug, PHP5.2
Responsibilities:
•	Technical architecture design
•	Network application service architecture design
•	Detailed design and development of business components
•	System performance optimization

Project Name: itour.cn - Electronic Tourism Integration Platform
Project Description: Zonghengtiandi is one of the largest travel product trading service providers in China, offering services such as ticket sales, hotel reservations, tour product ordering, and group travel management. After introducing strategic investment, the company aims to establish a unified business management platform to gradually replace the existing operation platforms, enhancing service efficiency and reducing operating costs.
System Description: The system adopts a B/S structure, based on the SOA architecture of a distributed system. Various subsystems are called via WS encapsulated by Tibco ESB, including a unified interface platform, unified payment platform, CRM system, resource product management system, and order processing system. Communication between systems is achieved through JMS messaging, and CAS is applied as a single sign-on server, integrating JBPM and DROOLS as workflow and rules engines.
Operating Environment: IBM PC server, Linux4.2, Oracle10g, GlassFish2.1, JDK1.6 Middleware: CAS, JBPM, DROOLS, OpenMQ, Tibco ESB Development Environment: Eclipse, SVN, ANT, Log4j, JUnit
Responsibilities:
•	Business architecture design
•	Technical architecture design
•	Detailed design of payment platform architecture
•	Framework construction of systems and integration between various application platforms
•	Development of abstract business components using design patterns
•	Definition of software interface specifications for external systems and provision of technical solutions
•	System performance optimization, capturing and tracking system performance indicators, and adjusting system configurations and JVM parameters.

Project Name: MMBase Module Refactoring
Project Description: MMBase.org is a Dutch Java open-source organization, and the MMBase project is a content management system.
System Description: The project involves refactoring components of the open-source content management system, evolving from the concept of "everything is an object" to a software framework. It was a privilege to participate in the component refactoring work of MMBase.
Operating Environment: WindowsXP, Tomcat, MySQL, JDK Development Environment: Eclipse, JDK, XSL
Responsibilities:
•	Refactoring of MMBase's backend content management and publishing modules
•	Java technology communication

Professional Skills

1.	UML, ROSE, Visio
2.	RedHat Linux, CentOS
3.	Oracle (PL/SQL), DB2, SQLServer, MySQL, MongoDB
4.	PHP, J2EE, Web container, EJB container
5.	Nginx, Apache, GlassFish, Tomcat, JMS (queue, publish/subscribe), ESB, JBPM, DROOLS, CAS, Memcache
6.	SpringBoot, SpringCloud, MyBatis
7.	Eclipse, OSGi, GMF, EMF, GEF
8.	SVN, WinCVS, Log4j, Ant, Maven
9.	Node.js, Vue2, Vue3, iview, ElementUI
10.	Unity3D, C#

