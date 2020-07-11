# WiML brekout session at ICML
### Towards Child-Aware Machine Learning with a Focus on NLP Challenges and Applications


This repo contains material for the breakout session `Towards Children-Aware Machine Learning with a Focus on NLP Challenges and Applications`, which will be held at the [WiML Un-Workshop at ICML](https://icml.cc/Conferences/2020/Schedule?showEvent=7300) on **Monday, July 13, 2020 at 2:35-3:35 pm ET**.

Breakout sessions come in many shapes and forms, but their one unifying characteristic is that they are free-form discussions between small groups of participants on topics relevant to the theme of the session proposed by the leaders. 

- Co-leaders: [Belen Saldias](https://belencarolina.com), [Safinah Ali](http://safinahali.github.io)
- Facilitator: [Tamara Covacevich](https://github.com/tamycova), [Clare Liu](amikago.github.io)


## Abstract

Most powerful neural language models are trained agnostically to audiences [1]. Justifiably, they take advantage of as much available text as they can use to learn how to produce language fluently and solve other challenging tasks, using sources such as Wikipedia, books, or news media. More recently, these models have been constrained or fine-tuned to generate "less toxic," "less discriminatory," and "less negative" content, where classifiers are trained to determine these labels [2, 3]. A particularly vulnerable audience is that of children, and as more and more children are exposed to and interact with AI agents and other humans online, the need for robust children-aware language classification and generation is becoming even more pressing [4]: for example, for content moderation and child-agent interaction purposes, respectively. Furthermore, minors are already being exposed to conversational agents, such as home assistants [5, 6] or chatbots and social robots for learning [7, 8]. Research in human-robot interaction (HRI) has demonstrated how children interacting with social robots that act as learning peers have a positive influence on children’s learning gains and engagement [9]. Verbal interactions such as storytelling have shown to be beneficial in vocabulary learning and creativity [7, 10]. While much of these interactions have involved manually curated language data, or data trained on children’s storybooks, there is a pressing need to develop more structured and scalable methods  to make these interactions autonomous and to ensure that these agents produce age-appropriate content—especially as they are increasingly powered by state-of-the-art language models. We believe that the NLP community has the expertise to help develop children-focused tools that can assess how appropriate content found on the internet, and other sources, is for different age groups. Our ability to develop reliable children-aware models may also open avenues to more complex scenarios, such as story generation or NLP-assisted personalized mentoring, for children's development [7, 11, 12, 16].

Some of the challenges that we would like to discuss concerning what children-aware NLP entails are:
> A. Sources of curated language content for children include movies and books. However, we most often only have one number to describe the age-appropriateness of that content. How can we best exploit this data? Further, can we make this child-appropriate content curation culturally diverse? [2, 3]

> B. Can we make state-of-art autonomous conversational agents "safe enough" that we actually deploy them to children? How should safety be defined and evaluated? And what is the role of interpretability for adults to understand, trust, and use these systems? [13]

> C. Different age groups are held to varying subsets of norms, and as age increases, these subsets of rules also expand and intersect. How can we learn the "decision boundaries" that make for acceptable norms within age groups? How can we use these boundaries or rules for language classification and generation? [14, 15]

## Format

Stay tuned for more details on this specific session.


## Short bios

##### Belen Saldias

Belen Saldias, M.Sc., is a second-year Ph.D. student at the Lab for Social Machines at MIT. Along with being a machine learning and natural language processing researcher, she is also a computer science engineer. Belen has worked in various research projects where she has contributed to multiple domains such as variational inference applications, human-computer interaction, online RCTs, and natural language processing. Before joining MIT, Belen worked at Harvard University as a research assistant with a focus on finding more efficient ways to create training sets, where she proposed a probabilistic graphical model to this end. Currently, she aims to understand and explore what children-aware NLP would entail.

##### Safinah Ali
Safinah is a PhD student in the Personal Robots group at MIT. Her research focuses on making AI accessible to diverse communities and using Social Robots to foster positive learning behaviors in children. She studies the role of child-robot interaction in simulating curiosity, creativity and growth mindset in young children. She has developed Creative AI learning tools. She has also worked on robots for accessibility, particularly to assist children with Autism Spectrum Disorder. She likes to explore creative computational techniques and how they can be applied to social problems, especially in the developing world. She did her Bachelors in Design from IIT Guwahati and her Masters in HCI from Carnegie Mellon University.

##### Tamara Covacevich
Tamara, B.Sc., is a master's student in the IA Lab at the Pontifical Catholic University of Chile. Her current research focuses on representation learning for healthcare challenges. Specifically, she is studying medical records representations and ways to leverage them to improve performance of the readmission prediction task.

##### Clare Liu
Clare is currently an undergraduate at MIT, studying design and computer science. Alongside exploring the intersection of art and technology, she adores reading and telling stories and designing new systems to share them. She hopes to tell thought-provoking and touching stories, translating everyday sentiments into a much more understandable medium.



## References

<sub><sup>
1.	Brown, T. B., Mann, B., Ryder, N., Subbiah, M., ... & Agarwal, S. (2020). Language Models are Few-Shot Learners. arXiv preprint arXiv:2005.14165.
1.	Peng, X, Li, S, Frazier, S & Riedl, M (2020) Fine-Tuning a Transformer-Based Language Model to Avoid Generating Non-Normative Text. arXiv:2001.08764.
1.	Schmidt, A., & Wiegand, M. (2017, April). A survey on hate speech detection using natural language processing. In Proceedings of the Fifth International Workshop on NLP for Social Media.
1.	Something is wrong on the internet (2017). Retrieved 8 June 2020 from medium.com/@jamesbridle/something-is-wrong-on-the-internet-c39c471271d2
1.	Druga, S., Williams, R., Breazeal, C., & Resnick, M. (2017, June). "Hey Google is it OK if I eat you?" Initial Explorations in Child-Agent Interaction. Conference on Interaction Design and Children.
1.	Lovato, S. B., Piper, A. M., & Wartella, E. A. (2019, June). Hey Google, Do Unicorns Exist? Conversational Agents as a Path to Answers to Children's Questions. International Conference on Interaction Design and Children.
1.	Kory Westlund, J. M., Jeong, S., Park, H. W., Ronfard, S., Adhikari, A., Harris, P. L., ... & Breazeal, C. L. (2017). Flat vs. expressive storytelling: young children’s learning and retention of a social robot’s narrative. Frontiers in human neuroscience, 11, 295.
1.	Xu, Y., & Warschauer, M. (2019, May). Young children's reading and learning with conversational agents. In Extended Abstracts of the 2019 CHI Conference on Human Factors in Computing Systems (pp. 1-8).
1.	H. W. Park, M. Gelsomini, J. J. Lee and C. Breazeal, "Telling Stories to Robots: The Effect of Backchanneling on a Child's Storytelling *," 2017 12th ACM/IEEE International Conference on Human-Robot Interaction (HRI, Vienna, 2017, pp. 100-108.
1.	Ali, S., Moroso, T., & Breazeal, C. (2019). Can Children Learn Creativity from a Social Robot?. In Proceedings of the 2019 on Creativity and Cognition.
1.	Cremin, T., Flewitt, R., Mardell, B, & Swann, J (2016) Storytelling in early childhood: Enriching language, literacy and classroom culture. Taylor & Francis
1.	Fan, A., Lewis, M., & Dauphin, Y. (2018). Hierarchical neural story generation. arXiv preprint arXiv:1805.04833.
1.	Jacovi, A., & Goldberg, Y. (2020). Towards Faithfully Interpretable NLP Systems: How should we define and evaluate faithfulness?.  arXiv:2004.03685.
1.	Awasthi, A., Ghosh, S., Goyal, R., & Sarawagi, S. (2020) Learning from Rules Generalizing Labeled Exemplars. ICLR.
1.	Dathathri, S., Madotto, A, Lan, J., ... & Liu, R. (2019) Plug and play language models: a simple approach to controlled text generation. arXiv:1912.02164.
1.  Gillani, N., Saldias, B., Makini, S., Hughes, M., and Roy, D. (2020) INSPIRE. Retrieved 8 June 2020 from https://www.media.mit.edu/projects/inspire/overview/.
</sup></sub>


