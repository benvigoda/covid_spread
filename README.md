# covid_spread
Mathematical model to help answer the questions "how long will we need to stay home?" and "how bad will COVID-19 get?"

Conclusion: 

### *The simulations show that given how people are behaving now, there will be a day at the peak in late April when 100,000 households in Cambridge and Arlington MA will yield 4,500 new symptomatic cases in one day.  If 5% of those are serious cases, the hospitals will be admitting 225 serious cases per day at the peak, and will average on the order of 100 new serious cases per day for a twenty day period.  Given over a million households in the Boston area, that is on the order of 2,000 new serious cases per day for twenty days.  That is 40,000 serious cases in the Boston area in a very short period.  We do not have that many ventilators.  The hospitals will still be over-run.*

To flatten the curve, we need to be even more careful not to transmit the disease than most people are being right now.

### Each staying home household needs to only transmit the virus to another staying home household once every 20 days.  So no going for walks with your best friend once every day or even every week.  One person from your household can only do that once per couple of weeks if you are going to transmit the virus to them while you are with them.

### A given moving/mobile worker like a food delivery person, must only communicate the virus to a stay at home household once every 20 days.  With all of the bags being carried and all of the individual fruits being picked up and put into bags by workers who might be incubating the virus, and with a delivery person delivering to 10-20 households per day, deliveries from a given delivery person can only result in a household getting infected once every 20 days.

### The mobile workers need to be very careful as well.  If they are together at a grocery store or packing warehouse, a given worker can only transmit the virus to another worker once every 10 days.

We deeply welcome improvements to the model, and experiments to simulate different input assumptions.  My goal here was to create a seed for the open source data science community to build from. Even though a big first wave of the virus will be already "crashing over the population" before this model can probably be put into public policy use, I anticipate that it could become extremely useful for helping local governments manage through how we lift the social distancing directives, and how we deal with the second wave of the virus.  Examples of things that are not yet in this model:

1. After people recover from the illness, they become a kind of buffer in the populaton.  It acts as if people become spatially more spread out. If you think of people like particles diffusing through space, on average they will start to have immune people in between them.  That is not in the model.

2. Age groups. I wanted the model to be simple so that a lot of people could quickly read and understand it.  So I didn't add age bands like the models reported by the WHO modeling team.  Adding age bands would be a great way for a graduate student mathematical modeling to contribute.

3. I didn't set this model up to learn the parameters from data.  This is a generative model.  It would be a great project to put it into, for example, https://pyro.ai/ and infer/learn the parameters from data.


How Computer Modeling Of COVID-19's Spread Could Help Fight The Virus: https://www.npr.org/sections/health-shots/2020/03/04/811146915/how-computer-modeling-of-covid-19s-spread-could-help-fight-the-virus

"Scientists who use math and computers to simulate the course of epidemics are taking on the new coronavirus to try to predict how this global outbreak might evolve and how best to tackle it.

But some say more could be done to take advantage of these modeling tools and the researchers' findings.

It is sort of an ad hoc, volunteer effort, and I think that's something that we could improve upon," says Caitlin Rivers, an infectious diseases modeler with the Johns Hopkins Center for Health Security.

In her view, "modeling plays a really important role in understanding how an outbreak is unfolding, where it might be going, and what we should be thinking through.

But only a small number of the modelers of epidemics work for the federal government, she says. Most are in academia, and they don't have formal relationships with officials who have to make key public health decisions.

Putting that information out really quickly helped to bring a lot more attention of other modelers to say, 'There are now things that we can do, so let's do that,'" says Rosalind Eggo, an infectious disease modeler at the London School of Hygiene & Tropical Medicine."

Useful resources:

https://www.imperial.ac.uk/media/imperial-college/medicine/sph/ide/gida-fellowships/Imperial-College-COVID19-NPI-modelling-16-03-2020.pdf

https://www.masslive.com/coronavirus/2020/03/coronavirus-updates-how-many-cases-deaths-and-recoveries-other-essential-and-changing-information.html

https://medium.com/@tomaspueyo/coronavirus-act-today-or-people-will-die-f4d3d9cd99ca

https://www.medrxiv.org/content/10.1101/2020.03.09.20033050v1.full.pdf
