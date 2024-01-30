# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- Power BI / Tableau specific: We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix` or `ex-1-initial.yxmd`, depending if you are auditioning for a Tableau/Power BI/Alteryx course.
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix` or `ex-1-sol.yxmd`

#### Learning Objective

*learn how you isolate the data through visuals only and interpret the charts correctly to get the answers to anomalous performance pattern*

#### Context

*This skill is absolutely crucial for all analyst to actually leverage the dashboards and extract anomalies & outliers and also pinpoint where and when the outlier was, so that right actions could be taken timely.* 

#### Steps to be executed by the student (max 6)


1.	Go to the bottom line by subcategory visual at the bottom of the dashboard
2.	Scroll down to the very bottom of the visual, see Tables (Sub category) with negative bottomline of 0.06mn
3.	Click it, and then go to the bottomline by markets and see that Asia Pacific is the most loss making market (19.9k), click it while pressing Ctrl key
4.	Now go to the YoY bottomline comparison and see which point in the line is the lowest (June 2012 = $ 3,056)


#### Exercise question:
*TDid we lose money in any sub category? Which market was majorly responsible (give me both absolute and net margin loss) and when did we lose the most? *


#### End goal:
https://drive.google.com/file/d/1rKsxYY0hKKR7uGhg5-eACensVTFntTco/view?usp=sharing


## 2nd VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-2-intial.twbx` or `ex-1-initial.yxmd`, depending if you are auditioning for a Tableau/Power BI/Alteryx course.
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-2-sol.twbx` or `ex-2-sol.pbix` or `ex-1-sol.yxmd`

#### Learning Objective

*learn how you isolate the data through combination of visuals and filters and answer questions from business users.*

#### Context

*This is also vital for analyst to be able to leverage the dashboards and quickly extract right answers to questions from business teams across the organization such as sales team in this case.*

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

1.	Select France from the country filter.
2.	Select Corporate from the segments tile
3.	Go down to the topline by customers bar chart and see the top value (Odella Nelson >> $6.2K)
4.	Click the bar chart to isolate that customer
5.	Now go up and select 2012 from the year filter
6.	Check gross sales for the 2012 account value ($ 6,677)


#### Exercise question:
*Who is our biggest corporate customer in France, and what was his/her account value in 2012?*

#### End goal:

https://drive.google.com/file/d/1CG7SqLJEt9L3ICyLLwvs-JI1R7WC_W8Q/view?usp=sharing

