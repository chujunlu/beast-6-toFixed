# beast6
1.I incorporated accounting.unformat() to process the value that is passed in, in order to replicate accounting.toFixed() to my best effort. However, I think it is better to return a typeError if value is not a number.
2.I decided to round -0.5 further away from 0, which is different from accountingJS. For example, accounting.toFixed(-0.615, 2) ==> "-0.61"; but my toFixed function will return "-0.62," which aligns with Excel's number rounding and financial rounding.
