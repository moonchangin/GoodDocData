# GoodDocData -- A Template for Simple and Clear Documentation of Hackathon Analyses!

*adapted from [NCBI-Hackathons/GoodDoc](https://github.com/NCBI-Hackathons/GoodDoc) with some tweaks for analysis-driven projects*

*instructions in italics can be deleted as sections are filled in*

*most fields are optional, Conclusion and Important Resources are required*

## Please cite our work -- here is the ICMJE Standard Citation:

### ...and a link to the DOI: *You can make a free DOI with zenodo, synapse, figshare, or other resources <link>*

## Awesome Logo *(if applicable)*
![NF2019](https://s3.amazonaws.com/proddata.sagebase.org/3320015/6b5675a8-2544-437a-bb40-7a3a1769d772/CTFS_in_Cvr%20%286%29.png?response-content-disposition=attachment%3B%20filename%3D%22CTFS_in_Cvr%20%286%29.png%22%3B%20filename%2A%3Dutf-8%27%27CTFS_in_Cvr%2520%286%29.png&response-content-type=image%2Fpng&X-Amz-Security-Token=AgoJb3JpZ2luX2VjEID%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJIMEYCIQCjjxzprIYDBes6mn2Vr38Lt6l3PMOXZENv9iwS%2BAI8EQIhAJgVaf0UM%2FX1gq1I7LE1iaz%2BRzRF3H2WEOWwNUP6V44uKtoDCEgQABoMMzI1NTY1NTg1ODM5IgzYnKNPgsvszo1d4bwqtwM7PmYaGk5826FemIqoCnwe8MYgssoqZ4jDdJ3j7Uk6idqknquQbtKv9YwWR7RCnJ9p2Fcxbx1h3xNgpcFLQAPwgcvX%2BswWG8rkz7MBOYEaQnM3H4Edfz%2BRJWy9e3dAdaZUnqFKlFuxenhp0yrhhnjhzFbgucgzQRIdYm1IYhdYPu10DwtDTF12ojl8mwSrwMh%2FTL2vV20XC3o8zpdxoU%2FJ6yvmFg%2F%2BVFfg6m8puPjZcqRS4Fhyfap3%2FY5QqAp7w5S4sEJapz2ahsroowbuUlMvF6j%2BTHIijPgvDgonTEkZ6C6c9BZhhqd0uLB6JsILuB4%2FtI4UVv72Ip9ZXntl8bZj2Id9CuJ9%2BSaYUJMDrlNZO7Nz01NIQIkTCFt233HVqmDjdRgg2kQYp10DF5i1xcjiVA6DxaZckIT9uAPBjjy6h%2FWktWe3YRSbWZoRX1Xx3HL2PuuOAmhTv8rdRll4k1F6JxCJAHRyjnpLMEvDvR99%2BAAoJ8TrBEH2wunX5phHflMOV5D43VZQPA8zclUYKTia7RpLr%2B5mXXa0EMmU6nGbU1Ksp1v%2FTkfhxAbnRLc%2FppopxlcQjE9gMMSn%2BesFOrMBbikpg1CBOQuACKI7ZB2gUA%2BwDFs2Q%2BjO5GR5wE7WU5af9XLD5qTAAX5O0mN%2BHXL0PRKdcWamJf1ks%2BOfN8bRPeQEagjL1SV%2BGZytpCqCDkp0Z2VpkAvGGK2MRCX1vekcHwQran6yfxmPMvttUBUyDjqfzUnsMQk2AvSDq7sDxFPHrOJHaM%2BK1FotRELXmmmYy1pK%2B%2FpIHYhQ9Mr3QPZMjvG%2BQaAm9WzwQ%2BDGhD%2BvhbJ4vr4%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20190915T165047Z&X-Amz-SignedHeaders=host&X-Amz-Expires=30&X-Amz-Credential=ASIAUXTJYTGXWCCYMMI3%2F20190915%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=b4bf9fe336fa4ea54fde596316868da73dda43d657775b63d08fdcac7c5dae19)

## Website *(if applicable)*

## Abstract *: Summarize everything in a few sentences.* 

## Introduction *: What's the problem? Why should we solve it?*

## Methods *: How did we go about solving it?*

## Results *: What did we observe? Figures are great!*

## Conclusion/Discussion: 

### Please make sure you address ALL of the following:

#### *1. What additional data would you like to have*

#### *2. What are the next rational steps?* 

#### *3. What additional tools or pipelines will be needed for those steps?*

#### *4. What skills would additional collaborators ideally have?*

## Reproduction: *How to reproduce the findings!*

### Docker

*The Docker image contains <R/jupyter> notebooks of all analyses and the dependencies to run them. *Be sure to note if you need any special credentials to access data for these analyses, **don't package restricted data** in your containers!*

Instructions for running the following notebooks: *be sure to adjust these instructions as necessary! check out https://github.com/Sage-Bionetworks/nf-hackathon-2019 for example containers and instructions*

1. `docker pull <your dockerhub repo>/<this container>` command to pull the image from the DockerHub
2. `docker run <your dockerhub repo>/<this container>` Run the docker image from the master shell script

### Important Resources *: primary data, github repository, Synapse project, dockerfile link etc.*


