
# Telecommunication-Churn-Prediction

Business Objective: Customer churn is a big problem for telecommunications companies. Indeed, their annual churn rates are usually higher than 10%. For that reason, they develop strategies to keep as many clients as possible. This is a classification project since the variable to be predicted is binary (churn or loyal customer). The goal here is to model churn probability, conditioned on the customer features.

Data Set Details: Each row corresponds to a client of a telecommunications company for whom it has collected information about the type of plan they have contracted, the minutes they have talked, or the charge they pay every month.

The data set includes the following variables:

●	state: Categorical, for the 51 states and the District of Columbia.

●	Area.code

●	account.length: how long the account has been active.

●	voice.plan: yes or no, voicemail plan.

●	voice.messages: number of voicemail messages.

●	intl.plan: yes or no, international plan.

●	intl.mins: minutes customer used service to make international calls.

●	intl.calls: total number of international calls.

●	intl.charge: total international charge.

●	day.mins: minutes customer used service during the day.

●	day.calls: total number of calls during the day.

●	day.charge: total charge during the day.

●	eve.mins: minutes customer used service during the evening.

●	eve.calls: total number of calls during the evening.

●	eve.charge: total charge during the evening.

●	night.mins: minutes customer used service during the night.

●	night.calls: total number of calls during the night.

●	night.charge: total charge during the night.

●	customer.calls: number of calls to customer service.

●	churn: Categorical, yes or no. Indicator of whether the customer has left the company (yes or no).



## Model

For predicting the churn I have used multiple models and selected XGBoot model which was giving the best accracry according to the evaluation metric (Used Precision,Recall and F1 score as Evaluation metric because the dataset was unbalanced)


## Forecasting App
[![Open in Streamlit](http://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ahmed-sayed99-telecommunication-churn-prediction-app-r44rpn.streamlit.app/) 👈 Click here!

## Author

<table>
<tr>
<td>
     <img src="https://avatars.githubusercontent.com/u/117753954?v=4" width="180" align="center"/>
     
     ahmedsaiyed17a@gmail.com

<p align="center">
<a href = "https://github.com/Ahmed-Sayed99"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/ahmed-saiyed//"><img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36"/></a>
</p>
</td>
</tr> 
  </table>


