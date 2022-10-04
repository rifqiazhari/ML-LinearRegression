# Simple Linear Regression
- Create the table using mouse data sample<br/>
`mouse.data <- data.frame(`<br/>
&emsp;&emsp;`weight=c(0.9,1.8,2.4,3.5,3.9,4.4,5.1,5.6,6.3)`<br/>
&emsp;&emsp;`size=c(1.4,2.6,1.0,3.7,5.5,3.2,3.0,4.9,6.3)`<br/>
`)`

![alt text](Picture2.png)
<br/>

- Plot to see the relationship between size and weight<br/>
`plot(mouse.data$weight, mouse.data$size)`<br/>
![alt text](ddbfd72c-8d63-415b-bccf-a9e04de76225.png)

- We want to predict size by weight, so we pull up the linear model function<br/>
`mouse.regression <- lm(size ~ weight, data=mouse.data)`<br/>
`summary(mouse.regression)`<br/>
![alt text](Picture3.png)

- Then we plot the regression line<br/>
![alt text](57f5e046-02bf-4fac-84d1-b1893ab289e4.png)

- Then we plot the regression line<br/>
![alt text](57f5e046-02bf-4fac-84d1-b1893ab289e4.png)

# Multiple Linear Regression
- Create the table with three variables<br/>
`mouse.data2 <- data.frame(`<br/>
&emsp;&emsp;`size=c(1.4,2.6,1.0,3.7,5.5,3.2,3.0,4.9,6.3),`<br/>
&emsp;&emsp;`weight=c(0.9,1.8,2.4,3.5,3.9,4.4,5.1,5.6,6.3),`<br/>
&emsp;&emsp;`tail=c(0.7,1.3,0.7,2.0,3.6,3.0,2.9,3.9,4.0)`<br/>
`)`<br/>

- Plot the data<br/>
![alt text](ce61e5db-d69d-44da-918d-d42b75999eb2.png)

We can see the correlation between size(y) and weight(x1)<br/>
We can see the correlation between size(y) and tail(x2)<br/>
We can see the correlation between weight(x1) and tail(x2)<br/>

- We want to predict size using weight and tail<br/>
![alt text](Picture5.png)


