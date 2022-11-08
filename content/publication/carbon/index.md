---
title: "Measuring the Carbon Intensity of AI in Cloud instances"
authors:
- jesse
- Taylor Prewitt
- Remi Tachet des Combes
- Erika Odmark 
- me
- emma
- Sasha 
- noah
- Nicole DeCario
- Will Buchanan 
publication_types: ["1"]
Date: 2022-04-06
publishDate: 2022-04-06T00:00:00Z
publication: In *Proc. of FAccT 2022*
abstract: "The advent of cloud computing has provided people around the world with unprecedented access to computational power and enabled
rapid growth in technologies such as machine learning, the computational demands of which come with a high energy cost and
a commensurate increase in carbon footprint. As a result, recent scholarship has called for better estimates of the impact of AI on
greenhouse gas emissions. However, data scientists today do not have easy or reliable access to measurements of this information,
which precludes consideration of how to reduce the costs (computational, electricity, environmental) associated with machine learning
workloads. We argue that cloud providers presenting information about software carbon intensity to users is a fundamental stepping
stone towards minimizing emissions.<br>
In this paper, we provide a framework for measuring software carbon intensity, and propose to measure operational carbon
emissions by using location-based and time-specific marginal emissions data per energy unit. We provide measurements of operational
software carbon intensity for a set of modern models covering natural language processing (NLP) and computer vision applications,
including four sizes of DenseNet models trained on MNIST, pretraining and finetuning of BERT-small, pretraining of a 6.1 billion
parameter language model, and five sizes of Vision Transformer. We confirm previous results that the geographic region of the data
center plays a significant role in the carbon intensity for a given cloud instance. We also present new results showing that the time of
day has meaningful impact on operational software carbon intensity. We then evaluate a suite of approaches for reducing emissions
in the cloud: using cloud instances in different geographic regions, using cloud instances at different times of day, and dynamically
pausing cloud instances when the marginal carbon intensity is above a certain threshold. We find that choosing an appropriate region
can have the largest impact, but emissions can be reduced by the other methods as well. Finally, we conclude with recommendations
for how machine learning practitioners can use software carbon intensity information to reduce environmental impact."
tags:
- greenai
links:
url_pdf: 'http://arxiv.org/abs/2206.05229'
#url_post: 'https://blog.allenai.org/measuring-and-mitigating-ai-carbon-intensity-8624bc805c1a'
news: <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://www.nature.com/articles/d41586-022-01983-7" target="_blank" rel="noopener noreferrer">Nature</a> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://www.technologyreview.com/2022/07/06/1055458/ai-research-emissions-energy-efficient/" target="_blank" rel="noopener noreferrer">MIT Technology Review</a> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://spectrum.ieee.org/ai-carbon-footprint" target="_blank" rel="noopener noreferrer">IEEE Spectrum</a> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://www.marktechpost.com/2022/06/19/microsoft-and-ai2-partnered-with-the-green-software-foundation-on-tools-for-building-carbon-aware-applications/" target="_blank" rel="noopener noreferrer">MarketTechPost</a> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://techcrunch.com/2022/06/27/perceptron-analyzing-images-in-the-blink-of-an-eye-and-tracking-the-lifecycle-of-snow/" target="_blank" rel="noopener noreferrer">TechCrunch</a> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://www.sdxcentral.com/articles/news/microsoft-urges-ai-compute-carbon-intensity-awareness/2022/06/" target="_blank" rel="noopener noreferrer">SDxCentral</a> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://www.techtarget.com/searchenterpriseai/feature/Green-AI-tackles-effects-of-AI-ML-on-climate-change" target="_blank" rel="noopener noreferrer">TechTarget</a> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://dataconomy.com/2022/07/reducing-the-carbon-footprint-of-ai/" target="_blank" rel="noopener noreferrer">Dataconomy</a> <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://indiaai.gov.in/article/the-need-to-measure-ai-s-carbon-footprint-is-more-than-ever-before-why-it-matters?utm_source=Twitter&utm_medium=Generic&utm_campaign=WBS-the-need-to-measure-ai-s-carbon-footprint-is-more-than-ever-before-why-it-matters-14th-July" target="_blank" rel="noopener noreferrer">INDIAai</a>
url_video: 'https://www.youtube.com/watch?v=L83p05NaoUU'
---
