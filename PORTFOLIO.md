<h1> More harm than good
    <br/>
    <span class="subtitle">Questions to ask yourself in text analysis research </span>
    <br/>
    <span class="byline">By Shay Culpepper </span>
</h1>

<h2 style="color: red">***DRAFT***</h2>

Work from the semester can be found [here](https://www.dropbox.com/personal/Culpepper)
## Intro
Machine-based text analysis is as pervasive in 2020 as it is impactful. With new open source tools becoming available all the time, anyone is a few lessons away from doing sentiment analysis, topic modeling or creating a chat bot. Currently there are applications in data journalism, digital humanities, language translation, customer service, advertising, criminal justice, search engine optimization and more. The possibilities are limited only by the researcher's imagination. 

The problem is that there is nothing to compel a researcher to be ethical or thoughtful in the way they source the data. My primary concern in this paper is the question of consent. 
## Do you have consent to do this research?
One of the most important aspects of any research is obtaining consent from the creators of the text. Some examples are *clear* violations of consent, such as recording people without their knowledge and analyzing their spoken conversations. Less clear are examples that come from our public use of the internet and social media, in particular. 

Text data from social media websites such as Twitter or Reddit is often made available via APIs from the company. When an API is not available, you also have the option to collect the data via web-scraping. Unfortunately, there is an assumption that because the text is publicly available, it is free game for analysis. Legally that might be true. Most social media companies' terms of service include written consent from the user regarding ownership of their data. However, this is not without it's own ethical considerations.

In a conference paper called "A Human-Centric Perspective on Digital Consenting: The Case of GAFAM", Soheil Human and Florian Cech describe the cognitive load often associated with user agreements. 
> [U]sers are confronted with the necessity to either accept the companies’ terms of services as-is or to undertake the arduous task of choosing when to share which of their private data through web interfaces provided by the data collectors themselves, meaning privacy and cookie consent forms.

Users' aversion to this "arduous task" creates a knowledge gap in how their data may be used. Requests for consent can be clicked-through thoughtlessly by the user regardless of what the terms of service are. This falls short of the medical and psychological research standard of informed consent. 

Informed consent has a few requirements (Brody 1997). For example, the participant should understand what the study will involve and potential outcomes and risks. It also requires that the participant is not compelled or pressured to give consent.  

Questions are currently being asked with regard to health databases and what obligations researchers have to the people who have consented to include their medical information.  (Bromley et al. 2020).  

In 2014 Facebook conducted an experiment on its users to test their emotional reaction to being shown happy or sad posts (Confessore). They used sentiment analysis to choose which posts to show or hide and then measured whether or not the participant's mood had shifted. The study was conducted without the consent of the participants that would reach the standard of "Informed Consent". When it became public that Facebook had been unknowingly experimenting on its users, the backlash was swift from social scientists. Typically, if your research involves experimenting on human subjects, your experiment should be been reviewed by an Institutional Review Board in order to evaluate potential ethical problems or harm. Max Masnick summed up the criticism in a blog post with this: "As a researcher, you don’t get an ethical free pass because a user checked a box next to a link to a website’s Terms of Use." 


In a related example, consider [plagiarism-detection software](https://academicworks.cuny.edu/gc_pubs/670/). 


## Legal consent
### Have the authors consented to their text to be used in _*this*_ way?  
Are you respecting the consent given by the text creator to the data provider (e.g. Facebook)? Are you abiding by the terms of the service agreement between you and the data provider?

The [Cambridge Analytica scandal](https://www.nytimes.com/2018/04/04/us/politics/cambridge-analytica-scandal-fallout.html) from the 2016 presidential election is an example of researchers using data in a way that the provider did not intend. In that case, Cambridge Analytica used a lengthy questionnaire to request access to users' Facebook data. From there, the researchers were able to create a map to all of the users' friends and then downloaded all Facebook pages that the friend had "liked". Only the person taking the questionnaire had given consent while the friends had not. This was an abuse of the data available and violated the terms of Facebook's third party data agreement. 

### Are you using data that you shouldn't actually have access to?

It would be reasonable to assume that if a company gives you access to user data, then you are allowed to use that data. Not so. To continue with the Cambridge Analytica example, Facebook had no safeguards to prevent a third party from gathering public page likes and friend networks. When Mark Zuckerberg testified before congress regarding this abuse of user data, he blamed Cambridge Analytica for violating the terms of agreement. Zuckerberg got by without taking responsibility for the data being available in the first place.

Another way to word this question is, "Are you blindly trusting the data provider to be judicious in what you have access to?"

## Potential harm to the end-users
### Are you forgetting to anonymize data? 
It is important to not inadvertently reveal information about someone that they have not consented to sharing broadly. Things like names, workplaces or addresses left raw in the data allows interested parties to connect your research to specific individuals. This question is especially important if you are making your data available to other researchers, which is becoming standard practice.  The UK Data Service has a [guide](https://www.ukdataservice.ac.uk/manage-data/legal-ethical/anonymisation/qualitative.aspx) with best practices for anonymizing data.
<!--
### Can your research or data be weaponized by law enforcement? *** TKTK example of [plagiarism-detection software](https://academicworks.cuny.edu/gc_pubs/670/). 

As an example, consider an [authorship attribution study](https://link.springer.com/chapter/10.1007/978-3-642-55415-5_28). In this study Min Yang and Kam-Pui Chow use a blog corpus to test an algorithm intended to aid law enforcement. 
TKTKTKTK
-->

## Potential harm to others
Most people would not consent to their data being used to harm others. In getting consent, future potential harm is difficult to communicate. 

### Can your research be used to perpetuate and even heighten inequality?
 With the wealth of data researchers have at their disposal, it is easy to become ensnared in the thought that if you just have enough data and your analyze it just right, you will be able to solve the world's problems. 
 
 From [Catherine D'Ignazio and Lauren Klein in The Numbers Don't Speak for Themselves](https://data-feminism.mitpress.mit.edu/pub/czq9dfs5/release/2#r6073173360) 
> Big Dick Data is a formal, academic term that we, the authors, have coined to denote big data projects that are characterized by patriarchial, cis-masculinist, totalizing fantasies of world domination as enacted through data capture and analysis. Big Dick Data projects ignore context, fetishize size, and inflate their technical and scientific capabilities."

From Weapons of Math Destruction, Conclusion:

## Conclusion
So what are we to do? 
## References
1. Brody, Janet L., John P. Cluck, and Alfredo S. Aragon. "Participants' understanding of the process of psychological research: Informed consent." *Ethics & Behavior* 7.4 (1997): 285-298.
2.  Bromley, Elizabeth et al. “From "Informed" to "Engaged" Consent: Risks and Obligations in Consent for Participation in a Health Data Repository.” The Journal of law, medicine & ethics : a journal of the American Society of Law, Medicine & Ethics vol. 48,1 (2020): 172-182. doi:10.1177/1073110520917007
3. Confessore, Nicholas. "Cambridge Analytica and Facebook: The Scandal and the Fallout So Far." *New York Times*, 4 April 2018, https://academicworks.cuny.edu/cgi/viewcontent.cgi?article=1797&context=gc_pubs. Accessed 18 Dec. 2020.
4. D'Ignazio, Catherine, and Lauren Klein. "Chapter Five: The Numbers Don’t Speak for Themselves." *Data Feminism.* PubPub, 2018.
5. Human, Soheil, and Florian Cech. "A Human-centric Perspective on Digital Consenting: The Case of GAFAM." *Human Centred Intelligent Systems.* Springer, Singapore, 2020. 139-159.
6. Meyer, Robinson. "Everything We Know About Facebook's Secret Mood Manipulation Experiment." The Atlantic, 28 June 2014, https://www.theatlantic.com/technology/archive/2014/06/everything-we-know-about-facebooks-secret-mood-manipulation-experiment/373648/. Accessed 18 Dec. 2020.
7. O'neil, Cathy. Weapons of math destruction: How big data increases inequality and threatens democracy. Kindle Ed. Broadway Books, 2016.
8. Perez, Caroline Criado. Invisible women: Exposing data bias in a world designed for men. Random House, 2019.
9. Sun, Tony, et al. "Mitigating Gender Bias in Natural Language Processing: Literature Review." *Association for Computational Linguistics (ACL 2019)* (2019).
10. Waltzer, Luke, Rhody, Lisa M., and Shirazi, Roxanne. “Testimony to the CUNY Board of Trustees in Opposition to the Resolution to Approve a Contract with Turnitin for Plagiarism Detection Software, December 14th, 2020 Meeting” *CUNY Academic Works*, 3 Dec. 2020, https://academicworks.cuny.edu/cgi/viewcontent.cgi?article=1797&context=gc_pubs. Accessed 18 Dec. 2020.
11. Yang, Min, and Kam-Pui Chow. "Authorship attribution for forensic investigation with thousands of authors." *IFIP International Information Security Conference*. Springer, Berlin, Heidelberg, 2014.
12. Mesnick, Max. "A Scientist's Take on Facebook's Psychology Experiment." *Max Masnick, PhD*. https://www.maxmasnick.com/2014/06/28/facebook/. Accessed 25 Dec. 2020.
13. "Anonymisation." *UK Data Service*. https://www.ukdataservice.ac.uk/manage-data/legal-ethical/anonymisation/qualitative.aspx. Accessed 25 Dec. 2020.

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
