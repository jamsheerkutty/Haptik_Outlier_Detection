## About Haptik

Haptik is India’s first Conversational Commerce platform that is powered by both AI and real
humans and we aim to redefine the way people get their everyday jobs done using chat as the
underlying interface.
A combination of Artificial Intelligence, Natural Language Process & Machine Learning has
helped Haptik create technology that assists their assistants work a lot faster; while the bot
learns every time a new query is answered.

### In short:
Haptik caters to a limited number of services. Users tend to ask queries, out of the scope of
Haptik’s reach. To identify these queries as outliers and handling those by gentle denial is the
best practice.

### Description:

Haptik provides help with a limited set of services to users. These being: Flights, Trains, Cabs,
Reminders, Recharge, Nearby. Though, these categories are clearly mentioned on the platform,
as the interaction medium being chat, users often ask queries which are out of scope of Haptik.
For Example:-
-What is the price of Iphone 7?
-Can you get me an appointment with physiotherapist?
-HSC results
-I want to download a hollywood movie for free. Please tell me a good website

Though, humans can most of the times cater to these queries with web-search, it is better to not
to cater to such queries as it creates a different/false image of Haptik as a service/product. We
call the queries which are out of scope of Haptik as, “outliers”. The outlier detection also helps
other modules such as domain classifier, to remove noisy data from training set.
How do we solve this problem? An important fact to notice is that most of the queries fall under
the scope of Haptik and only a small portion of queries fall under the Outliers category. The
outlier queries are small in number, while the types of queries has a wide range of variety. Does
this hint towards unsupervised approaches? Anomaly detection? What are the commonly used
algorithms for anomaly detection? Do these work good for text data? What about large feature
vectors? Would clustering with little human intervention work?
Formally, given a large set of strings, the task is to identify potential candidate strings which are
different from most of the queries.

### Datasets:
The dataset contains a large set of strings, most belonging to either of the domains catered by
Haptik, or casual/generic queries.
