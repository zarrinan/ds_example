---
layout: post
title: Sci-fi books influence on tech development
---

Sci-fi books have been a great influence on tech, ai, robotics industries of the 21st century. Sci-fi authors, dreaming of the future, had a great impact on the tech development of their countries. 
 
 In my project, I'm going to explore if the number and the main story content of sci-fi books, correlated with the countries' development in tech. 
I will also explore the popularity of a specific content for countries, decades, and also, based on an author's gender. I will analyze if some contents are often found together in sci-fi books, or if some author pioneered some content more than once. 

For every country, I'll compare the number and the most popular story content of sci-fi books with a size of the tech industry (or, high-tech exports),  and the number of tech patents per capita. 


For my project, I'm planning to use a dataset by Kathleen M. Carley(2017). [Sci-Fi Books data set](http://www.casos.cs.cmu.edu/tools/datasets/internal/index.php). Retrieved from http://www.casos.cs.cmu.edu/tools/datasets/internal/index.php This dataset contains information a book's year, author, author's gender, content of story.

Potentially, I might also use the following [dataset](https://github.com/zygmuntz/goodbooks-10k), which containts information for 10000 books of mixed genre. I found on github. It will require more cleaning and feature engineering.

World Bank [data](https://data.worldbank.org/indicator/NV.MNF.TECH.ZS.UN) on tech industry sizes per country with latest data for 2015 year.

I might also use the tech patents [data](https://www.wipo.int/ipstats/en/) from World Intellectual property organization.


#### To get started with my project, I'd:

1. Explore more datasets on the subject;

2. Create a single dataset on sci-fi books from different sources;

3. To the existing dataset, I'd add author's country.


#### To hit my projet's MVP, I'd:

1. Explore the popularity of a specific content throught the century and through the decades;

2. Explore the popularity of a content based on an author's gender;

3. Explore the popularity of a content based on an author's country;

4. Explore if some author was pioneering a specific content more than one time;

5. Explore if some contents are often found together in sci-fi books; 

6. Explore, if the number of sci-fi books written in a specific country is correlated with tech development in that country (and I'd need and additional dataset on countries level of development in tech);

7. As a continuation of the previous item, if the number of sci-fi books written in a specific country is correlated with tech patent numbers in that country (and I'd need and additional dataset on tech patent numbers for countries); 

#### When I'm done with MVP, I'd:

1. Train NN on the books content:

- To find out the most popular phrase/ word for all books and for a specific genre;
- For sentiment analysis based on genre, decade, country, aouthor's gender;
- To predict if a specific typed phrase would belong to some author.


