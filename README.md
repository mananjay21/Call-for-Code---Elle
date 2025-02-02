
# `Community H2H`
**A Smart Natural Resource, Health and Sanitation Monitoring System for Communities**

A brief overview of our idea for the [Call for Code](https://developer.ibm.com/callforcode/) initiative. 

[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Community](https://img.shields.io/badge/Join-Community-yellow)](https://developer.ibm.com/callforcode/get-started/) [![Website](https://img.shields.io/badge/IBM-CallForCode-teal)](https://developer.ibm.com/podcasts/call-for-code-podcast/) 





## :fallen_leaf: Contents :


  - [Short description](#short-description)
    - [What's the problem?](#whats-the-problem)
    - [How can technology help?](#how-can-technology-help)
    - [The idea](#the-idea)
  - [Code Repository](#code-repository) 
 - [Demo video](#demo-video)
  - [The architecture](#the-architecture)
  - [Solution Roadmap](#solution-roadmap)
  - [Getting started](#getting-started)

  - [Built with](#built-with)
  - [Contributing](#contributing)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

## Short description

### What's the problem?

In rural and semi-rural communities, there is a lack of understanding of various diseases and health complications due to water contamination and improper sanitation. As a result, millions of children lose their lives each year across the planet, teenagers and adults get diseases that they carry for the rest of their lives, and environmental damage. Due to improper exclusion and timely quarantines, from a few people, entire communities may be affected. It may be from air & plasma borne diseases like COVID19, Influenza, Tuberculosis, and water-borne diseases like Arsenic Pollution, Typhoid, Dysentry and Hepatitis.

### How can technology help?

With modern technology, combining IoT, Advanced Algorithms, Machine Learning and Smart-Interaction methods with Artificial Intelligence, the diseases can be prevented by imposing smart sanitation systems to improve hygiene and community-symptoms monitoring systems. Smart Sanitation can also have an added advantage, methods to save and control unnecessary water wastage, thus improving the ecological balance.

### The idea

The idea is to set up smart-community hubs across multiple physical locations with an interactive system to govern the area. It will do the following :
1) Monitor the water sources with smart sensory data
2) Maintain water analysis reports and trigger a response if threshold is crossed
3) Keep an average population count of the blocks of communities assigned per community hub
4) Keep solo count of disease symptoms reported regularly at every block and raise alarm if threshold goes above a pre-determined level. 
5) The nearest health centre will be informed on an urgent basis and a containment team and doctors will be allocated. 

`Explanation --Say a person from Block A reported of Nausea, Vomiting and Severe Diarrhea on Jan 01. On the next couple of days, similar reports from that particular block/community started to get logged into the system. The system will immediately go into SOS mode, validate the sensory data, water quality at sources, and trigger a response to the controller for immediate remedial action. This will prevent pandemics even before things get really serious. This is a great way to ensure preventative measures to ensure and control sanitation quality across large communities. `

This is a general explanation of the idea. Implementation will be using sensory data, population datasets, realtime water source monitoring, machine learning for predictions and Artificial Intelligence for approximating the disease or problem that might be occuring in the blocks/communities it is responsible for monitoring.

## Demo video

[![Watch the video](https://github.com/DeepprabhaMalviya/Call-for-Code---Elle/blob/main/images/vidprev.png)](https://youtu.be/7VVVswdY-E8)

## The architecture

1. The data sensors monitor the water quality in the area.
2. The Watson Machine Learning system collects the latest updated data of resouce quality and human health to process a trigger of locally occuring outbreak
3. IBM API Connect is implemented and the authorities are informed for instant remediation.
4. The community is saved from an epidemic and this is vital for controlling deadly diseases.


## Solution Roadmap

See below for our proposed schedule on next steps after Call for Code 2021 submission.

![Roadmap](./images/newimages.jpg)

## Getting started

We are readying the system for deployment. This section will be updated shortly.

- [Watch one of India's Smart Villages in the meantime](https://www.youtube.com/watch?v=TR2zWze-Te4&ab_channel=AmritVatsaAmritVatsa)

## Code Repository

We will be using this operation dashboard system for the solution. [Official Repo Link](https://github.com/IBM/osipi-monitor-integration).

## Built with

- [IBM Watson](https://cloud.ibm.com/catalog/services/machine-learning#about) - The Machine Learning Tool by IBM
- [IBM Cloud Functions](https://cloud.ibm.com/catalog?search=cloud%20functions#search_results) - The compute platform for handing logic
- [IBM API Connect](https://cloud.ibm.com/catalog?search=api%20connect#search_results) - For controlling the event driven logic, i.e. the triggers to be sent to authorities
- [NodeRED](https://developer.ibm.com/components/node-red/) - For connecting the sensory data and validation


## Contributing

Currently, the project is in development stage and noble ideas are always welcome. We can make a long lasting impression on our society by joining hands and pledging for a better future. 

###### Read the official Call For Code FAQ [here](https://callforcode.org/faq/).

## Authors

  <img src="https://raw.githubusercontent.com/DeepprabhaMalviya/Call-for-Code---Elle/main/images/bannerimg.png" />

    # We are Team Elle. We started at Institute of Engineering & Management, Kolkata.
	We are 5 friends with one target ->  #"To change the world for a greater good"
	
	Deepprabha Malviya -> [Leader]
    Kajal Singha -> [Research and Quality Control]
    Ruchira Biswas -> [Technical Feasibility Analysis]
    Aditya Kundu -> [Technical Developer]
    Mananjay Roy -> [Technical Developer]
	
	# You can find us in the classroom of 3rd Year's Section B, Department : CSE
	
`Team Mentor : Tuhinadri Banerjee [IEM CSE 3rd Year] # IoT & IBM Cloud Technology Guide`
## License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special Thanks to [IBM](https://www.ibm.com/in-en) for providing the Cloud Platform and valuable resources for this challenge.
- [Women in Technology (WiT)](https://wit-ace.com/) , India for enabling us to participate for a noble cause.
- Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth).
- Video Source : [Pexels](https://videos.pexels.com/)
- Background Audio :  [YouTube](https://www.youtube.com/watch?v=azNw-vQhAXQ&vl=en)

Punch Deck - Brahe" is under a Creative Commons (cc-by) license Music promoted by BreakingCopyright



