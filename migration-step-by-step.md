# Migration, Step by Step

### Communicating the change

In order to reduce the impact of resistance to change, it is important to start the migration project with a communication activity targeted at the entire organization \(and not only to future users of LibreOffice\). In fact, migrating to LibreOffice is a strategic move for the organization, and should be communicated with the same emphasis as any other strategic decision.

When the migration process starts, all managers and employees should be familiar with the rationale behind the decision to migrate to LibreOffice \(lower TCO and independence from vendor lock-in\), and with LibreOffice \(history of the project, software features, potential interoperability issues, and so on\). It should be clear for everyone that LibreOffice is a viable replacement for Microsoft Office, which has already been implemented on million of desktops worldwide.

### Starting the migration process

Once the analysis of the existing situation \(in terms of third party applications, templates and macros to migrate\) has been completed, it is possible to start the process by implementing an impact test, which is supposed to help find all of the problems that could affect the migration, and ensure that document workflow and interoperability work as intended. Although LibreOffice is, to a very large extent, fully compatible with MS Office, it is a different application with specific strengths and drawbacks, and might trigger specific workflow and interoperability issues.

The participants to the impact test should be representative of the entire organization workflow, and should be trained on LibreOffice \(or have access to trained personnel\).

The impact test has a couple of key objectives:

* Identifying critical documents, templates and macros: a good deal of existing documents, templates and macros might not be in use, or will have outlived their usefulness after your move to LibreOffice. Documents and templates that are still in use should be converted to the standard ODF format, while macros should be re-created using the appropriate technology.
* Creating an inventory of tools and MS Office dependent applications, which are quite frequent in CRM and ERP environments. These applications need to be identified and checked for compatibility with LibreOffice, as the new features might offer an alternative solution \(such as CMIS connectivity\). Questionnaires given to team leads or group managers can be used to get a better insight into how the business solutions interact with MS Office.

To minimize support calls and maximize productivity from the start, it is highly advisable to prepare a "welcome" package for users, with supplementary information about LibreOffice, highlighting the basic functionality of the software and the few specific functional differences with MS Office.

### Switching to open document standards

It is also important to switch immediately to the standard ODF format for all documents, and resort to legacy or current MS Office document formats only to exchange files with users of the proprietary office suite. File sharing is a crucial issue, because it is essential to be able to develop and exchange information effectively. Using ODF as the default document format helps organizations to establish a repository for all information assets, guaranteed against obsolescence and vendor lock-in.

In addition, MS Office is able to read and write ODF format since version 2007, although with several important exceptions, especially in the case of spreadsheets, up to version 2013 \(which supports the reference implementation of ODF 1.2\). Also, if the other party does not have LibreOffice and only needs to read or print the document, this can be exchanged in PDF format \(in this case, using the Hybrid PDF format gives LibreOffice an edge over any other office suite, as the document retains the formatting\).

Of course, choosing the interoperability format for each document might result in an overload and be considered an unnecessary nuisance for the average user, but is a key factor for liberating both the user him/herself and the organization from the constraints of proprietary formats developed by software vendors to perpetuate lock-in. Users and organizations should always remember that closed document formats are limiting not only their freedom but also the ownership of their information assets.

### Identifying "technology leaders" within the organization

Once the impact test and the migration to ODF are in place, it is the right time to identify "technology leaders" within the organization: they are the individuals who are recognized by their peers for their tech competence. For instance, they are the ones who are asked about the latest and greatest smartphone or PC to buy, and about the sexiest applications to use.

"Technology leaders" will have a key role in the migration process, as they will become the LibreOffice evangelists and act as the first contact point for providing simple support to users. The role and efforts of the "technology leaders" should be recognized, supported and encouraged through appropriate incentives by the organization's management.

Once the "technology leaders" have been identified, it will be necessary to organize a small number of LibreOffice briefing sessions targeted mainly at senior and middle management, the IT Support team and the "technology leaders". The briefings are intended to achieve the required buy-in of LibreOffice and motivate the decision makers and the opinion leaders about the migration process.

Once the key stakeholders are convinced, they will be able to inform their staff about the migration process and to encourage them to adopt LibreOffice as early as possible after training and installation.

The first group of "technology leaders" should include - if possible - a mix of middle managers and employees in order to penetrate into the different layers of the organization. The group will meet regularly during all the stages of the migration process, to share the different experiences and identify solutions to common issues.

### Providing training and support

A comprehensive training on LibreOffice - characteristics, advantages, features, peculiarities, and main differences with MS Office - is a fundamental step for any migration project. Training, at different levels, should be provided to IT personnel, trainers, "technology leaders", middle and upper management, and all end users.

Another objective of the training process is to make users aware of the rationale and objectives of the migration project, so that it is not perceived as a mere solution to budget-related issues. In fact, migrating to LibreOffice offers the opportunity of adopting a truly open and standard format, intended to protect the freedom of each individual's creative work and contribute to the growth of a Free Software project which is beneficial to the user community at large \(beyond any kind of border\).

Users, including middle and upper managers, should be segmented for technical skills, training needs and organizational units. These groups form the basis for planning the implementation phase of the migration, so that the transition takes place in homogeneous steps \(to avoid fragmentation\).

Trainings will also be instrumental for the development of a technical support team, which is another crucial element for the success of the migration project. In fact, when the "technology leaders" - who  provide first-hand support to colleagues - are not able to provide an answer to issues arising within their department, the problem should always be escalated to first level support and if necessary to second level support \(which might be internal or external, according to needs\).

In order to assist users, the entire support team will work together to compile a list of Frequently Asked Questions \(FAQ\) as a quick reference for future needs. This FAQ, together will all the documents used during the migration process - especially presentations and manuals - should be published online onto the organization's website, for easy access and retrieval.

### Deploying LibreOffice on every personal computer

The deployment of LibreOffice on every personal computer, including those of users who have been authorized - for specific technical reasons - to keep on using MS Office, needs to be planned in advance and should be coordinated with the training schedule, in order to ensure that users will be able to use the software as soon as possible \(ideally, after the first training session\).

The deployment method can be identified and selected based on the characteristics of the organization's IT infrastructure. LibreOffice can be mass-deployed inside a large organization using Windows desktops by tweaking the .msi package with the help of a MSI editor such as InstEd, and then by creating a Group Policy Object \(GPO\) to distribute the software package.

Deploying LibreOffice, though, does not mean eradicating MS Office from each and every PC. The goal is to maximize the number of PCs using LibreOffice, and to foster the interoperability with MS Office by identifying areas where the latter - for obvious reasons - tries to perpetuate lock-in. For instance, it will be necessary to educate MS Office users - who, at the end of the migration, should not exceed 20% of all users \(as this is the highest potential percentage of people using MS Office-specific features in corporate environments\) - to replace proprietary fonts with free fonts \(such as those backed by the SIL Open Font License\).

