QTD Sales = TOTALQTD(SUM(Amazon_Data[Price(Dollar)]),'Date Table'[Date])

YTD Products Sales = TOTALYTD(COUNT(Amazon_Data[Product Category]),'Date Table'[Date])

YTD Reviews = TOTALYTD(SUM(Amazon_Data[Number of  reviews]),'Date Table'[Date])

YTD Sales = TOTALYTD(SUM(Amazon_Data[Price(Dollar)]),'Date Table'[Date])

Month Number = MONTH('Date Table'[Date])

Quatr num = QUARTER('Date Table'[Date])

QUTR = CONCATENATE("QTR", 'Date Table'[Quatr num])

week num = WEEKNUM('Date Table'[Date])

YTD Sales = TOTALYTD(SUM(Amazon_Data[Price(Dollar)]),'Date Table'[Date])

