### Relevant Terms explain
<details>

``` javascript
- Business: related to the financial aspect of that activity
  - Data: 
    > Qualitative: contains no number
      >> comes in the form of text and is descriptive in nature
      >> ex: business feedback, a business case study
    > Quantitative: numeric data
      >> Quantifiable information that can be involved in statistical and mathematical computations
      
    > Analysis: past performance
    > Analytics: future performance
    
- What does a data analyst do?
  > Data gathering/data collection
  > Data cleaning
  > Data preprocessing
  > Data visualization and analysis
  
 - Jupyter Shortcuts: "H" - open the keyboard shortcuts

- Types of Analysis:
  > Descriptive Analytics: What happened?
  > Diagnostic Analytics: Why did it happen?
  > Predictive Analytics: what will happen?
  > Prescriptive Analytics: How can we make it happen?

- A/B Testing
  > What?: experimentation technique, used to understand the effects of [potential] change to a company's products
  > Why?
    >> You already have a functioning product and are worried about the change
    >> You need to quantify the impacts (ie. you need to know how much the impact is)
  > Requirement:
    >> Infrastructure
    >> Statistical testing and experimental testing

```
</details>

### Basic Python
<details>

```python
- List:
  > List.append(value): add a value into a list
  > List.extend([value1, value2]): add value1 and value2 into a list
  > del List[index]: delete a value at index
  > List[1:3] : slice elements 1 and 2 from a list
  > List.index(value): find the index of a value in a list
  > List.sort(reverse = True): sort the list in reverse order
  
- Loops:
  > for n in list_name:
    print(n, end = " ")
    # print a list horrizontally
  
  > x = 0
  > while x <= 20:
    print(x)
    x += 2 #incrementing x
    
  > for item in x:
    print (item, end = " ")
    
  > for n in range(len(x)):
    print (x[n], end = " ")
    
- Imoprt modules:
  > Option 1:
    >> import math
    >> math.sqrt()
  > Option 2:
    >> from math import sqrt
    >> sqrt(25)
  > Option 3:
    >> from math import sqrt as s
    >> s(36)
  > Option 4:
    >> import math as m
    >> m.sqrt(49)
  > Option 5:
    >> from math import *
    >> sqrt(49)
  
```
</details>

### Pandas
<details>

```python
- import text file into python:
  > fileName = "source.txt"
  > file = open(fileName, mode='r')
  > fileContent = file.read() #read only once, so better to save it into variable fileContent
  > print(fileContent)
  
  # We should always close the connection to avoid any risk of being hacked
  > file.closed # True / False - check the status of open connection
  > file.close() # close the connection

- Professional way to open a file:
  > with open(fileName, mode='r') as file:
      fileContent = file.read() # the file will be closed automatically
      file.write("new content")
  > print(fileContent)

```
</details>
