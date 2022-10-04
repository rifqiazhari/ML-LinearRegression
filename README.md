# Simple Linear Regression
- Create the table using mouse data sample<br/>
`mouse.data <- data.frame(`<br/>
&emsp;&emsp;`weight=c(0.9,1.8,2.4,3.5,3.9,4.4,5.1,5.6,6.3)`<br/>
&emsp;&emsp;`size=c(1.4,2.6,1.0,3.7,5.5,3.2,3.0,4.9,6.3)`<br/>
`)`<br/>
<br/>
- Plot to see the relationship between size and weight<br/>
`plot(mouse.data$weight, mouse.data$size)`<br/>
<br/>
- We want to predict size by weight, so we pull up the linear model function<br/>
`mouse.regression <- lm(size ~ weight, data=mouse.data)`<br/>
`summary(mouse.regression)`<br/>
