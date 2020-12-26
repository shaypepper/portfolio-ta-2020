<h1> More harm than good
    <br/>
    <span class="subtitle">Questions to ask yourself in text analysis research </span>
    <br/>
    <span class="byline">By Shay Culpepper </span>
</h1>

## Intro
Machine-based text analysis is as pervasive in 2020 as it is impactful. With new open source tools becoming available all the time, anyone is a few lessons away from doing sentiment analysis, topic modeling or creating a chat bot. Currently there are applications in data journalism, digital humanities, language translation, customer service, advertising, criminal justice, search engine optimization and more. The possibilities are limited only by the researcher's imagination. 

The problem is that there is nothing to compel a researcher to be ethical or thoughtful. There are few checks and therefore we must police ourselves. In order to avoid missteps, here is a list of questions to help scrutinize your own work.  

[Ethical decision-making in internet research.](http://aoir.org/reports/ethics2.pdf)

## Do you have consent to do this research?
One of the most important aspects of any research is obtaining consent from the creators of the text. Some examples are *clear* violations of consent, such as recording people without their knowledge and analyzing their spoken conversations. Less clear are examples that come from our public use of the internet and social media, in particular. 

Text data from social media websites such as Twitter or Reddit is often made available via APIs from the company. You can also obtain social media data via web-scraping. Unfortunately, there is an assumption that because the text is publicly available, it is free game for analysis. Legally, that is often true as most social media companies' terms of service include written consent from the user regarding ownership of their data. However, this is not without it's own ethical considerations.

In a conference paper called "A Human-Centric Perspective on Digital Consenting: The Case of GAFAM", Soheil Human and Florian Cech describe the cognitive load often associated with user consent agreements. 
> Subsequently, users are confronted with the necessity to either accept the companies’ terms of services as-is or to undertake the arduous task of choosing when to share which of their private data through web interfaces provided by the data collectors themselves, meaning privacy and cookie consent forms.

Users' aversion to this "arduous task" creates a knowledge gap in how their data may be used. This form of consent falls short of the medical and psychological research standard of informed consent. Informed consent requires the subject to have an understanding of the implications of the research before consenting. There is no requirement for this level of consent in most text analysis, but it could be used as a guiding light.

In other words, If a social media user knew the intended use of their data, would they be comfortable with it? 

As an example, consider an [authorship attribution study](https://link.springer.com/chapter/10.1007/978-3-642-55415-5_28). In this study Min Yang and Kam-Pui Chow use a blog corpus to test an algorithm intended to aid law enforcement. 

In a related example, consider [plagiarism-detection software](https://academicworks.cuny.edu/gc_pubs/670/). 

### Have the authors consented to their text to be used in this way?  
Are you respecting the consent given by the text creator to the data provider (e.g. Facebook)? Are you abiding by the terms of the service agreement between you and the data provider?

The [Cambridge Analytica scandal](https://www.nytimes.com/2018/04/04/us/politics/cambridge-analytica-scandal-fallout.html) from the 2016 presidential election is an example of researchers using data in a way that the provider did not intend. In that case, Cambridge Analytica used a lengthy questionnaire to request access to users' Facebook data. From there, the researchers were able to create a map to all of the users' friends and then downloaded all Facebook pages that the friend had "liked". Only the person taking the questionnaire had given consent while the friends had not. This was an abuse of the data available and violated the terms of Facebook's third party data agreement. 

### Are you using data that you shouldn't actually have access to?

It would be reasonable to assume that if a company gives you access to user data, then you are allowed to use that data. Not so. To continue with the Cambridge Analytica example, Facebook had no safeguards to prevent this sort of abuse. When Mark Zuckerberg testified before congress regarding this abuse of user data, he blamed Cambridge Analytica for violating the terms of agreement without taking responsibility for the data being available in the first place.

Maybe another way to word this question is, "Are you blindly trusting the data provider to be judicious in what have you access to?" 
### Are you forgetting to anonymize data? 
This question is especially important if you are making your data available to other researchers, which is becoming the standard for academic research. The UK Data Service has a [guide](https://www.ukdataservice.ac.uk/manage-data/legal-ethical/anonymisation/qualitative.aspx) with best practices and what to look out for in anonymizing. 

## Is your data and analysis representative?
There are two sides to the question of representation. First, are your inputs representative?  Does your text come from a good mix of people of different ages, genders and races.

### Are you ignoring race and gender in your analysis? Are you inadvertently treating men or white people as the default and others as outliers/strange? 
TKTKTK Invisible women reference

### Is your model similarly accurate for people of all races and genders or is there a group that is favored?
 Voice recognition is a well known example of where this can go wrong.
 ### Do your models and analysis ignore [African-American Vernacular English](https://www.nytimes.com/2020/03/23/technology/speech-recognition-bias-apple-amazon-google.html)
TKTKTK
### What about about people whose second language is English or who [have a strong accent](https://www.washingtonpost.com/graphics/2018/business/alexa-does-not-understand-your-accent/)? 
TKTKTK


### Are you assuming everyone is only speaking English when you should be adapting to bilingual speakers?
(https://techcrunch.com/2019/09/25/amazon-launches-multilingual-mode-for-using-alexa-in-multiple-languages-at-once/)?



[Mitigating Gender Bias in Natural Language Processing:
Literature Review](https://arxiv.org/pdf/1906.08976.pdf)


TKTKTKTK




## Could your research do harm?

### Can your research or data be weaponized by law enforcement? *** TKTK example of [plagiarism-detection software](https://academicworks.cuny.edu/gc_pubs/670/). 

TKTKTKTK


### If your research involves experimenting on human subjects as opposed to simply text analysis, [has your experiment been reviewed by the IRB](https://www.theatlantic.com/technology/archive/2014/06/everything-we-know-about-facebooks-secret-mood-manipulation-experiment/373648/) to  protect your subjects from harm?
TKTKTKTK


### Can your research be used to perpetuate and even heighten economic disparities between genders and races? Would 
From Weapons of Math Destruction, Conclusion:

> The achievement gap, mass incarceration, and voter apathy are big, nationwide problems that no free market nor mathematical algorithm will fix. So the first step is to get a grip on our techno-utopia, that unbounded and unwarranted hope in what algorithms and technology can accomplish. Before asking them to do better, we have to admit they can’t do everything


## Does your data say as much as you think it can? 

### Are you trying to make a human, nuanced decision-making process more "objective"? 
From [Catherine D'Ignazio and Lauren Klein in The Numbers Donn't Speak for Themselves](https://data-feminism.mitpress.mit.edu/pub/czq9dfs5/release/2#r6073173360) 
> Big Dick Data is a formal, academic term that we, the authors, have coined to denote big data projects that are characterized by patriarchial, cis-masculinist, totalizing fantasies of world domination as enacted through data capture and analysis. Big Dick Data projects ignore context, fetishize size, and inflate their technical and scientific capabilities."



## Conclusion
However, reality is limited by time and resources. Thorough, representative analysis is simply expensive. It is easier to use someone else's model than create your own, even if it comes from a black box of unsupervised learning. It takes less time to reach for an existing data set even if that data comes exclusively from people who were not aware their text would be analyzed in the way you intend to. It is _easy_ to settle in research. It is _easy_ to take shortcuts. What if researchers refused to? What sorts of objections would be necessary for a researcher to say, "This is not worth it." ([Like that Google ethics researcher](https://www.platformer.news/p/the-withering-email-that-got-an-ethical))


## References
1. Human, Soheil, and Florian Cech. "A Human-centric Perspective on Digital Consenting: The Case of GAFAM." Human Centred Intelligent Systems. Springer, Singapore, 2020. 139-159.




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
