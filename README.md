# Quantitative Value Trading
The following repository contains the second project I did with guidance from @nickmccullum and his "Algorithmic Trading Using Python" course on youtube. <br>
I have taken the initiative to make my own changes: <br>
-- I have implemented a screening process to delete any companies for which any metrics are not returned from the API call. 
This will only work if there are less than 20 companies for which we don't have values. If there are more than 20, 
I have used the mean of the other values to not skew the data too drastically. <br>
-- Moreover, the portfolio is weighted on the RV Score rather than doing an equal weight portfolio with the top 50.<br>
