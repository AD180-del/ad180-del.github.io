---
title: "Women in Asia: Introduction"
series: "Women in Asia"
layout: default
hidden: true
part: 1
---
{% assign essay_parts = site.coursework-collection | where: "series", "Women in Asia" | sort: "part" %}
{% assign current_index = page.part | minus: 1 %}

{% assign previous_index = current_index | minus: 1 %}
{% if previous_index >= 0 and essay_parts[previous_index] %}
[Previous Part]({{ essay_parts[previous_index].url }})
{% endif %}

{% assign next_index = current_index | plus: 1 %}
{% if next_index < essay_parts.size and essay_parts[next_index] %}
[Next Part]({{ essay_parts[next_index].url }})
{% endif %}

# Introduction

Demography is a truly unequal phenomenon in the world. While some parts have an extremely dynamic one with a high ration of births for deaths, some are aging and face real challenges. The French President Emmanuel Macron has thus talked about "demographic rearmament" [^1], the idea that the French people need more births than before to offset the aging population (it is also tightly linked to the unbalanced social security system where less and less workers will have to pay for more and more retirees). One may joke about the term "demographic rearmament". One may think that Emmanuel Macron is right and that the aging Europe needs to renew its population or it will meet its end. However, one must think about the underlying thoughts of a "demographic rearmament". Who is most needed to conceive a child? Women. Who will have to bear during nine months the weight of the baby, both physically, mentally, and socially? Women. Therefore, who could be the target of a demographic rearmament? Women. It is quite pernicious for the French President to one day support the enshrinement of abortion right into the Constitution, and the day after, tell women that they need to produce more offsprings. In the same fashion that some men want to control women's body by forbidding them access to abortion, asking women to make babies is a way of controlling their body. This two-faced way of thinking only deters further women's right even in countries that everyone can agree on being liberal democracies (apart from those living in them). In Asia, even strong democracies such as Japan are faced with the challenge and governments attempt to change the trajectory of demography. Japan's Prime Minister Shigeru Ishiba thus declared "The low birth rate and the resulting population decline are a challenge to the very foundations of the country — a quiet emergency, so to speak" [^2]. Since then, the Japanese government has approved a measure to give government employees four-day workweek to boost fertility and family time [^3]. The example of Japan highlights the stale situation of birthrate and fertility in Asia, as well as the stakes behind the decisions that lie before governments. On the one hand, a "vital issue" that needs to be taken care of, on the other hand, possibly impeding on liberties. As long as governments incentivise the people into making more children, there does not seem to be any offence to liberal democracy principles. However, when looking at how governments throughout history have decided to implement laws and birth control in the name of their fear of "the population bomb" [^4] and other Malthusian theories [^5], it is undisputable that freedom is infringed in the process. Therefore, we will have a look at how the situation of women in Asia is a good case to demonstrate the challenges that democracies and democratisation are faces with. 


[^1]: Cordier, S. (2024, January 17). ‘Demographic rearmament’: Macron plans to reform parental leave and fight infertility. Le Monde. https://www.lemonde.fr/en/france/article/2024/01/17/demographic-rearmament-macron-plans-to-reform-parental-leave-and-fight-infertility_6440096_7.html

[^2]: AFP. (2024, October 4). Japan’s Low Birth Rate A ‘Quiet Emergency’: PM. Barron’s. https://www.barrons.com/news/japan-s-low-birth-rate-a-quiet-emergency-pm-897f48c6

[^3]: Asada, Y., Ancheta, N., & Lau, C. (2024, December 6). Tokyo government gives workers 4-day workweek to boost fertility, family time. CNN. https://www.cnn.com/2024/12/06/asia/tokyo-government-4-day-workweek-intl-hnk/index.html

[^4]: Ehrlich, P. R. (with Internet Archive). (1968). The Population Bomb. Ballantine Books. http://archive.org/details/populationbomb00ehrl

[^5]: Morand, S., & Lajaunie, C. (2018). Biodiversity and Health Scenarios. In S. Morand & C. Lajaunie (Eds.), Biodiversity and Health (pp. 147–171). Elsevier. https://doi.org/10.1016/B978-1-78548-115-4.50010-X
