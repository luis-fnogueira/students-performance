# students-performance
EDA with Kaggle's dataset about students performance.

The main goal of this study is to understand how this dataset is distributed, doing an descriptive analysis.

### The dataset

Here's how the dataset look like in a Pandas Dataframe:

![Captura de tela de 2022-06-02 15-31-36](https://user-images.githubusercontent.com/82065199/171701568-0f6945cb-5b8c-4b7c-abe1-c6e371fe300a.png)


First looking at the grades (which are the quantitative variables) one can see that the grades are relatively similar among them. There is no big difference when we look at the quartiles and medians.
What brings attention in this first glance is that we have only a zero grade in math, it can be just an outlier, but it could be a point of attention. 

![Captura de tela de 2022-05-23 22-04-47](https://user-images.githubusercontent.com/82065199/169928000-a6f86bdc-64d8-4d79-ae53-d53bc2f13dd5.png)

This dataset has 1000 rows duly filled

![Captura de tela de 2022-05-24 21-42-01](https://user-images.githubusercontent.com/82065199/170154492-d30ffbf7-e729-48fb-bd8c-3cd2f60bc384.png)


### Math scores

![box-math](https://user-images.githubusercontent.com/82065199/175425074-f63c3803-2cce-4825-bfdd-d2b65ebe4e70.png) ![hist-math](https://user-images.githubusercontent.com/82065199/175425101-f53b3e26-9329-421e-81ec-4e7d5a123265.png)

As seen earlier, math has the lowest grades compared to the other matters. Besides the low outliers, the distribution seems normal.

### Reading scores

![BOX-READING](https://user-images.githubusercontent.com/82065199/175425530-e4429c12-b7f3-45a9-88f8-55f45a9ed652.png) ![hist-reading](https://user-images.githubusercontent.com/82065199/175425558-3c3de4bb-dda0-4f80-82c0-4da294f9232b.png)


Reading scores distribution also seems normal.

### Writing scores


![box-writing](https://user-images.githubusercontent.com/82065199/175425641-d9604de2-ffee-4401-a3d1-5248cfa0e032.png) ![hist-writing](https://user-images.githubusercontent.com/82065199/175425666-7fc8f86e-1635-46d6-a933-79ae02110912.png)


And lastly the distribution of writing scores also seems normal. In a way, all scores are similar to each other.

### Correlation

![Captura de tela de 2022-06-01 15-34-43](https://user-images.githubusercontent.com/82065199/171477654-0d17053e-ec5b-496e-a2de-47ba4d3f511d.png)

Those three variables have a strong positive correlation, mainly writing and reading.

### Proportion by sex

![sex](https://user-images.githubusercontent.com/82065199/175425802-720df478-0fbf-44eb-85e8-84999aef60ac.png)


In this dataset we have almost a division of 50/50 by sex. We have a little bit more men in the research.

### Parental level of education

![Captura de tela de 2022-06-01 15-38-54](https://user-images.githubusercontent.com/82065199/171478344-f1e35a5d-9538-4225-b4f4-d68782b3731a.png)

Student's parents have "some college" and "associate degree". 

### Lunch

The majority of students prefer the standart lunch.

![Captura de tela de 2022-06-01 15-41-08](https://user-images.githubusercontent.com/82065199/171478687-1d744dcd-6fcb-4f31-91b6-32f0fe5d0712.png)

### Race

![race](https://user-images.githubusercontent.com/82065199/175425859-2f951330-e38f-42cf-bd92-e25b1acee667.png)

Most students are of Race C and the less represented group is Race A



