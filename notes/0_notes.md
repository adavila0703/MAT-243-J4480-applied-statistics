# Notes

> Notes containing major notes that I need to take.

## Week 1

### 1.1

- A **quantitative variable** can take on a numeric value (quantitative data) that can be measured and ordered. Ex: A person's age, the outside temperature, and a meal's price are quantitative variables. Example numeric values are an age of or years, a temperature of or degrees, and a price of or dollars.

- A **categorical variable** can take on the value (usually a label) of one of several categories. Ex: A person's gender, seasons, and U.S. companies are categorical variables. Gender can be male or female, seasons can be fall, winter, spring, or summer, and U.S. companies can be Wal-Mart, McDonalds, UPS, etc. A categorical variable is often called a qualitative variable (known by qualities, rather than quantities).

- A **nominal variable**'s categories have no ordering, existing in name only, like apples, oranges, and grapes. ("Nominal" means "in name only").

- An **ordinal variable**'s categories have an ordering, like disagree, neutral, and agree.

- A **continuous variable**'s values are infinite along a continuum of values within a range, typically real numbers. Continuous variables usually represent measurements, like height ( meters) or temperature ( degrees).

- A **discrete variable**'s values are finite within a range, typically integers. Discrete variables usually represent countable items, like people in a family () or cars in a city (). Generally, if "number of" can be added to the beginning, the variable is discrete, like "number of people in a family", but not "number of height". Note: "Discrete" means separate or distinct, not to be confused with "discreet" which means careful or unobtrusive.

### Pandas - DataFrame

#### Attributes

| DataFrame.attribute | Description of output                                  |
| :------------------ | :----------------------------------------------------- |
| axes                | Index and column labels                                |
| columns             | Column labels                                          |
| dtypes              | Data types of values in each column                    |
| index               | Index labels                                           |
| shape               | Ordered pair that gives the number of rows and columns |
| size                | Number of values in the DataFrame                      |
| values              | Values in the DataFrame                                |

#### Methods

| DataFrame.method | Description of output                              |
| :--------------- | :------------------------------------------------- |
| describe()       | Summary statistics for numerical columns           |
| head(), tail()   | First/last rows in the DataFrame                   |
| min(), max()     | Minimum/maximum of values in a numerical column    |
| mean(), median() | Mean/median of values in a numerical column        |
| sample()         | Random row                                         |
| std()            | Standard deviation of values in a numerical column |

### Percentile

![percentile](./images/percentile.png)
