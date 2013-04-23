# Behrang Noruzi Niya

### Software Developer

Phone: [+989125208859](tel:+989125208859)  
Email: [behrangn@gmail.com](mailto:behrangn@gmail.com)  
Twitter: [@behrangn](https://twitter.com/behrangn)  
GitHub: [github.com/behrang](https://github.com/behrang)  
Portfolio: [coderbits.com/behrang](https://coderbits.com/behrang)  
LinkedIn: [linkedin.com/in/behrangn](http://www.linkedin.com/in/behrangn)

## Summary

Detail oriented software developer and product designer.

## Experience

### Software Developer
Pardazeshgaran Saman  
June 2012 – Present

Web application development, development process improvement, user experience design, team building, teaching, improving security, product design.

### Software Developer
Tosan  
January 2008 – May 2012 (4 years 5 months)

Server side and web application development, development process improvement, user experience design, team administration, team building, teaching, improving security, product design.

### Software Developer
Pardazeshgar  
June 2006 – December 2007 (1 year 7 months)

## Projects

### Payment Gateway
January 2008

I designed and developed a new version of the company's payment gateway. Old version was a badly written and hard to maintain application, written as a single JavaServlet class. As the old version was being used by a few banks (like Saman at sb24.com) and many shopping web sites were already connected to it, backward compatibility was very important. The new version was developed using Struts 2 framework but the API remained the same as before. The new maintainable application with a better performance deployed with no change on the shopping sites.

### Messaging Application (Chapar)
October 2008

Chapar was a new product replacing an old product called message switch. Message switch's job was to send sms and email messages to bank customers when they had a transaction. Other uses were to send batch email reports or send responses to customer inquiries via sms about account balance or statement. This project was not maintainable and slow, and inflexible. It was a heavy weight Java EE app, using schedulers to send sms messages in batch, and badly written rules using many nested if-statements. It also needed a big expensive server for deployment.

Chapar replaced it and solved many of the problems of the old system. It was designed as a modular system. Some of the modules were: Core, Sms, Email, Im, and Fax. So at start, we supported two new media (Im and Fax) for messaging. Responses to customer inquiries could be sent to a different channel (for example account statement requested via sms could be sent to fax). Each module could be deployed independent of the others. Also to improve redundancy and performance, more than one copy of each module could be deployed on the same or another server. Chapar was designed and developed with Enterprise Integration Patterns (or EAI patterns) using Spring Integration framework. The declarative nature of Spring Integration helped reduce the maintenance costs. Also message queues were used to pass incoming and outgoing messages between different modules. A simple rule engine system was designed and developed to replace those nested if-statements. This rule engine makes the system very flexible. Some of the rules developed were: Delay (to delay sms messages generated at midnight), Account (to override default address of recipient for one of the customers accounts), Amount (to filter-out sms messages for transactions below a certain amount) and others. Modules were very light weight and they could be deployed on a very low-cost server.

### Internet Banking
April 2010

Improved the design and developed third generation of Internet Banking application. Old products were not stable and their performance was very bad. Some of the problems were: storing everything in user session storage, few JavaServlet classes handling everything, every request being a POST, double form submission, unwanted money transfer by using browser back button!, different code style for different parts of the project, bad conflicting CSS styles, including big uncompressed JavaScript files for doing nearly nothing, XSS holes, CSRF holes and etc.

I designed and help develop a new application with User Experience, Security, Performance and Maintainability in mind. The new app was a lot faster and safer. User interface was a lot simpler. Many features added because of improved maintainability. Also some AJAX features added to improve usability.

### Credit Card Management System (Diamond)
December 2010

I designed the UI/UX of a credit card management system and helped in developing it. This application was one of the most successful applications in company. It was a RIA (Rich Internet Application) with an intuitive and fast user interface. The app was a single page AJAX application. We used ExtJS for client side. Some of the features were: super simple interface, keyboard shortcuts for every interaction, window- and clutter-free, and client side export to Excel and PDF.

### Cheque Designer
July 2011

I helped in designing and developing a cheque (or check) designer application. It was a simple, beautiful application helping customers to design a template for their cheques and print their cheques with the actual cheque data (instead of filling it by hand).

### Internet Banking (Rakhsh)
October 2011

I designed and helped develop the next generation of the companies internet banking application. We called it Rakhsh. It was a rich internet application, with simple user interface. In addition to grid views, it had thumbnail views. It had some simple and quick animations. I also tried to create a team, and developed it using agile practices (Scrum). The team was great and together we built this application. I also designed and implemented a plugin architecture. Everything in this application was a plugin. Some of these plugins were: Login (with also a few authentication type plugins over it), Account, Card, Money Transfer (with different transfers being another plugin over this plugin) and some more. CoffeeScript was used for client side development. Also we used ExtJS.

### [ExtJS Mirror](https://github.com/behrang/extjs-mirror)
April 2012

ExtJS didn't support RTL (Right-To-Left) languages. This project which was open-sources at GitHub, solved this problem. It is a script that loads in the page and makes ExtJS RTL-compatible.

### Bam Saman
June 2012

I joined the team building Bam, a social banking application. It supports oAuth and helps users create profiles, and other social features. I helped in applying test practices, including integration tests.

### [Net Bank](https://ib.sb24.com)
September 2012

I joined the net bank team and tried to help them improving the product in security, performance, development practices and also developed some features.

### Corporate Banking
January 2013

I joined the corporate banking team to design and develop this application. We were a Scrum team. Main feature of this project is a workflow helping corporate stakeholders approve money transfers.

## Languages

### Persian
Native proficiency

### English
Professional working proficiency

## Skills & Expertise

* JavaScript
* CoffeeScript
* Node.js
* HTML 5
* Web Applications
* Ajax
* Security
* Agile Methodologies
* Scrum
* Java
* Spring Framework

## Education

### Azad University
Bachelor's degree, Computer Software Engineering  
2003 – 2005

### Qazvin Universoty of Industry Exploration
Associate's degree, Computer Software Engineering  
2000 – 2002
