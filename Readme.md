**To rotate logs and split them every 1 hour to avoid endurance test results getting crashed or high memory issue**

**follow below two steps:-**

1.jmeter.properties file

update this line 

jmeter.save.saveservice.autoflush=true

*This will help reduce high memory issue*

2.jmeter -l results_$(date +%H).jtl


**Last Updated  23:33  19/07/2025
Hariprakash S**
