---
title: Bias in AI Systems
tags: [AI, ML, Machine Bias]
style: fill
color: danger
description: How Machine Bias effects decision making
---


![](https://koyapartners.com/wp-content/uploads/2019/09/Bias.jpg)


Artificial Intelligence (AI) is revolutionizing the way we look at decision-making which is more traditionally attributed to human experience, expertise and judgement. Smart systems developed using AI come with processing speeds and capacities that far surpass those of humans. Machine Learning is a highly data-driven pattern recognition approach which tries to deduce why certain actions were executed across a wide range of data points in the training samples. When we look at automating loan sanctions, credit scores or passing on a law judgement, they take into account factors other than prior criminal records such as poverty, joblessness and social marginalization. But these systems come with a catch. Though they have unparalleled processing capacities, these systems do not always provide us with reliable results. Since AI models are created and trained by humans, they are bound to mimic some of the biases and prejudices that we humans carry. These discrepancies generally occur due to biased datasets as AI models are only as good as the data they are fed with which lead to higher error rates and biased decision making, even when the underlying algorithm is sound. Let us look at how bad training datasets give rise to biased judgements.


 Use of risk assessments scores is becoming more and more common at every stage of criminal justice proceedings in the US. These scores predicted the likelihood of each felon from committing a future crime. While computing these scores, the computer algorithm was more likely to falsely flag black defendants as future criminals at almost twice the rate as white defendants. White defendants were mislabeled as low risk more often than black defendants. On the basis of these risk assessments, black defendants are condemned to much harsher sentences as opposed to their white counterparts. Even when we consider factors such as poverty, economic stability and social marginalization, blacks are shown in a negative light. According to the research conducted by the Pew Research Center, on average, blacks are at least twice as likely as whites to be poor or unemployed. And in terms of their median net worth, white households are about 13 times as wealthy as black households - a gap that has been growing wider since the Great Depression. Another factor we need to consider is unequal pay. According to the above-mentioned survey, the income of blacks at all levels of educational attainment lags behind that of their white counterparts. So when the algorithm takes into account the above-mentioned factors, a repeated offender might come out as low risk since he has a job while a drunk guy might come across as high risk just because he’s homeless.

 ![](https://miro.medium.com/max/700/0*cfX-3V_kHwT5o3_T)


Gender and racial bias could also cause problems for computer vision models like facial recognition, such as security applications at concerts, airports, and sports arenas, a concern that also extends into the gender binary. If AI sees gender as simply male and female, this doesn't align with modern perspectives of non-binary and transgender expression, causing potential harm for these communities and loss of faith in digital identity. Studies show that capabilities of facial recognition services are not adequately balanced for gender and skin tone resulting in higher error rates. Results are the most accurate for light-skinned men while dark-skinned women have the highest error rates. In order to increase the accuracy of the facial analysis, we need to use more diverse, inclusive and unbiased training datasets and improve the feature extraction and recognition capabilities of the service. These adjustments to the service demonstrated a nearly ten-fold decrease in error-rate for facial analysis when compared with the previous test set. 


Gender bias in online recruitment tools. Amazon has discontinued the use of its recruiting algorithm since the algorithm was derived from the resumes submitted to the company over a decade, which were predominantly from white males. Rather than reviewing the skill sets, the algorithm was taught to recognise word patterns in the resume and these patterns were benchmarked against the company’s predominantly male engineering department to deem an applicant fit for the job. As a result, the AI software penalised the resumes containing the word “women’s” in the text, thereby discrediting the resumes of women who graduated from women’s colleges, resulting in gender bias.

Many of these biases have been there in existence way before data-driven, decision-making models came to surface but infusing the existing biased data with decision making has far more disastrous implications in how we govern our society as the gap will just tend to increase and set us on a journey to an unjust society if these biases aren’t mitigated.

Data Augmentation is also one technique to diversify our dataset and populate it with underrepresented data while training. This will obviously work only when the developer is aware of such biases. To do so, while preprocessing we make data duplicates and diversify the biased factors for the same set of other training features followed by imbalance learning techniques like undersampling and oversampling which will help us create a robust model subject to minimal bias. This helps models to find patterns beyond race, gender, caste etc.

We can mitigate bias by diversifying training samples in terms of gender, ethnicity, age, sexuality, etc; a continual cycle of bias detection and mitigation coupled with AI models that are transparent and explainable. Lastly, one method of study proposed to understand why models conclude on a certain decision. Explainable AI, XAI is our way of understanding the immense learning capabilities of AI and unravelling the mysterious black box, the so-called artificial brain. XAI has been part of our lives for a long time, Amazon Shopping and Netflix recommendations are a prime example of simple XAI models where they associate our recommendations to that of our past behaviours. When it comes to the filter bubble problem, a factor of randomisation or surprise plays an important role in breaking the filter bubble and allowing users to interact with the content they otherwise wouldn’t have. A factor of explanation along with a surprise quotient allows populating the training set with newer possibilities and break the chain of far left or far right biases. EU’s guidelines on ethics in Artificial Intelligence associates standards of human explainability to AI requiring fair and context-based modelling in order to associate trust in such decision-making capabilities. Though it’s a fairly new approach it is important to understand the why behind the what. 

Bias has been an age-old existence and it cannot be completely removed from the equation for machines or humans. Machines are subjected with far more scrutiny than their human counterparts but it’s important to understand that in a society full of prejudices and biases we still try to serve all and follow the principles of humanity and inclusivity. To mitigate bias means to fight for a just and fair decision which is far more important than the accuracy of a model based on prior data. Human supervision, cooperation and constant reconfiguration and bias tracking is the way going forward. 



References:<br>
-<a href="https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing">https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing</a><br>
-<a href="https://www.ibm.com/blogs/research/2018/02/mitigating-bias-ai-models/">https://www.ibm.com/blogs/research/2018/02/mitigating-bias-ai-models/</a> <br>
-<a href="https://www.theverge.com/2018/10/10/17958784/ai-recruiting-tool-bias-amazon-report">https://www.theverge.com/2018/10/10/17958784/ai-recruiting-tool-bias-amazon-report</a><br>


