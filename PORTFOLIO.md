<h1> More harm than good
    <br/>
    <span class="subtitle">Questions to ask yourself in text analysis research </span>
    <br/>
    <span class="byline">By Shay Culpepper </span>
</h1>

## Intro
Machine-based text analysis is as pervasive in 2020 as it is impactful. With new open source tools becoming available all the time, anyone is a few lessons away from doing sentiment analysis, topic modeling or creating a chat bot. Currently there are applications in data journalism, digital humanities, language translation, customer service, advertising, criminal justice, search engine optimization and more. The possibilities are limited only by the analyst's imagination. 

The problem is that no one can make a researcher be ethical. There are so few checks and therefore we must police ourselves. In order to avoid missteps, there are many things to ask yourself. Here is a sample list of questions to help your scrutinize your own work.  

However, reality is limited by time and resources. Thorough, representative analysis is simply expensive. It is easier to use someone else's model than create your own, even if it comes from a black box of unsupervised learning. It takes less time to reach for an existing data set even if that data comes exclusively from people who were not aware their text would be analyzed in the way you intend to. It is _easy_ to settle in research. It is _easy_ to take shortcuts. What if researchers refused to? What sorts of objections would be necessary for a researcher to say, "This is not worth it." ([Like that Google ethics researcher](https://www.platformer.news/p/the-withering-email-that-got-an-ethical))


## Definitions
For this paper I use the term text analysis (TA) to describe the general use of computers to analyze text. However, most of my concerns revolve around machine learning applications of text analysis and training sets in particular. These concerns are most relevant to social media. 

[Ethical decision-making in internet research.](http://aoir.org/reports/ethics2.pdf)

## Do you have consent to do this research?
Text data from social media websites such as Twitter or Reddit is often made available via APIs directly from the company. Often you can also obtain social media data via web-scraping. Unfortunately, there is an assumption that because the text is publicly available, it is free game for analysis. Legally, that is often true as most social media companies' terms of service include written consent from the user regarding ownership of their data. However, how many users actually read those? ** TKTK User agreement enforcement ** Furthermore, no written agreement can account for all possible use cases. This creates a [consent](https://epub.wu.ac.at/7523/1/HCIS2020_A%20Human-centric%20Perspective%20on%20Digital%20Consenting_The%20Case%20of%20GAFAM_Soheil%20Human_Florian%20Cech.pdf) gap because the user is not aware of the implications of their data being used in unknown contexts. 

> Subsequently, users are confronted with the necessity to either accept the companies’ terms of services as-is or to undertake the arduous task of choosing when to share which of their private data through web interfaces provided by the data collectors themselves, meaning privacy and cookie consent forms.

The question I am getting at is this: If a social media user knew the intended use of their data, would they be comfortable with it? 

As an example, consider an [authorship attribution study](https://link.springer.com/chapter/10.1007/978-3-642-55415-5_28). In this study Min Yang and Kam-Pui Chow use a blog corpus to test an algorithm intended to aid law enforcement. 

In a related example, consider [plagiarism-detection software](https://academicworks.cuny.edu/gc_pubs/670/). 



[A Human-centric Perspective on Digital
Consenting: The Case of GAFAM](https://epub.wu.ac.at/7523/1/HCIS2020_A%20Human-centric%20Perspective%20on%20Digital%20Consenting_The%20Case%20of%20GAFAM_Soheil%20Human_Florian%20Cech.pdf)

### Have the authors consented to their text to be used in this way?  
Are you respecting the consent given by the text creator to the data provider (e.g. Facebook)? Are you abiding by the terms of the service agreement between you and the data provider (unlike Cambridge Analytica)?

### Are you using data that you [shouldn't actually have access to](https://www.vox.com/2018/3/17/17134072/facebook-cambridge-analytica-trump-explained-user-data)? 
Are you blindly trusting the data provider to be judicious in what have you access to? 
### Are you forgetting to anonymize data? 
TKTKTK

## Is your data representative?
TKTKTK

### Are you accounting for authors of different races and genders in your analysis? Are you treating men or white people as the default and others as outliers/strange? 
TKTKTK Invisible women reference

### Does your model work similarly well on people of various races or genders or is it favored toward a particular gender (usually male) or race (usually white)?
TKTKTK
### Do your models and analysis ignore [African-American Vernacular English](https://www.nytimes.com/2020/03/23/technology/speech-recognition-bias-apple-amazon-google.html)
TKTKTK
### What about about people whose second language is English or who [have a strong accent](https://www.washingtonpost.com/graphics/2018/business/alexa-does-not-understand-your-accent/)? 
TKTKTK
### What about people of different ages or [geographies](https://www.nytimes.com/interactive/2014/upshot/dialect-quiz-map.html)?
TKTKTK




### Are you assuming everyone is only speaking English when you should be adapting to bilingual speakers?
(https://techcrunch.com/2019/09/25/amazon-launches-multilingual-mode-for-using-alexa-in-multiple-languages-at-once/)?



[Mitigating Gender Bias in Natural Language Processing:
Literature Review](https://arxiv.org/pdf/1906.08976.pdf)


"The achievement gap, mass incarceration, and voter apathy are big, nationwide problems that no free market nor mathematical algorithm will fix. So the first step is to get a grip on our techno-utopia, that unbounded and unwarranted hope in what algorithms and technology can accomplish. Before asking them to do better, we have to admit they can’t do everything" - Weapons of Math Destruction, Conclusion

## Are you trying to say more than your data actually  says? 


Have you at any point used the words "revolutionize" or  "disrupt" in talking about your research?

Are you trying to save the world?



Are you trying to make a human, nuanced decision-making process more "objective"? 

TKTKTKTK




## Could your research do harm?

### Are you spying on employees to keep them from unionizing? 
TKTKTKTK



### Can your research or data be weaponized by law enforcement? *** TKTK example of [plagiarism-detection software](https://academicworks.cuny.edu/gc_pubs/670/). 

TKTKTKTK



### Can your research be used to perpetuate and even heighten economic disparities between genders and races? Would 
***TKTK classify your research as a Weapon of Math Destruction because of... ***TKTK


### If your research involves experimenting on human subjects as opposed to simply text analysis, [has your experiment been reviewed by the IRB](https://www.theatlantic.com/technology/archive/2014/06/everything-we-know-about-facebooks-secret-mood-manipulation-experiment/373648/) to  protect your subjects from harm?
TKTKTKTK

<style>
summary {
    margin-bottom: 0.75rem;
}

h2 {
    font-weight: bold;
}
p {
    font-weight: 200;
}
h3 {
    color: #222;
    /* font-style: italic; */
}

.subtitle, .byline {
    font-size: 1rem;
}

.byline {
    font-style: italic;
}
</style>
