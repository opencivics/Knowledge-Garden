---
id: 20241202193228
tags: 
publish:
---

A knowledge commons is a collectively managed resource of knowledge that is accessible to a community or the public. It involves the collaborative creation, sharing, and management of knowledge resources, often emphasizing open access, shared governance, and community involvement.

The purpose of developing a knowledge commons is to support innovation by allowing people to build upon existing knowledge resources.

Examples of familiar knowledge commons include Wikipedia, open academic journals, open source software, public libraries, and data repositories.

The benefits of a knowledge commons:

- **Democratization of Knowledge:** Makes knowledge accessible to a wider audience, breaking down barriers related to cost and exclusivity.
- **Innovation and Creativity:** Encourages innovation by allowing people to build upon existing knowledge and resources.
- **Community Building:** Strengthens community bonds through collective effort and shared goals.
- **Education and Learning:** Provides educational resources that can be freely used and adapted for teaching and learning.

The design principles of an knowledge commons:

- **Accessibility**: Ensuring that resources are easily accessible to everyone, removing barriers to entry and use.
- **Participation**: Encouraging active participation from the community in creating, managing, and using the resources.
- **Collaboration**: Fostering a collaborative environment where users can work together to improve and expand the commons.
- **Sustainability**: Managing the commons in a way that ensures long-term availability and usability of the resources.
- **Equity**: Promoting fair access and representation within the commons, addressing power imbalances and ensuring diverse voices are heard.

### **Knowledge Management Strategy**

With these design principles in mind, an approach to developing an OpenCivic Knowledge Commons prioritizes these considerations and prioritizes low barrier of entry, sovereignty, longevity, and efficient co-management is proposed to be an **open source markdown library.**

Open source markdown libraries use markdown files (.md) to store content. This format is lightweight, human-readable, and easily version-controlled. Files are organized into a clear directory structure that reflects the hierarchy and categories of the knowledge base.

By leveraging markdown files and open-source tools, this approach creates a flexible, scalable, and collaborative knowledge commons that is easy to manage and maintain.

The fundamental structure that enables the open source markdown library to exist is a data protocol and a governance process. The data protocol defines the metadata structure that enables organization and searchability of knowledge resources. The governance process manages updates to the data protocol and provides authority for moderation of knowledge resources where necessary.

The utility of the OpenCivics Innovation Framework relies most-so on the shared data protocol, as a formalization participants opt-into, to optimize for access and interoperability. As the knowledge commons represents an open source data format, there will not be one comprehensive database but many that exist with their own unique configurations.

In addition to governing the articulation of the data protocol format, the OpenCivics Network will also maintain both a database and an interface for accessing a particular instance of the knowledge commons that acts as a primary repository. This particular instance will apply its own version control system, moderation protocols, documentation, and backups.

Maintaining a primary repository is an effort to serve as the authoritative source, promoting consistency, coherence, and coordination among contributors. It provides a unified platform for collaboration, version control, and the integration of changes, facilitating efficient development and management so the knowledge commons remains a vibrant and valuable resource.

### **Data Protocol**

The data structure is intended as an infrastructural foundation for the process of open civic innovation. The following preliminary data structure is intended to align with the grammar introduced by open civic systems and enable both composability of these systems and informed practice. The structure proposed would be managed by a governance process conducted by the OpenCivics Consortium.

The data protocol is composed of:

- Directory structure
- Metadata structure
- Content guidelines
- Contribution process
- Licensing guidelines

### **Directory Structure**

Each folder corresponds to an object template with uniquely defined metadata properties.

- Agency
    - Agents
    - Agencies
- Activities
    - Initiatives
    - Alliances
    - Gatherings
    - Courses
    - Grants
    - Proposals
- Protocols
    - Civic Stacks
    - Civic Scales
- Classifications
    - Innovation Sectors
    - Civic Utilities
    - Civic Systems
    - Civic Scales

### **Metadata Structure**

Each object contains standard metadata of:

- Name/Title
- Author
- Date created
- Tags

Each object template has uniquely defined metadata properties that act as bidirectional links where appropriate (exceptions marked by *).

[ we need to reconcile this table / object type and the directory structure above]

|**Object Type**|**Description**|**Attributes**|**Relationships**|
|---|---|---|---|
|Agent||||
|Agency||||
|Project||||
|Tool||||
|Protocol||||
|Civic Sector||||
|Bioregion||||
|Civic Stack||||
|Gathering||||
|Space||||
|Civic Utility||||

**Content Guidelines**

Content guidelines for entries within the open markdown library are bound by markdown formatting guidelines and general standards that include:

**Clarity and Conciseness**

- Write in clear, straightforward language.
- Avoid jargon and technical terms unless necessary, and provide definitions or explanations when used.
- Be concise; eliminate unnecessary words and information.

**Structure and Organization**

- Use headings and subheadings to organize content logically.
- Break content into short paragraphs and use bullet points or numbered lists for readability.
- Include a table of contents for longer documents.

**Tone and Style**

- Maintain a consistent and professional tone.
- Use active voice where possible.
- Ensure the writing style aligns with the target audience.

**Accuracy and Reliability**

- Verify facts and data before including them.
- Cite reliable sources and provide references.
- Avoid speculation and clearly distinguish between opinion and fact.

**Inclusivity and Accessibility**

- Use inclusive language that respects all readers.
- Ensure content is accessible to people with disabilities, such as providing alt text for images.
- Attempt to use gender-neutral terms and avoid stereotypes.

### **Contribution Process**

Contribution processes will evolve quickly in the establishment and evolution of this knowledge commons, based on the functionality of tooling to support progressive decentralization of governance, detailed attribution and self-sovereign data.

A core intention of the OpenCivics Network instance is the integration of version control systems empowered by git, that both support necessary levels of moderation and remain accessible for those that wish to engage through that medium.

Opportunities for contribution will remain accessible for all users through simple forms that integrate submissions into the primary repository.

### **Interface**

The primary repository managed by the OpenCivics Network will be connected with a public interface that allows users to browse its contents on the web without any specialized tooling. The open markdown library will be compiled as a web interface through the use of a static site generator that converts the active markdown files into a well-structured, searchable website.

Users can both upload any export of the knowledge commons to their client app of choice and/or choose to display the repository on a site of their own – without the need for technical support beyond documentation that guides the user how to conduct an export.

### **Future Technical Stack**

In addition to the increased capacity for coordination between innovators that emerges through formalization of a framework, alignment between technologists and community organizers supports the development of modular and interoperable software that facilitates open protocol discovery, education, and feedback processes. Instead of producing a single, monolithic technology platform to provision the service of open protocols databases and curricula, shared ontological definitions allow technologists to easily transpose and migrate data from one platform to another. Federated wikis are one example of a method that could be utilized to create “flotillas” of open protocol libraries that can be merged by multiple clusters of communities and research initiatives. Drawing inspiration from

[Murmurations Protocol](https://murmurations.network/)

, a distributed data sharing protocol to facilitate collaboration at scale, open protocols can be shared in an open and permissionless structure that supports aggregation, collaboration, and iteration. Linking contact information of specialized trainers, practitioners, facilitators, and designers with the design patterns themselves, the technological interface for open protocol discovery, customization, and iteration supports the education and empowerment of the public to deploy open protocols in their community.