## EXNO-3-DS

# AIM:
To read the given data and perform Feature Encoding and Transformation process and save the data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Encoding for the feature in the data set.
STEP 4:Apply Feature Transformation for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE ENCODING:
1. Ordinal Encoding
An ordinal encoding involves mapping each unique label to an integer value. This type of encoding is really only appropriate if there is a known relationship between the categories. This relationship does exist for some of the variables in our dataset, and ideally, this should be harnessed when preparing the data.
2. Label Encoding
Label encoding is a simple and straight forward approach. This converts each value in a categorical column into a numerical value. Each value in a categorical column is called Label.
3. Binary Encoding
Binary encoding converts a category into binary digits. Each binary digit creates one feature column. If there are n unique categories, then binary encoding results in the only log(base 2)ⁿ features.
4. One Hot Encoding
We use this categorical data encoding technique when the features are nominal(do not have any order). In one hot encoding, for each level of a categorical feature, we create a new variable. Each category is mapped with a binary variable containing either 0 or 1. Here, 0 represents the absence, and 1 represents the presence of that category.

# Methods Used for Data Transformation:
  # 1. FUNCTION TRANSFORMATION
• Log Transformation
• Reciprocal Transformation
• Square Root Transformation
• Square Transformation
  # 2. POWER TRANSFORMATION
• Boxcox method
• Yeojohnson method

# CODING AND OUTPUT:
<img width="631" height="476" alt="Screenshot 2025-09-19 160802" src="https://github.com/user-attachments/assets/134355fb-2801-404d-b0b0-39d3b6c814bb" />
<img width="801" height="387" alt="Screenshot 2025-09-19 160813" src="https://github.com/user-attachments/assets/0e608461-91c9-4874-8b93-3959a967cd1a" />
<img width="652" height="438" alt="Screenshot 2025-09-19 160822" src="https://github.com/user-attachments/assets/f82cfaba-b3df-4cb3-8109-f985201a4cce" />
<img width="656" height="576" alt="Screenshot 2025-09-19 160911" src="https://github.com/user-attachments/assets/94ea90e1-f0d6-48a7-9fce-1880b0446e2d" />
<img width="588" height="501" alt="Screenshot 2025-09-19 160919" src="https://github.com/user-attachments/assets/e1a74d53-b45b-4e10-9281-995f7a52436c" />
<img width="974" height="430" alt="Screenshot 2025-09-19 160927" src="https://github.com/user-attachments/assets/a00116ce-ea2c-4df0-8ccc-7777624245cc" />
<img width="950" height="633" alt="Screenshot 2025-09-19 160937" src="https://github.com/user-attachments/assets/3849df87-3b8a-4d56-bd24-00a3283eb28c" />
<img width="972" height="578" alt="Screenshot 2025-09-19 160946" src="https://github.com/user-attachments/assets/92ad5812-a13b-4f75-b83c-51ce6a0306bc" />
<img width="1015" height="513" alt="Screenshot 2025-09-19 160955" src="https://github.com/user-attachments/assets/c72c7ab0-5b96-43a5-8cb8-672b33509c1f" />
<img width="557" height="173" alt="Screenshot 2025-09-19 161004" src="https://github.com/user-attachments/assets/f09a41c5-d5ce-45c0-ab83-b4c33603c3eb" />
<img width="958" height="709" alt="Screenshot 2025-09-19 161012" src="https://github.com/user-attachments/assets/14045c25-2afb-4178-a60b-069a29fb7fc1" />
<img width="983" height="628" alt="Screenshot 2025-09-19 161018" src="https://github.com/user-attachments/assets/367c4a60-9318-4dca-a058-636977321a25" />
<img width="985" height="616" alt="Screenshot 2025-09-19 161026" src="https://github.com/user-attachments/assets/e1f305b5-272d-4463-aba7-52947ea33ce1" />
<img width="960" height="624" alt="Screenshot 2025-09-19 161031" src="https://github.com/user-attachments/assets/3e6767f5-d2e7-43d0-8c0c-e5a6110eb661" />
<img width="1062" height="554" alt="Screenshot 2025-09-19 161038" src="https://github.com/user-attachments/assets/c87be090-b1fe-465d-8c4f-b75e4f1f50d7" />
<img width="1046" height="625" alt="Screenshot 2025-09-19 161045" src="https://github.com/user-attachments/assets/b3912a6a-6011-41af-80d5-66239aa1646c" />
<img width="1059" height="544" alt="Screenshot 2025-09-19 161053" src="https://github.com/user-attachments/assets/6b6b75aa-0732-4078-8f70-f53ee2fa74c7" />
<img width="986" height="608" alt="Screenshot 2025-09-19 161101" src="https://github.com/user-attachments/assets/307541b0-84a2-4acc-929a-9109ee4b6a92" />
<img width="1036" height="534" alt="Screenshot 2025-09-19 161107" src="https://github.com/user-attachments/assets/c85dc8aa-f3ca-4324-add1-c58d51850be7" />
<img width="913" height="614" alt="Screenshot 2025-09-19 161113" src="https://github.com/user-attachments/assets/ea25f6d9-78fc-49d5-b900-8b55555cdbed" />
<img width="1106" height="548" alt="Screenshot 2025-09-19 161119" src="https://github.com/user-attachments/assets/5f02fa7d-55ba-43c9-b7ff-50db77a0a6c6" />
<img width="1048" height="604" alt="Screenshot 2025-09-19 161125" src="https://github.com/user-attachments/assets/5966eecd-36f2-4db3-acfe-5a97f3f001ea" />
<img width="1045" height="560" alt="Screenshot 2025-09-19 161131" src="https://github.com/user-attachments/assets/6270e676-d6bc-45b0-88d8-04d24488fb3b" />
<img width="975" height="601" alt="Screenshot 2025-09-19 161136" src="https://github.com/user-attachments/assets/5142cd9e-fd62-47ac-855b-ede9e0d4ffe8" />
<img width="1041" height="548" alt="Screenshot 2025-09-19 161142" src="https://github.com/user-attachments/assets/a8e2d1ca-a23e-428c-9af9-c9244946dffa" />
<img width="970" height="618" alt="Screenshot 2025-09-19 161148" src="https://github.com/user-attachments/assets/0b027c6b-850b-4f7a-9178-e000cd4c90b8" />
<img width="1088" height="608" alt="Screenshot 2025-09-19 161154" src="https://github.com/user-attachments/assets/fd9d3ce1-d8dd-4410-b31e-367b0cc29c5c" />
<img width="970" height="611" alt="Screenshot 2025-09-19 161200" src="https://github.com/user-attachments/assets/101158c7-5f23-4f5c-a696-d719c017ac9d" />



# RESULT:
       # INCLUDE YOUR RESULT HERE

       
