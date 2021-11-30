# land-magament-fabric-IndianGovt
To create a blockchain network that will help different govt organisations to maintain records and manage operations.

The Blockchain network which we have designed is 

![title](docs/design/network-design.png)

The government maintains multiple types of land records at different Department:
1. Department of Stamps and Registration
2. Department of Revenue
3. Department of Suvery and Mapping. 

The Model bill 2020 propsed by NITI Aayog proposes to create a conclusive land titling system i.e "state guaranteed titles, where the state guarantees the title for its correctness and provides for compensation in case of any disputes" [1]

The bill proposes that each state government creates a new registry where it maintains the ownership record of each land. 

    "Land Authorities to be set up by each State government, which will appoint a Title Registration Officer (TRO) to prepare and publish a draft list of land titles based on existing records and documents." [2]

In this blockchain network we will have two types of channels.
1. Land Managment Channel : Each State government will have its own channel. The land is a subject of state govt and each state government will design department who manage this based on their needs and resources. So each state government will create its own channel. 
2. Authentication Channel using Aadhar : The Unique Identification Authority of India (UIDAI) is a governmment body. UIDAI was created to issue Unique Identification numbers (UID), named as "Aadhaar", to all residents of India. [3] UIDAI is responsible for providing authentication services i.e. help citizen prove who they are to different service providers. 

    For demo purposes we created Land Management with 4 departments, most states have similar departments with slightly different name to manage the land operation.
    1. Department of Stamps and Registration
    2. Department of Revenue
    3. Department of Suvery and Mapping. 
    4. Department of Land Authorities

    Authentication Channel will contain
    1. UIDAI (Unique Identification Authority of India) 



Reference 
 1. Land Records and Titles in India https://prsindia.org/policy/analytical-reports/land-records-and-titles-india
 2. Conclusive Land Titling https://www.drishtiias.com/daily-updates/daily-news-analysis/conclusive-land-titling
 3. About UIDAI https://uidai.gov.in/about-uidai/unique-identification-authority-of-india/about.html#:~:text=The%20Unique%20Identification%20Authority%20of,the%20Ministry%20of%20Electronics%20and 
 