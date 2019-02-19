# Final project for cloud computing

# Predicting Amazon Spot Prices 

Amazon spot instances provide preemptable computing capacity using an unused EC2 instance that is available that is available for less than On-Demand price. Spot instances are charged at the current spot price: a mutable price which changes based on the supply and demand of these instances. Because the spot instances are available at steep discounts (usually up to 90%), it helps lowering the use of Amazon EC2 cost significantly. However, these instances are highly unpredictable and can be rescinded by Amazon with as little as two minutes warning. Given its significant discounts – there has been a significant interest in the scientific cloud computing community to move towards spot instances for workload and that are fault-tolerant and flexible. Thus, the need of predicting the accurate pricing in the future is important for a cost-effective use of this instance. We will explore the current models being used for the same and try to implement other models to compare with the existing models.

Here we implement ARIMA and LSTM-dense neural network architecture to try and predict the prices and compare them to see which is a better model.

# ARIMA 

ARIMA stands for auto-regressive integrated moving average. for predicting future points in the series), in such a way that :a pattern of growth/decline in the data is accounted for (auto-regressive), the rate of change of the growth/decline in the data is accounted for (integrated), noise between consecutive time points is accounted for (moving average).
