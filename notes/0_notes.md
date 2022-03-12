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

### Research

- Normal distribution
- Central limit theorem

### Survey Sampling

- Descriptive statistics focuses on summarizing survey data about a sample drawn from a population. Summary statistics include measures of central tendency such as mean, median, and mode; and dispersion such as range and standard deviation. Descriptive statistics cannot make conclusions based on the data. Rather, descriptive statistics is a way to present data in a meaningful way.

- Inferential statistics focuses on using information from the sample to make conclusions about the population from which the sample was drawn. The two primary methods of inferential statistics are confidence intervals, which specify the range within which a parameter falls with a given probability, and hypothesis testing, which allows differences between population parameters to be compared.

- Surveys are conducted to allow statisticians to make generalizations about a population.

- A population is any collection of objects, people, or things about which statistical inference are made. A parameter of a population is a numerical characteristic of a population, such as mean, median, or standard deviation.

- A sampling unit is an individual in the population on which a measurement can be taken.

- The sampling frame is the subset of the population from which a sample is drawn.

- The sample is composed of the sampling units that provide data to be collected.

- A statistic is a numerical characteristic of a sample, rather than the population.
