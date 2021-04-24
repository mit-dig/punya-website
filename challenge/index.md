---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: challenge
---

<!-- Overview -->

<section id="overview" markdown="1">

# Overview

<div class="row">
<div class="span12" markdown="1">
Mobile apps have become ubiquitous. However, many of them do not fully leverage the advanced capabilities of smartphones, including connectivity, sensors, and processing power. In part, this is due to online data, services, and IoT devices existing within silos and isolated ecosystems even in case the data, service, or device is freely accessible, they are often outfitted with discordant schema or protocols, making it difficult to tie them into an app. Moreover, to add expert system-like intelligent features, such as decision support or context-sensitive recommendations, one has to manually program complex applicationlogic. We posit that Semantic Web technologies, by virtue of domain ontolo-gies and semantic representation formalisms, can help overcome the difficultyof building interoperable, intelligent, and fully-fledged mobile apps.

[Punya](https://punya.mit.edu){:target="_blank"} is a drag-and-drop visual programming environment based on [MIT App Inventor](https://appinventor.mit.edu){:target="_blank"} that incorporates many semantic technologies, intending to democratize the ability to consume, produce, and act on Linked Data. One can build apps that consume Linked Data by querying a remote [SPARQL](https://www.w3.org/TR/sparql11-query/){:target="_blank"} endpoint, and generate Linked Data through forms annotated with a domain ontology. The framework embodies advanced Linked Data features that make the most use of mobile capabilities including the _Constrained Application Protocol_ extension for [Linked Data Platform (LDP-CoAP)](http://sisinflab.poliba.it/swottools/ldp-coap/){:target="_blank"} and rule-based semantic reasoning.
</div>
</div>

</section>

<!-- Task Description -->

<section id="task" markdown="1">

# Task Description

<div class="row">
<div class="span12" markdown="1">
Participants will build an intelligent mobile app using the __Punya__ framework that connects with online Linked Data sources and services, nearby IoT devices or on-device sensors, and/or implement expert system features, by producing, consuming, and processing Linked Data. 

To that end, participants may extend the Punya framework itself with new Linked Data components, or extend existing ones. The challenge participants will be expected to utilize at least two Punya __Linked Data__ components, which currently include the:
* ``LinkedDataForm``
* ``LinkedDataListPicker``
* ``Reasoner``
* ``LdpCoapClient``

Apps should tackle relevant and challenging __real-world scenarios__ that impact health, the environment, and society. The list of suggested themes includes Linked Data for:
* Social Good
* Better Resource Allocation (e.g., water scarcity,natural disaster response)
* Climate Change
* Ending Poverty
* Health Care (e.g.,COVID-19, mental health)
* Learning and Working Remotely
* Living Together
* Active Aging
* Social and Racial Justice
* Social Impact of Artificial Intelligence (e.g., biases, opportunities, equitability)

The apps developed will need to present end-user interactions, providing an adequate and usable interface that favors concrete usage. 
We require the challenge participants to provide:
* a 2-minute video demo for the judges;
* the .aia file of their mobile app that can be loaded into the Punya MIT App Inventor endpoint at [http://punya.appinventor.mit.edu](http://punya.appinventor.mit.edu){:target="_blank"};
* an extended abstract briefly describing the contribution. Submissions must be in English, no longer than 4 pages (including references), and formatted in the style of the Springer Publications format for Lecture Notes in Computer Science (LNCS). For details on the LNCS style, see [Springer’s Author Instructions](https://www.springer.com/gp/computer-science/lncs/conference-proceedings-guidelines){:target="_blank"}.

If the app developers have extended Punya features for their app, they must make the software __open source__ under the [Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0){:target="_blank"}. It is preferred if the data used to demonstrate the app is publicly made available, but at the very least, the data must be available to the challenge organizers and judges.
</div>
</div>

</section>

<!-- Important Dates -->

<section id="timeline" markdown="1">

# Important Dates

<div class="row">
<div class="span12" markdown="1">
The challenge timeline is composed of the following tasks. We will require all participants to check-in a month before the deadline to make sure their development efforts are in line with the challenge expectations.

<style type="text/css">
.tg  {border-collapse:collapse; border-spacing:0;}
.tg td {padding:10px 5px; word-break:normal;}
</style>
<table class="tg">
<tbody>
  <tr>
    <td>Check-in of Mobile Apps with Challenge Organizers</td>
    <td>15 June 2021</td>
  </tr>
  <tr>
    <td>Submission of Mobile Apps</td>
    <td>15 July 2021</td>
  </tr>
  <tr>
    <td>Notification of System Results</td>
    <td>15 August 2021</td>
  </tr>
  <tr>
    <td>Participation Invitations to Present at ISWC2021</td>
    <td>15 August 2021</td>
  </tr>
  <tr>
    <td>Challenge Presentations</td>
    <td>24-28 October 2021</td>
  </tr>
</tbody>
</table>
</div>
</div>

</section>

<!-- Resources: Software & Tutorials -->

<section id="resources" markdown="1">

# Punya resources

<div class="row">
<div class="span12" markdown="1">
The Punya open-source code repository is available at [https://github.com/mit-dig/punya](https://github.com/mit-dig/punya){:target="_blank"}. 

We also have extensive documentation on the Punya components at [https://punya.mit.edu](https://punya.mit.edu){:target="_blank"}. 

### Learning materials

Several of the challenge organizers ran a successful tutorial titled __“Building Mobile Semantic Web Appswith Punya”__ at _ISWC 2020_, and the tutorial material is available at [https://punya2020.appinventor.mit.edu](https://punya2020.appinventor.mit.edu){:target="_blank"}. 

This material will help guide participants through the use of Punya for building complex and intelligent mobile apps, as it outlines the use of the Punya Linked Data components in real-world scenarios. Mobile apps developed as part of this challenge may leverage existing online Linked Data (e.g., Wikidata, DBPedia, Bio2RDF) or put online their own queryable Linked Data.

According to the ISWC 2020 material, Punya also includes the following built-in tutorials for learning how to build Linked Data-aware mobile apps:
* [RDF Notepad](http://punya.appinventor.mit.edu/?repo=RdfNotepad){:target="_blank"}: 
basics of using the ``LinkedDataForm`` to construct and edit RDF graphs and reading and writing of RDF using the ``LinkedData`` component;
* [Sleep Apnea](http://punya.appinventor.mit.edu/?repo=SleepApnea){:target="_blank"}: write rules in Punya and use them to reason about RDF data exploiting the ``Reasoner`` component;
* [LDP-CoAP sensing app](http://punya.appinventor.mit.edu/?repo=LdpCoapTutorial){:target="_blank"}: share device sensors data in Semantic Web of Things scenarios using the ``LdpCoapClient``.

Further information is available on the [Punya use cases](https://punya.mit.edu/#use-cases){:target="_blank"} section.

### MIT App Inventor community

Because Punya is built on _MIT App Inventor_, partecipants can tap into a large community of app developers worldwide (1,967 active community members in the 30 days ending April 1, 2021, and almost 900,000 yearly active users): [https://community.appinventor.mit.edu](https://community.appinventor.mit.edu){:target="_blank"}.

</div>
</div>

</section>

<!-- Evaluation -->

<section id="evaluation" markdown="1">

# Evaluation

<div class="row">
<div class="span12" markdown="1">
A panel of senior Semantic Web and mobile application researchers will judge the submitted apps. 
We have invited senior leaders, scientists, researchers, and highly reputed managers with expertise in the Semantic Web and/or mobile computing communities to be in the panel of judges. Already confirmed members include:

* [Fernando Bobillo](http://webdiis.unizar.es/~fbobillo/){:target="_blank"}, Associate Professor of Artificial Intelligence - Universidad de Zaragoza, Spain
* [Amélie Gyrard](https://fr.linkedin.com/in/amélie-gyrard-3a94613b){:target="_blank"}, IoT Semantic Interoperability Researcher - Trialog, Paris, France
* [James A. Hendler](https://faculty.rpi.edu/node/36225){:target="_blank"}, Professor of Computer, Web and Cognitive Sciences - Rensselaer Polytechnic Institute, Troy, NY, USA
* [Roberto Mirizzi](https://www.linkedin.com/in/robertomirizzi){:target="_blank"}, Vice President of Engineering - Machine Learning, Personalization, Recommendation, Search - Discovery, Inc., Bellevue, WA, USA
* [Enrico Motta](http://people.kmi.open.ac.uk/motta/){:target="_blank"}, Professor of Knowledge Technologies - KMi, The Open University, Milton Keynes, UK
* [Vito C. Ostuni](https://www.linkedin.com/in/vito-claudio-ostuni-0b576027){:target="_blank"}, Senior Research Scientist - Recommendation and Search - Netflix, Inc., Los Gatos, CA, USA
* [Michele Ruta](http://sisinflab.poliba.it/ruta){:target="_blank"}, Professor of Information Systems - Polytechnic University of Bari, Italy
* [Juan Sequeda](https://juansequeda.com){:target="_blank"}, Principal Scientist - data.world, Austin, TX, USA
</div>
</div>

</section>

<!-- Organizers -->

<section id="organizers" markdown="1">

# Challenge Organizers

<div class="row">
<div class="span12" markdown="1">
* [Oshani Seneviratne](https://idea.rpi.edu/people/staff/oshani-seneviratne){:target="_blank"} - Rensselaer Polytechnic Institute, USA
* [Lalana Kagal](https://www.csail.mit.edu/person/lalana-kagal){:target="_blank"} - Massachusetts Institute of Technology, USA
* [Giuseppe Loseto](http://sisinflab.poliba.it/loseto){:target="_blank"} - Polytechnic University of Bari, Italy
* [Evan W. Patton](https://www.csail.mit.edu/person/evan-patton){:target="_blank"} - Massachusetts Institute of Technology, USA
* [Floriano Scioscia](http://sisinflab.poliba.it/scioscia){:target="_blank"} - Polytechnic University of Bari, Italy
* [William Van Woensel](https://niche.cs.dal.ca/william-van-woensel){:target="_blank"} - Dalhousie University, Canada 

For any information, please contact the challenge organizers.
</div>
</div>

</section>
