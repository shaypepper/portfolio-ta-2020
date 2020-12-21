## _*So, you think you're a feminist?*_
The easy ways we cut corners in text analysis

By Shay Culpepper

---


## Intro
Machine-based text analysis is as pervasive in 2020 as it is impactful. With new open source tools becoming available all the time, anyone is a few lessons away from doing sentiment analysis, topic modeling or creating a chat bot. Currently there are applications in data journalism, digital humanities, language translation, customer service, advertising, criminal justice, search engine optimization and more. The possibilities are limited only by the analyst's imagination. However, reality is limited by time and resources. Thorough, representative analysis is simply expensive. It is easier to use someone else's model than create your own, even if it comes from a blackbox of unsupervised learning. It takes less time to reach for an existing data set even if that data comes exclusively from people who were not aware their text would be analyzed in the way you intend to. It is _easy_ to settle in research. It is _easy_ to take shortcuts. What if researchers refused to? What sorts of objections would be neccessary for a researcher to say, "This is not worth it." ([Like that Google ethics researcher](https://www.platformer.news/p/the-withering-email-that-got-an-ethical))

Big Dick Data


## Definitions
For this paper I use the term text analysis (TA) to describe the general use of computers to analyze text. However, most of my concerns revolve around machine learning applications of text analysis and training sets in particular. These concerns are most relevant to social media. 

## Choosing your data
[Ethical decision-making in internet research.](http://aoir.org/reports/ethics2.pdf)

### Consent
Text data from social media websites such as Twitter or Reddit is often made available via APIs directly from the company. Often you can also obtain social media data via web-scraping. Unfortunately, there is an assumption that because the text is publicly available, it is free game for analysis. Legally, that is often true as most social media companies' terms of service include written consent from the user regarding ownership of their data. However, how many users actually read those? Furthermore, no written agreement can account for all possible use cases. This creates a [consent](https://epub.wu.ac.at/7523/1/HCIS2020_A%20Human-centric%20Perspective%20on%20Digital%20Consenting_The%20Case%20of%20GAFAM_Soheil%20Human_Florian%20Cech.pdf) gap because the user is not aware of the implications of their data being used in unknown contexts. 

> Subsequently, users are confronted with the necessity to either accept the companies’ terms of services as-is or to undertake the arduous task of choosing when to share which of their private data through web interfaces provided by the data collectors themselves, meaning privacy and cookie consent forms.

The question I am getting at is this: If a social media user knew the intended use of their data, would they be comfortable with it? 

As an example, consider an [authorship attribution study](https://link.springer.com/chapter/10.1007/978-3-642-55415-5_28). In this study Min Yang and Kam-Pui Chow use a blog corpus to test an algorithm intended to aid law enforcement. 

In a related example, consider [plagiarism-detection software](https://academicworks.cuny.edu/gc_pubs/670/). 

### Potential for harm
Would using this data expose anyone to harm? 
* Return to plagiarism example
* Return to authorship attribution by Law enforcement
* Weapons of math destruction & Feedback loops
* Privacy. Potential for doxxing.
* Should the dataset exist at all?

### Representation
Interectional representation? 
Gender: Is this majority male? Are non-binary people included as non-binary. 
Quote Invisible Women

## Training sets and models
Most Natural Language Processing requires training sets and models 

#### Secondary Data Analysis
Are you using this text for its intended purpose? 
#### Creating harmful feedback loops
#### Erasing intersectional features
AAVE
English as a second language
Women's voives versus men's
#### Feature selection


### Supervised vs unsupervised

## Conclusion


Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum semper diam et eleifend sollicitudin. Quisque semper sapien sed est pulvinar, sit amet tincidunt leo luctus. Integer viverra massa eu ornare imperdiet. Duis neque orci, ornare at leo id, viverra hendrerit mauris. Aenean non dictum velit. Nunc rhoncus tellus nec sem consequat, sit amet ornare arcu ultrices. Nunc nisi sapien, finibus non tincidunt et, mattis vel lectus. Aenean suscipit ligula metus, non iaculis mauris pellentesque in. Pellentesque varius ut eros non auctor. Sed et justo tempus, aliquet diam eu, tristique libero. Aliquam erat volutpat. Nulla metus ligula, euismod ut enim eu, finibus malesuada tortor. Ut diam risus, lacinia et placerat id, aliquam id magna.

Aenean vitae convallis orci, ac lobortis diam. Suspendisse tortor mauris, pretium eget nunc non, suscipit dignissim dolor. Donec aliquam sollicitudin nulla, at lobortis est consequat nec. Quisque congue, nisi at luctus imperdiet, elit nisl sollicitudin massa, rhoncus commodo nibh augue non odio. Morbi pulvinar justo id malesuada eleifend. Morbi vel magna vel orci imperdiet pharetra. Aenean mattis libero mi, nec ultrices quam sodales sed. Fusce molestie diam posuere ante rutrum, vel rhoncus lectus mollis. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent nisi justo, ornare vulputate vestibulum et, porttitor vel lectus. Cras lobortis massa nisi, quis bibendum quam porta at. Etiam maximus felis et odio consectetur fermentum. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nam iaculis euismod dolor a sodales.

Aenean tristique erat sit amet sem mattis, eget consequat arcu pellentesque. Suspendisse bibendum mattis rutrum. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Quisque vitae tortor vulputate, suscipit arcu eu, scelerisque ipsum. Nulla mattis tempor tristique. Donec ex nunc, lacinia ut turpis et, laoreet porttitor dolor. Ut luctus aliquet dolor. Curabitur porta risus sapien, ut iaculis tortor fermentum sit amet. Nullam eget iaculis orci.

Maecenas mollis elit eget mauris faucibus lobortis. Curabitur ultricies, nibh quis venenatis viverra, sapien ante semper neque, id lobortis sem ipsum id lectus. Quisque rhoncus libero et nisl egestas porta. Aliquam suscipit ante ut nunc mattis viverra. Morbi fringilla condimentum justo, et condimentum lorem vehicula in. Morbi suscipit quam nibh, a malesuada massa egestas a. Curabitur pretium ex a gravida feugiat.

Curabitur mollis, orci non iaculis vehicula, lectus sapien dignissim ex, ac tincidunt mauris enim sed nisi. Vivamus suscipit vitae justo sit amet pellentesque. Praesent pharetra massa ac mi fringilla, id vehicula elit maximus. Nulla quis blandit ex, non venenatis neque. Praesent et est ut leo tempor condimentum nec in lorem. Pellentesque vitae volutpat ex, sed vehicula tortor. Nam luctus nisl non luctus porttitor. Nam et vulputate urna, vitae egestas orci. Suspendisse pulvinar bibendum mi nec consectetur. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut id ipsum laoreet tellus pretium mollis.

Cras dictum ornare enim vitae dictum. Nunc convallis cursus cursus. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Mauris fermentum congue cursus. Sed sapien odio, faucibus in venenatis ut, faucibus et ex. Proin volutpat orci a porta cursus. Pellentesque lobortis urna et quam aliquam, et venenatis mi facilisis. Pellentesque pretium eu dolor dignissim euismod. Sed posuere posuere imperdiet.

Donec commodo mauris non dignissim congue. Etiam quis lacinia dui. Vivamus non velit at ex faucibus tristique. Morbi dapibus neque sit amet mauris lacinia, a bibendum sem porttitor. Donec libero elit, lacinia sed facilisis at, fringilla a urna. Vestibulum semper quis tellus quis viverra. Nullam justo justo, condimentum eu suscipit a, accumsan vel justo. Integer quam nunc, imperdiet id felis in, sodales ullamcorper sapien. Praesent eget luctus metus. Aenean tincidunt a massa et volutpat. Duis et mauris vitae ligula tempor gravida. Vivamus in ultrices justo, sit amet gravida nisi. In rutrum nulla quis ipsum sodales iaculis. Morbi consequat laoreet neque ac condimentum. In in nisi scelerisque magna pretium maximus.

Proin commodo volutpat dui, faucibus ullamcorper est efficitur sit amet. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Curabitur porttitor nisi massa, vel dictum libero rhoncus a. Proin vel facilisis arcu. Donec vitae urna non tellus eleifend pellentesque. Quisque vel ultricies tellus, ut lobortis leo. Vestibulum pellentesque consectetur quam, et molestie metus venenatis non. Vivamus semper faucibus diam, vitae commodo dui posuere in. Nulla velit metus, rhoncus sollicitudin lorem non, tristique tincidunt elit. In mollis est eget iaculis scelerisque. Vivamus tincidunt ultrices ligula eu scelerisque. Proin imperdiet eget mi eget interdum.

Morbi metus urna, dapibus vel gravida vitae, ornare at justo. Suspendisse congue ac eros quis finibus. Integer sollicitudin, augue in vehicula porttitor, turpis justo fermentum arcu, ut tincidunt turpis est ut nibh. Aenean eu gravida ante, eget sollicitudin ligula. Vivamus elementum gravida elementum. Sed finibus lacus nibh, varius varius libero imperdiet porta. In vitae tempor dui. Maecenas accumsan nibh eros, ac congue eros tincidunt posuere. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Vivamus et lectus dolor. Nunc pretium velit justo, non mattis lacus porta sit amet. Sed eget sodales eros. Nulla lacinia volutpat lectus quis condimentum. Vestibulum purus enim, facilisis non consectetur euismod, aliquam sit amet enim. Donec dui magna, aliquam eu maximus quis, consectetur ac justo.

Morbi auctor sem nec lacus elementum suscipit. Praesent placerat lacinia molestie. Cras libero lectus, facilisis et feugiat in, convallis ut erat. Nulla nunc quam, porttitor ut sollicitudin eu, suscipit vel eros. Curabitur nec nisi vitae felis pulvinar aliquam. Morbi porta diam ligula, pellentesque fringilla mauris pulvinar id. Nam vel suscipit sapien.

Proin libero ante, efficitur non gravida a, interdum nec tellus. Vestibulum eget augue eleifend, accumsan odio sit amet, egestas augue. Sed cursus tempus eros, in interdum nisl iaculis sit amet. Praesent hendrerit lectus eu lectus semper, a blandit ex porta. Aliquam a tortor sodales, congue nunc ac, congue mauris. Donec pulvinar mauris lacinia dolor suscipit egestas. Integer in neque consectetur, suscipit justo ut, ullamcorper leo. Ut condimentum dolor sit amet auctor mollis. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Phasellus at elementum tellus, sed semper dolor. Phasellus nec metus at lectus elementum efficitur. Ut a hendrerit nunc.

Sed congue tristique urna, sed iaculis augue. Nulla id erat nibh. Cras ac nulla non tellus sagittis suscipit. Proin laoreet massa lorem, ac varius leo facilisis fermentum. Aliquam velit mi, blandit vitae aliquet ut, imperdiet at eros. Fusce feugiat elit quis nisi efficitur, a pharetra mauris convallis. Proin dictum placerat dui et commodo. Cras ornare quam a varius pretium. Aliquam ullamcorper metus ac hendrerit tristique. Fusce mollis tortor neque, et semper dolor pellentesque quis. Vivamus dignissim eu purus id fringilla. In in arcu sit amet magna vestibulum rutrum.

Duis porttitor ante vitae diam posuere porttitor at sit amet arcu. Duis id tincidunt sapien, ut porta sapien. Nunc sit amet turpis dapibus, tincidunt nisl non, sagittis mi. Nunc a facilisis turpis. Ut sagittis sem in massa consectetur, ut molestie erat tempus. Phasellus lobortis magna turpis, vel hendrerit nisi viverra sed. Phasellus eu erat eu justo hendrerit maximus. Vivamus malesuada ante nisi, in hendrerit massa gravida at. Integer quam enim, rhoncus nec libero a, faucibus semper velit. Morbi faucibus fermentum felis, sit amet finibus nunc. Duis suscipit, leo vitae mollis malesuada, ligula magna dapibus ligula, nec rhoncus libero mi commodo metus. Pellentesque a placerat ante, posuere rhoncus tellus. Duis sit amet dolor quis tortor malesuada pharetra. Praesent luctus hendrerit imperdiet. Aenean vitae urna dignissim, convallis lectus at, gravida lorem. Vestibulum egestas eu orci vitae aliquam.

In dapibus laoreet nisl, consequat molestie eros laoreet sit amet. Praesent congue hendrerit libero, tincidunt ultricies sapien egestas non. Vivamus sem lorem, rutrum et metus.