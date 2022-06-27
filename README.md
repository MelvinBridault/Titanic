*"There is magic in graphs. The profile of a curve reveals in a flash a whole situation — the life history of an epidemic, a panic, or an era of prosperity. The curve informs the mind, awakens the imagination, convinces."*
<p align="right"> 
Henry D. Hubbard, Creator of the Periodic Table of Elements
</p>

# WORK IN PROGRESS

Over time, this notebook will cover also data cleaning, feature engineering, exploratory data analysis, mapping, feature importance, correlations, machine learning, model selection and evaluation of the model.

I highly recommend [nbviewer](https://nbviewer.org/) to explore my notebook  :relaxed:

<p align="center">                                                                                                                      
  <a href="https://user-images.githubusercontent.com/73826011/150744607-3fb04f60-cdb9-4f15-a328-d33145f91417.png">
    <img alt="graph" src="https://user-images.githubusercontent.com/73826011/150744607-3fb04f60-cdb9-4f15-a328-d33145f91417.png"/></a>
</p>


| **Feature Name** | **Description**                        | **Data Type**           | **Key**                                           | **Used in Model?** |
|------------------|----------------------------------------|-------------------------|---------------------------------------------------|------|
| `Name`           | Passenger Name                         | `str` - Nominal         |                                                   | ❌ |
| `Ticket`         | Ticket Number                          | `str` - Nominal         |                                                   | ✅ |
| `Cabin`          | Cabin Number                           | `str` - Nominal         |                                                   | ✅ |
| `Embarked`       | Port of Embarkation                    | `str` - Nominal         |C - Cherbourg<br>Q - Queenstown<br>S - Southampton | ❌ |
| `Sex`            | Male or Female                         | `str` - Nominal         |                                                   | ❌ |
| `Pclass`         | Proxy for socio-economic statut        | `int64` - Ordinal       |1 - Upper<br>2 - Middle<br>3 - Lower               | ✅ |
| `Passenger ID`   | Unique identifing # for each passenger | `int64` - Discrete      |                                                   | ✅ |
| `SibSp`          | # of Siblings or Spouses               | `int64` - Discrete      |                                                   | ✅ |
| `Parch`          | # of Parents or Children               | `int64`   - Discrete    |                                                   | ✅ |
| `Survived`       | Target variable                        | `int64`   - Discrete    |0 - No<br>1 - Yes                                  | ✅ |
| `Age`            | Passenger Age                          | `float64` - Continuous  |                                                   | ✅ |
| `Fare`           | Passenger Fare                         | `float64` - Continuous  |                                                   | ✅ |
