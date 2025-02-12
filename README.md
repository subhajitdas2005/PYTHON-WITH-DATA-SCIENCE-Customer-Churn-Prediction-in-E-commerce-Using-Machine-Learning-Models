# PYTHON-WITH-DATA-SCIENCE-Customer-Churn-Prediction-in-E-commerce-Using-Machine-Learning-Models

axx = sns.countplot(x='HourSpendOnApp', data=data)
for a in axx.patches:
    axx.annotate(format((a.get_height()/5630)*100,'.2f'), (a.get_x() + a.get_width()/2., a.get_height()),\
                ha='center',va='center',size=12,xytext=(0, 6),textcoords='offset points')
plt.title("Distribution of hours spent on the app by the customers")
plt.show()

# x axis shows the number of coustomers 
# y axis shows the number of hours spent on the app 
