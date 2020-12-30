# Automated Identification of Security Discussions in Microservices Systems

**Problem Statement**: Problem Statement: Our research shows that security decisions in microservices systems are often not well informed. This can stem from different factors. For example, there is a knowledge gap among practitioners and organizations in designing and implementing a secure microservices system. Also, there is a lot of confusion in the industry about the potential security capabilities of technologies and tools used in the development of microservices systems and the best practices to configure them for security purposes and address their security vulnerabilities.

 
**Our Approach**: Our position to (partially) address this gap is to acquaint microservices practitioners with security discussions scattered in the issue tracking systems of microservices systems. We define security discussion as “a paragraph from developer discussions (conversations) that includes design decisions, challenges, or solutions relating to security”. In issue tracking systems, thousands of discussions about various topics can happen among developers. Hence, reading issue discussions and then deciding which of them or which parts of an issue include security discussion would be tedious and error-prone for practitioners. To this end, we developed a **machine learning-based tool** that can **automatically** identify security discussions with **high accuracy** from a large number of issue discussions in microservices systems.


As an example, this repo shows how our tool can distinguish security discussions from non-security discussions in issue [303](https://github.com/moleculerjs/moleculer/issues/303), [72](https://github.com/moleculerjs/moleculer/issues/72) and [100](https://github.com/moleculerjs/moleculer/issues/100) from the [moleculer](https://github.com/moleculerjs/moleculer) project.

**Example of Issues:**

* [The HTML preview of issue 303 from moleculer project](http://htmlpreview.github.io/?https://github.com/RezaeiNasab/SD_MSA/blob/main/Question%20on%20how%20to%20use%20this%20framework%20·%20Issue%20%23303%20·%20moleculerjs:moleculer.html) 
* [The HTML preview of issue 72 from moleculer project](http://htmlpreview.github.io/?https://github.com/RezaeiNasab/SD_MSA/blob/main/AMQP%20Transporter%20by%20Nathan-Schwartz%20·%20Pull%20Request%20%2372%20·%20moleculerjs:moleculer.html)
* [The HTML preview of issue 100 from moleculer project](http://htmlpreview.github.io/?https://github.com/RezaeiNasab/SD_MSA/blob/main/Wishlist%20·%20Issue%20%23100%20·%20moleculerjs:moleculer.html)


---
### NOTE

The ***highlighted texts in green*** are detected by our machine learning-based tool as a security discussion.

---
