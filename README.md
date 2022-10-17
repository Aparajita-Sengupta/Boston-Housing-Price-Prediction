<img width="751" alt="Screen Shot 2022-10-17 at 5 21 34 AM" src="https://user-images.githubusercontent.com/110929917/196140610-87c59184-86b6-46d3-a437-062e19b4b850.png">
<img width="725" alt="Screen Shot 2022-10-17 at 5 22 35 AM" src="https://user-images.githubusercontent.com/110929917/196140799-ddd58c31-56f3-45a0-9ab6-02974ed45d44.png">

### About the data:

<img width="720" alt="Screen Shot 2022-10-17 at 5 23 23 AM" src="https://user-images.githubusercontent.com/110929917/196140991-f3433bf9-08b8-408b-8aef-f7b1a8b61425.png">


### Exploratory Data Analysis: 
#### Summary Statistics of this Dataset:
<img width="709" alt="Screen Shot 2022-10-17 at 5 26 53 AM" src="https://user-images.githubusercontent.com/110929917/196141850-a6612fde-f447-46f3-932d-cbb0b4bf2090.png">

#### Univariate Analysis:
<img width="782" alt="Screen Shot 2022-10-17 at 5 27 53 AM" src="https://user-images.githubusercontent.com/110929917/196143236-4b40b4d6-3500-4f3f-96bb-0f321019940d.png">
<img width="764" alt="Screen Shot 2022-10-17 at 5 28 05 AM" src="https://user-images.githubusercontent.com/110929917/196143251-c2f39227-559d-4277-b473-43f015c7db05.png">
<img width="503" alt="Screen Shot 2022-10-17 at 5 28 13 AM" src="https://user-images.githubusercontent.com/110929917/196143259-d6c58fba-a3d5-44e0-a964-f0b67947df12.png">

#### Bivariate Analysis
##### Correlation matrix based on heatmap:
<img width="689" alt="Screen Shot 2022-10-17 at 5 34 23 AM" src="https://user-images.githubusercontent.com/110929917/196143607-d4319e9e-9ea3-4f10-84b0-972138b5bb22.png">
<img width="941" alt="Screen Shot 2022-10-17 at 9 41 48 AM" src="https://user-images.githubusercontent.com/110929917/196192770-60744fad-99eb-43c0-b835-f81f812c740f.png">
<img width="961" alt="Screen Shot 2022-10-17 at 9 41 59 AM" src="https://user-images.githubusercontent.com/110929917/196192810-e385559f-82be-4bc5-8316-fa45dfbe3312.png">


##### Could any of the strong/weak correlations be due to outliers?
<img width="944" alt="Screen Shot 2022-10-17 at 5 35 51 AM" src="https://user-images.githubusercontent.com/110929917/196144267-b7ff1ad9-96f0-42e3-ba9b-cb4c7e965a49.png">
<img width="559" alt="Screen Shot 2022-10-17 at 5 36 08 AM" src="https://user-images.githubusercontent.com/110929917/196144292-25626425-3023-4c5e-b96f-c2c2c647e819.png">
<img width="887" alt="Screen Shot 2022-10-17 at 5 36 24 AM" src="https://user-images.githubusercontent.com/110929917/196144310-ed0a6592-7ce4-4685-8b83-f98bb9c5ec3a.png">
<img width="922" alt="Screen Shot 2022-10-17 at 5 36 36 AM" src="https://user-images.githubusercontent.com/110929917/196144332-9c530d78-b944-45df-8b98-074113f5dc75.png">
<img width="953" alt="Screen Shot 2022-10-17 at 5 36 47 AM" src="https://user-images.githubusercontent.com/110929917/196144349-bd029edc-e2b4-48ae-9c4f-860a5eac7e8d.png">
<img width="922" alt="Screen Shot 2022-10-17 at 5 36 59 AM" src="https://user-images.githubusercontent.com/110929917/196144367-72d4ad5e-ba9a-420a-9aa0-37b8c8ba61d0.png">

##### Checking correlation of TAX and RAD after removing outliers:
<img width="913" alt="Screen Shot 2022-10-17 at 5 39 41 AM" src="https://user-images.githubusercontent.com/110929917/196144816-f086113e-87be-4b8a-a546-f45ac21fba8e.png">
<img width="614" alt="Screen Shot 2022-10-17 at 5 39 59 AM" src="https://user-images.githubusercontent.com/110929917/196144860-5ffadc1c-80ca-446a-a3d7-a9d21d717984.png">
<img width="880" alt="Screen Shot 2022-10-17 at 5 40 12 AM" src="https://user-images.githubusercontent.com/110929917/196144871-b5cceb12-7328-4d7a-8fd5-d944346b8996.png">

### Regression Model:

<img width="444" alt="Screen Shot 2022-10-17 at 9 37 27 AM" src="https://user-images.githubusercontent.com/110929917/196191828-b4aed262-f988-4162-bf94-de9494e1a16a.png">

<img width="907" alt="Screen Shot 2022-10-17 at 9 38 16 AM" src="https://user-images.githubusercontent.com/110929917/196191863-1853d418-e6c8-4e28-b7ea-423e80658af6.png">
<img width="907" alt="Screen Shot 2022-10-17 at 9 38 24 AM" src="https://user-images.githubusercontent.com/110929917/196191884-d86410b7-d099-4dbf-bcfe-98252b7c81fc.png">
<img width="795" alt="Screen Shot 2022-10-17 at 9 38 40 AM" src="https://user-images.githubusercontent.com/110929917/196191901-d19013bd-6928-4cf3-b063-8689f0b1057f.png">

### Modelling after removing multicollinearity:
<img width="923" alt="Screen Shot 2022-10-17 at 9 45 03 AM" src="https://user-images.githubusercontent.com/110929917/196193967-e4858fb1-623f-49d7-8254-b618cb20b17c.png">

### Dropping features with P(t) > 0.05:
<img width="923" alt="Screen Shot 2022-10-17 at 9 45 28 AM" src="https://user-images.githubusercontent.com/110929917/196193991-36b1de12-7089-4c5a-9e90-e903af46e47d.png">

### Checking for the assumptions and rebuilding the model:
<img width="903" alt="Screen Shot 2022-10-17 at 9 45 52 AM" src="https://user-images.githubusercontent.com/110929917/196194072-b99ab79b-e6ad-49fe-bc39-41182dfbe844.png">
<img width="900" alt="Screen Shot 2022-10-17 at 9 46 12 AM" src="https://user-images.githubusercontent.com/110929917/196194084-fc500c51-db82-4678-99cf-9e3b65430c9b.png">
<img width="949" alt="Screen Shot 2022-10-17 at 9 46 22 AM" src="https://user-images.githubusercontent.com/110929917/196194096-e9652b9c-f53f-486c-bc77-394de8a6d8cb.png">
<img width="942" alt="Screen Shot 2022-10-17 at 9 46 36 AM" src="https://user-images.githubusercontent.com/110929917/196194112-188215ce-1bb6-4661-8bc2-0d72c500c785.png">
<img width="967" alt="Screen Shot 2022-10-17 at 9 46 45 AM" src="https://user-images.githubusercontent.com/110929917/196194138-194a5ad3-9c7b-4b37-8aa3-1c3a44914af6.png">
<img width="944" alt="Screen Shot 2022-10-17 at 9 46 53 AM" src="https://user-images.githubusercontent.com/110929917/196194147-c5e3209a-7b1c-4af2-9288-8dcf2f52c42f.png">

### Taking log of the target variable:
<img width="935" alt="Screen Shot 2022-10-17 at 9 49 04 AM" src="https://user-images.githubusercontent.com/110929917/196194440-08b67343-49db-431e-a64a-07dddeaeb321.png">

#### Checking for the assumptions for our model:

- Mean of residuals: -1.549921521948453e-15
- Tests for Normality:
<img width="598" alt="Screen Shot 2022-10-17 at 9 50 06 AM" src="https://user-images.githubusercontent.com/110929917/196195630-a5e7930e-64bd-442a-a197-4e911561a9cb.png">

- Linearity of Variables:
<img width="595" alt="Screen Shot 2022-10-17 at 9 50 36 AM" src="https://user-images.githubusercontent.com/110929917/196195805-b2d225fb-8968-423c-88d9-0a14160b81c6.png">

- Heteroscedasticity:
<img width="948" alt="Screen Shot 2022-10-17 at 9 50 48 AM" src="https://user-images.githubusercontent.com/110929917/196195857-7bdcc353-4abc-48af-93d5-9afa0d777c3f.png">

<img width="944" alt="Screen Shot 2022-10-17 at 9 51 13 AM" src="https://user-images.githubusercontent.com/110929917/196195923-4d346645-3db1-4754-b900-0a56045f8114.png">


### Check the performance of the model on the train and test data set

<img width="571" alt="Screen Shot 2022-10-17 at 9 51 38 AM" src="https://user-images.githubusercontent.com/110929917/196195961-8677ced3-8fc8-49d4-a4f0-90713791085e.png">

<img width="949" alt="Screen Shot 2022-10-17 at 9 52 00 AM" src="https://user-images.githubusercontent.com/110929917/196195985-227a0a0f-62f7-433e-920f-8d0312d6df4d.png">


