# Stock_market_prediction_during_WARPERIOD
Stock market prediction of Two major subsidiaries of Ukraine and Russia during War period.
Investors and traders on the stock exchange may sell and buy shares, shifting its value
high or low. Stock values are based on supply and demand, so the ultimate goal of
shopping for stocks is to create cash by purchasing securities that are assumed to be worth
is expected to rise. Stocks are closely coupled with the planet of economic science —the
risee and falls of share costs is copied directly from some Key Operating Indicators
(KPI&#39;s). The 5 most ordinarily used KPI&#39;s are the gap stocks value (open), ending of day
value (close), intraday low value (Low), intra peak day value (high), and total amount of
stocks listed over the course of the
day (volume)

Our project goal is to apply Bidirectional LSTM recurrent neural networks to
forecast the adjusted final market price for a portfolio of securities, the maximum goal
right here is to get the best skilled algorithmic software, to expect destiny returns.

Proposed Model:

The main role of the Bi-LSTM is to decide the information that needs to be hold
and the information that needs to be discarded from the Bi-LSTM
 This is the conclusion reached by the sigmoid layer. If the output is &#39;0,&#39; the
information is discarded; if the value is &#39;1,&#39; the information is kept.The next step is to choose the information that will be stored in our Bi-LSTM cell.
We have a LSTM layer followed by a Dropout of 30% for preventing complex co-
adaptions on training data.
 Next, we have few more layers of Neural networks with “elu” activation
(Exponential Linear Unit) which is a combination of tanh and relu activation.
 At last, Our output layer produces a better version of our cell state. We run it
through a linear function to acquire the output value we want.

![image](https://user-images.githubusercontent.com/87561916/174879230-58be4aa0-3eed-40d2-a64d-5a948d4daeb2.png)

Results:

We observed that the results were near and accurate when we compared them to the
actual ones.
2. We recommended integrating the attention mechanism which is dependent on the
size of the given input matrix with the help of this paper. It was created with the
numerous benefits of deep neural networks over other machine learning techniques
in mind.
3. for Binge and Renault, the graphs are between the real and the predicted values.
4. The X-axis shows the time period in which we forecast the stock price, while the
Yaxis shows the current stock price.
5. On X-axis, One unit is equals to 100 days, whereas one Y axis , one unit equals $20
in the training dataset.
6. On X-axis, One unit is equals to 20 days, whereas one Y axis , one unit equals $20
in the test dataset.

![image](https://user-images.githubusercontent.com/87561916/174879389-0b17415b-27d1-442d-b733-a302e9181f31.png)
![image](https://user-images.githubusercontent.com/87561916/174879434-6f188c43-32c7-4097-886e-ad19178ba707.png)



