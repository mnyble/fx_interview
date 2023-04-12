### **Task**

Create and endpoint that calculates average, max and min fx rate between two currencies for a custom period of time. Either both start date and end date of period are provided, or none. If none provided, then return exchange rate for today.

The historical exchange API: https://freecurrencyapi.com/docs/historical#request-parameters

API Key: Q3N4TUMCH2odhogpwNdVrlYLRd40MwsoLgzv4dQO

**Bonus points for:**
1. Following all REST guidelines
2. Using dependency injection (with interfaces)
3. Plugging in swagger (do not forget proper action annotations)
4. Proper handling of exceptions
5. Clean and easy to understand code. The logic needs to be easy to follow. It's better if easy to follow without any comments, but comments are accepted
6. Unit tests (one unit test is enough - any library is accepted)
7. Writing a usable exchange API mock service

**Not important for this exercise:**
1. Logging
2. Authentication
3. Number of decimal points (i.e. do not worry about rounding)