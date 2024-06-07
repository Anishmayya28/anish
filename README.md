he catplot code to show the scatterplot of  FlightNumber vs LaunchSite with x as FlightNumber, and y to Launch Site and hue to 'Class’ is


1 point

 sns.catplot(y="LaunchSite",x="FlightNumber",hue="Class", data=df, aspect = 1,kind=’cat’)

plt.ylabel("Launch Site",fontsize=15)

plt.xlabel("Flight Number",fontsize=15)

plt.show()



 sns.catplot(y="LaunchSite",x="FlightNumber",hue="Class", data=df, aspect = 1)

plt.ylabel("Launch Site",fontsize=15)

plt.xlabel("Flight Number",fontsize=15)

plt.show()



sns.catplot(y="LaunchSite",x="FlightNumber",hue="Class", data=df, aspect = 1,kind=’scatter’)

plt.ylabel("Launch Site",fontsize=15)

plt.xlabel("Flight Number",fontsize=15)

plt.show()



sns.catplot(y="LaunchSite",x="FlightNumber",hue="Class", col=”Class”, data=df, aspect = 1)

plt.ylabel("Launch Site",fontsize=15)

plt.xlabel("Flight Number",fontsize=15)

plt.show()
