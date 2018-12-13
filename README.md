# beast6
This is an exercise for watchandcode.com course content. Students submitted their answers here: https://github.com/gordonmzhu/beasts/issues/7
1. I incorporated accounting.unformat() to process the value that is passed in, in order to replicate accounting.toFixed() to my best effort. However, I think it is better to return a typeError if the value is not a number.

2. I decided to round -0.5 further away from 0, which is different from accountingJS. For example, accounting.toFixed(-0.615, 2) ==> "-0.61"; but my toFixed function will return "-0.62," which aligns with Excel's number rounding and financial rounding.

3. I learned a lot from reading other students' solutions. After learning from you, I was able to refactor my code to a more succinct and efficient fashion. I didn't use array manipulation or String.prototype.substr() (it is deprecated on MDN). But thank you for showing me the many possible methods to solve the same question. Thank you for all your sharing and keep up with the excellent work.
