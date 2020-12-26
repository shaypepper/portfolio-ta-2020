<h1> More harm than good
    <br/>
    <span class="subtitle">Questions to ask yourself in text analysis research </span>
    <br/>
    <span class="byline">By Shay Culpepper </span>
</h1>

<h2 style="color: red">***DRAFT***</h2>

## Intro
Machine-based text analysis is as pervasive in 2020 as it is impactful. With new open source tools becoming available all the time, anyone is a few lessons away from doing sentiment analysis, topic modeling or creating a chat bot. Currently there are applications in data journalism, digital humanities, language translation, customer service, advertising, criminal justice, search engine optimization and more. The possibilities are limited only by the researcher's imagination. 

The problem is that there is nothing to compel a researcher to be ethical or thoughtful in the way they source the data. There are few checks and therefore we must police ourselves. In order to avoid missteps, here is a list of questions to help scrutinize your own work.  

[Ethical decision-making in internet research.](http://aoir.org/reports/ethics2.pdf)

## Do you have consent to do this research?
One of the most important aspects of any research is obtaining consent from the creators of the text. Some examples are *clear* violations of consent, such as recording people without their knowledge and analyzing their spoken conversations. Less clear are examples that come from our public use of the internet and social media, in particular. 

Text data from social media websites such as Twitter or Reddit is often made available via APIs from the company. When an API is not available, you also have the option to collect the data via web-scraping. Unfortunately, there is an assumption that because the text is publicly available, it is free game for analysis. Legally that might be true. Most social media companies' terms of service include written consent from the user regarding ownership of their data. However, this is not without it's own ethical considerations.

In a conference paper called "A Human-Centric Perspective on Digital Consenting: The Case of GAFAM", Soheil Human and Florian Cech describe the cognitive load often associated with user consent agreements. 
> [U]sers are confronted with the necessity to either accept the companies’ terms of services as-is or to undertake the arduous task of choosing when to share which of their private data through web interfaces provided by the data collectors themselves, meaning privacy and cookie consent forms.

Users' aversion to this "arduous task" creates a knowledge gap in how their data may be used. Requests for consent can be clicked-through thoughtlessly by the user regardless of what the terms of service are. 

This form of consent falls short of the medical and psychological research standard of informed consent. Informed consent requires the subject to have an understanding of the possible outcomes of the research before consenting. There is no requirement for this level of consent in most text analysis, but it could be used as a guiding light.

In other words, If a social media user knew the intended use of their data, would they be comfortable with it? 

If your research involves experimenting on human subjects as opposed to simply text analysis, [has your experiment been reviewed by the IRB](https://www.theatlantic.com/technology/archive/2014/06/everything-we-know-about-facebooks-secret-mood-manipulation-experiment/373648/) to  protect your subjects from harm?
TKTKTKTK


In a related example, consider [plagiarism-detection software](https://academicworks.cuny.edu/gc_pubs/670/). 


## Legal consent
### Have the authors consented to their text to be used in _*this*_ way?  
Are you respecting the consent given by the text creator to the data provider (e.g. Facebook)? Are you abiding by the terms of the service agreement between you and the data provider?

The [Cambridge Analytica scandal](https://www.nytimes.com/2018/04/04/us/politics/cambridge-analytica-scandal-fallout.html) from the 2016 presidential election is an example of researchers using data in a way that the provider did not intend. In that case, Cambridge Analytica used a lengthy questionnaire to request access to users' Facebook data. From there, the researchers were able to create a map to all of the users' friends and then downloaded all Facebook pages that the friend had "liked". Only the person taking the questionnaire had given consent while the friends had not. This was an abuse of the data available and violated the terms of Facebook's third party data agreement. 

### Are you using data that you shouldn't actually have access to?

It would be reasonable to assume that if a company gives you access to user data, then you are allowed to use that data. Not so. To continue with the Cambridge Analytica example, Facebook had no safeguards to prevent a third party from gathering public page likes and friend networks. When Mark Zuckerberg testified before congress regarding this abuse of user data, he blamed Cambridge Analytica for violating the terms of agreement. Zuckerberg got by without taking responsibility for the data being available in the first place.

Another way to word this question is, "Are you blindly trusting the data provider to be judicious in what you have access to?"

## Potential harm to the "subjects"
### Are you forgetting to anonymize data? 
It is important to not inadvertently reveal information about someone that they have not consented to sharing broadly. Things like names, workplaces or addresses left raw in the data allows interested parties to connect your research to specific individuals. This question is especially important if you are making your data available to other researchers, which is becoming standard practice.  The UK Data Service has a [guide](https://www.ukdataservice.ac.uk/manage-data/legal-ethical/anonymisation/qualitative.aspx) with best practices for anonymizing data.

### Can your research or data be weaponized by law enforcement? *** TKTK example of [plagiarism-detection software](https://academicworks.cuny.edu/gc_pubs/670/). 

As an example, consider an [authorship attribution study](https://link.springer.com/chapter/10.1007/978-3-642-55415-5_28). In this study Min Yang and Kam-Pui Chow use a blog corpus to test an algorithm intended to aid law enforcement. 
TKTKTKTK



## Potential harm to others
### Can your research be used to perpetuate and even heighten economic disparities between genders and races? Would 
From Weapons of Math Destruction, Conclusion:

> The achievement gap, mass incarceration, and voter apathy are big, nationwide problems that no free market nor mathematical algorithm will fix. So the first step is to get a grip on our techno-utopia, that unbounded and unwarranted hope in what algorithms and technology can accomplish. Before asking them to do better, we have to admit they can’t do everything

[Mitigating Gender Bias in Natural Language Processing:
Literature Review](https://arxiv.org/pdf/1906.08976.pdf)

### Are you trying to make a human, nuanced decision-making process more "objective"? 
From [Catherine D'Ignazio and Lauren Klein in The Numbers Donn't Speak for Themselves](https://data-feminism.mitpress.mit.edu/pub/czq9dfs5/release/2#r6073173360) 
> Big Dick Data is a formal, academic term that we, the authors, have coined to denote big data projects that are characterized by patriarchial, cis-masculinist, totalizing fantasies of world domination as enacted through data capture and analysis. Big Dick Data projects ignore context, fetishize size, and inflate their technical and scientific capabilities."


## References
1. Human, Soheil, and Florian Cech. "A Human-centric Perspective on Digital Consenting: The Case of GAFAM." *Human Centred Intelligent Systems.* Springer, Singapore, 2020. 139-159.
2. Perez, Caroline Criado. Invisible women: Exposing data bias in a world designed for men. Random House, 2019.



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
