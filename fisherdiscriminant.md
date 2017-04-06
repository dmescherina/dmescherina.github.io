> April 7, 2017

# Discrimination Beyond Good and Evil

****

This is Ronald Aylmer Fisher, Sc.D., F.R.S.
You would probably agree that he looks like a very serious man.

![](assets/post2/fisher.jpg)

He looks even more serious when his portrait is transformed using the Deep Dream algorithm (you can find the algorithm in the open source [here] ):

[here]:https://deepdreamgenerator.com/generator-style

![](assets/post2/dream_fisher.jpg)

I believe we can say with the utmost certainty that he was indeed important for the development of statistical analysis. However, as it happens, one of his contributions, __*Fisher's linear discriminant*__, which is the subject of this post, has been invented in the context of [Eugenics], a more than controversial academic discipline that was used, amongst other things, as a justification for Nazism, discrimination against racial minorities and sterilisation of mentally or otherwise disabled patients in US and Europe.  

[Eugenics]:https://en.wikipedia.org/wiki/Eugenics

On the other hand, the discriminant analysis has become one of the fundamental classification methodologies. Since the publication of the [original paper] by Fisher in the "Annals of Eugenics" in 1936 its underlying principles have given rise to a lot of more modern and sophisticated classification techniques popular in machine learning today

[original paper]:http://onlinelibrary.wiley.com/doi/10.1111/j.1469-1809.1936.tb02137.x/abstract

****

* In short, __*Linear discriminant analysis*__ solves the classification problem by maximising the distance between the means of the two classes. The original problem that Fisher posed was the following:
        >Find the linear combination Z = aT*X such that the between-
        class variance is maximised relative to the within-class variance

* __*Quadratic discriminant analysis*__, unlike the linear version, doesn't make the assumption that the covariance matrices of the 


* __*Regularised discriminant analysis*__ is a compromise between the linear and quadratic discriminant analysis where covariance matrices which are different in the assumptions of quadratic discriminant analysis are shrunk towards the common matrix like in linear discriminant analysis case  
