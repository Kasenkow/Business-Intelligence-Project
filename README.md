# Business-Intelligence-Project
Predicting telemarketing success in the banking sector. An assignment based on Moro, Cortez and Rita (2014) “ A data-driven approach to predict the success of bank telemarketing ”

## Introduction
Marketing selling campaigns are a ubiquitous strategy to improve sales and enhance business across
a wide variety of industries. Telemarketing is a specific type of sales campaign that is operationalized
through a contact center. Typically, telemarketing can be divided into inbound and outbound contacts,
where customers contact the communication center on their own initiative or are contacted on the
initiative of a sales agent, respectively.
The student project will be based on the paper of Moro et al. (2014), in which the authors apply data
mining techniques to predict the success of telemarketing campaigns in the banking sector. Moro et
al. collect data on a telemarketing campaign from a Portugese bank, which aims to sell their customers
a subscription to a long-term deposit. They perform their own feature selection to derive a set of 22
features and proceed to fit models using Logistic Regression (LR), Decision Trees (DT), Support Vector
Machines (SVM) and Neural Networks (NN).

## Assignment
You and your teammates are data analysts at a consultancy company that provides their clients with
data driven suggestions on a wide range of business problems. You have been approached by a
Portugese bank, lets call them Sberbankos, to help them gain insights for what type of people in their
pool of prospective customers their telemarketing is most effective. Using this information, they will
be able to direct their campaigns better, reducing their marketing costs and minimizing intrusion from
unwanted sales calls to uninterested prospects.
Sberbankos also asked for help in predicting future revenues from their ongoing campaign. They have
data available on a set of customers whom have already decided whether to subscribe to the long-
term deposit and those who have rejected the proposal. Furthermore, they possess data on a large
set of potential customers whom have been contacted by Sberbankos, but for whom they do not know
yet whether they will accept the subscription. You are requested to forecast which of these potential
customers will eventually subscribe to the long-term deposit.

## Data
On the shared folder Business Intelligence/student project you will find the files “training data” and
“test data”. Both files contain real data on 16 features (variables), describing some demographic and
campaign-related characteristics for each (potential) customer. The training dataset contains 10,000
randomly selected instances of existing customers. From these instances you know the output variable
y, which states whether the contacted person became a subscriber to the long-term deposit. This
information is not available for the dataset with potential customers, which consists of another 2,000
randomly selected instances of potential future customers. You can find the description of each
variable in the file “Variables”.

## Instructions
You must write a report to the management team of Sberbankos. Your analysis needs to consist of
two components: (i) a descriptive investigation aimed at understanding the current and potential
customer database and (ii) a predictive exercise in which you predict whom of the potential customers
will subscribe to the long-term deposit...
...
Just as in real life, you often are required to decide on the most important purpose of your forecast
model. Since Sberbankos did not tell you how they want to use the predictions, you need to make
three different models:
1. a model that aims to achieve the highest accuracy,
2. a model that aims to deliver the highest possible true-positive rate while trying to keep the
false-positive rate below 10%, and
3. a model that aims to achieve the best Area Under the Curve (AUC) metric as discussed in the
second workshop.
