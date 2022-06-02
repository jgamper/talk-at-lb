# Talk at the Bank of Lithuania
----

### Recent notable advances:
1. Chowdhery, Aakanksha, et al. "Palm: Scaling language modeling with pathways." arXiv preprint arXiv:2204.02311 (2022). [link](https://arxiv.org/abs/2204.02311)
2. Saharia, Chitwan, et al. "Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding." arXiv preprint arXiv:2205.11487 (2022). [link](https://arxiv.org/abs/2205.11487) [accompanying page](https://imagen.research.google/)
3. Ramesh, Aditya, et al. "Zero-shot text-to-image generation." International Conference on Machine Learning. PMLR, 2021. [link](https://proceedings.mlr.press/v139/ramesh21a.html)
4. Reed, Scott, et al. "A Generalist Agent." arXiv preprint arXiv:2205.06175 (2022). [link](https://arxiv.org/abs/2205.06175) [accompanying page](https://www.deepmind.com/publications/a-generalist-agent)

### Industry examples:
1. Kangas, Ioannis, Maud Schwoerer, and Lucas J. Bernardi. "Recommender Systems for Personalized User Experience: Lessons learned at Booking. com." Fifteenth ACM Conference on Recommender Systems. 2021. [link](https://dl.acm.org/doi/pdf/10.1145/3460231.3474611?casa_token=m7tDyd2C0V8AAAAA:U0Wj5jaGHOWniXtkGMIKtwpVICHkZJcAEHbU7mng6vXNuEDJL9-j32mTWesmG0XqANh03ELKwho)
2. Gomez-Uribe, Carlos A., and Neil Hunt. "The netflix recommender system: Algorithms, business value, and innovation." ACM Transactions on Management Information Systems (TMIS) 6.4 (2015): 1-19. [link](https://dl.acm.org/doi/pdf/10.1145/2843948)
3. Basilico, Justin. “Recent Trends in Personalization at Netflix”. (2020). [link](https://www.slideshare.net/justinbasilico/recent-trends-in-personalization-at-netflix)

### Richard Sutton's Bitter Lesson
1. Sutton, Richard. “The Bitter Lesson.” (2019) [link](http://www.incompleteideas.net/IncIdeas/BitterLesson.html)

### Tooling/Compute/Accessibility
1. Sculley, David, et al. "Hidden technical debt in machine learning systems." Advances in neural information processing systems 28 (2015). [link](https://proceedings.neurips.cc/paper/2015/hash/86df7dcfd896fcaf2674f757a2463eba-Abstract.html)
2. https://github.com/FRBNY-DSGE
3. Lawrence, Neil. “Deploying Machine Learning: Intellectual debt and AutoAI”. (2020). [link](http://inverseprobability.com/talks/notes/deploying-machine-learning-systems-intellectual-debt-and-auto-ai.html)

### Parameterisation & Ammortisation
1. Kingma, Diederik P. "Variational inference & deep learning." PhD thesis 978–94-6299–745-5 (2017). [link](https://pure.uva.nl/ws/files/17891313/Thesis.pdf)
2. Summary on flow models: https://lilianweng.github.io/posts/2018-10-13-flow-models/
3. Jia, Junteng, and Austin R. Benson. "Neural jump stochastic differential equations." Advances in Neural Information Processing Systems 32 (2019). [link](https://proceedings.neurips.cc/paper/2019/hash/59b1deff341edb0b76ace57820cef237-Abstract.html)
4. https://github.com/SciML/DiffEqFlux.jl <- package for solving all sorts of differential equations types with neural net parameterisation

### Funky agent-based example
1. https://www.stephanzheng.com/ <- all resources there

### NOTE!
A lot of the models above are based on Transformer neural network, to learn more about it, see following resources:
1. http://nlp.seas.harvard.edu/annotated-transformer/
2. https://jalammar.github.io/illustrated-transformer/

Because it is an attention based model, people tend to think that they can use attention weights to interpret the model - one needs to be extremely cautious when doing that (see https://arxiv.org/abs/2110.08412 for details).
