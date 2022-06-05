<c><h2>A Prototype Rainforest Information System: to reduce the cost and increase the accessibility of technology to improve the collection of field data from tropical rainforest environments.</h2></c>
  
  <c>“Over half of the world’s plants and animal species are found in the rainforests, 99% of them have still to be studied by science.” </c>
<c> - Eden Project, Rainforest Biome. </c>

<c><h3>Abstract / Summary</h3></c>

<c>A Bsc Computing and Information Systems project to detail the current innovations and to attempt to improve the current limitations of tropical Rainforest Information Systems (RIS) including reducing their cost and increasing the accessibility of technology for tropical rainforest scientific field research, forestry, data collection and visualisation of field recorded sensor readings. </c>

<c><h3>...</h3></c>

Rainforests can be inaccessible, their mystery, extensive biodiversity of species, and extreme conditions
make rainforests areas of great, and challenging, scientific research. Technologies used in the rainforests
have to be designed to span the vastness of these forests, record their complexities and resist and perform
in intense tropical rainforest conditions.
From research into the current state and context of innovations and systems that meet these core
requirements, and comparing the performance, cost and accessibility of the existing systems, their
software, hardware, and recognizing that most of the world's tropical rainforests are found in developing
countries, it was determined that recycled devices such as smartphones and tablets, due to their
prevalence, ubiquity, mobility, familiarity, and their conveniently builtin array of environmental sensors,
networking hardware, protective casing and being well tested in a range of operating conditions could be
a viable, low cost, accessible, easy to deploy and use, alternative to the high cost, complex, high
precision, high barrier of entry, well funded scientific and Forestry Information System (FIS) technologies
that exist with their own strengths and limitations.
The project aims to measure the feasibility of using recycled hardware and open source software as part of
a low cost, easy to use, robust prototype RIS to retrieve scientifically useful information easily and at a
low cost when conducting field research in the world's tropical rainforests and in tropical rainforest
conditions.
The project report documents the research, design, development, software code, testing, field trials,
evaluation and user feedback for the feasibility, cost, accuracy and availability of using open source
software and recycled hardware in the prototype RIS. The complete prototype is made with a 2013
Samsung Galaxy S4 smartphone and a 2012 Google Nexus 7 tablet, a 15w solar panel and a 9000 mAh
power bank.
A client smartphone Java Android application serves as a reasonably reliable automated data-capturing
TPS (Transaction Processing System) Input Component of the RIS, that automates the data collection
from the currently implemented device’s inbuilt sensors, including, GPS, temperature, humidity and
timestamps at 15 minute intervals that can store the field data offline and network data to the Central
processing and Data storage component; a Java Springboot web server and Docker based Postgres
database using a GSM or wireless Internet connection.
Retrieved data hosted from the server is then visualizable on the Output Component’s presentation
dashboard web page by mapping the GPS coordinates and sensor readings on an interactive 3D globe
with customizable map overlayers including satellite and road.
The complete system is durable and portable and can be taken into the field with the server running on a
full desktop distribution of Linux running on a modified 2012 Google Nexus 7 tablet as an ‘in-the-field
laptop’ hosting the server and database and making available the stored field data with a HTTP RESTful
API.
MarkAnthonyStart_CO3320_FinalProjectReport
Page 6 of 157.University of London: International Programs - Final Project Report
Mark Anthony Start
The system can be powered by a 15w solar panel and power bank and with the right management of its
operation and power reserves can be powered without interruption.
Accuracy of the input component’s sensors were tested and evaluated and shown to be reasonable for the
humidity sensor and quite accurate for the temperature sensor in comparison to online weather services
and a commercially available device with the same set of inbuilt sensors. GPS coordinates ranged from
exact to within a variance of ~50-100 metres of their true location with reliable timestamps but with some
anomalous time and date values.
The overall cost of the prototype was very low and the accessibility of the system evaluated to be high in
comparison to the technologies of the researched scientific, academic and commercially available
systems.
The feasibility of the performance of using recycled devices was also found to be high but necessitates
adaptable, modular and extendible design and engineering principles, project methodology, system
architecture and an iterative development cycle based on testing results and user feedback to enable
continuous development to more closely align with the identified primary and secondary requirements of
the system formalised from the literary review and to improve the systems performance and accuracy of
its components based on user feedback and testing results.







![Project Management Plan](https://user-images.githubusercontent.com/45234288/101823315-7acb4200-3b22-11eb-9848-c815d0ca624e.png)


