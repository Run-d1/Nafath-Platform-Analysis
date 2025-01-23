# تحليل منصة نفاذ

## نظرة عامة
يتضمن هذا المستودع (repository) تحليلًا لإحصائيات مستخدمي منصة نفاذ حتى تاريخ 3 يوليو 2024.


## عن منصة نفاذ
نفاذ هي منصة الهوية الرقمية الوطنية للمملكة العربية السعودية، طورتها الهيئة السعودية للبيانات والذكاء الاصطناعي (سدايا). تهدف المنصة إلى تقديم خدمات رقمية موحدة وآمنة للأفراد والمؤسسات، مما يسهم في تسهيل المعاملات الإلكترونية وتعزيز الأمن السيبراني في مختلف القطاعات.

## محتويات المستودع
- **Data/**: ملف يحتوي على البيانات الخام لإحصائيات منصة نفاذ بصيغة اكسل.
- **Nafath.ipynb**: هو ملف Jupyter Notebook المستخدم في عملية تنظيف البيانات.
- **nafath-dashboard**: صورة لواجهة لوحة التحكم (Dashboard) الخاصة بإحصائيات منصة نفاذ.

## أبرز الرؤى

١. **انتشار المستخدمين**
   - يبلغ عدد سكان المملكة (يوليو 2024) حوالي **33,962,800** نسمة، بينما بلغ عدد مستخدمي منصة نفاذ **23,297,934**، مما يعكس معدل انتشار بنسبة **68.6%**.
   - يشير هذا الرقم إلى اعتماد واسع النطاق للمنصة على مستوى المملكة.

٢. **طلبات المصادقة لكل مستخدم**
   - بلغ إجمالي طلبات المصادقة **2,075,830,418**، بمتوسط **89 طلبًا لكل مستخدم**، ما يعكس الاستخدام المتكرر لخدمات التحقق من الهوية في المنصة.

٣. **التوزيع حسب الجنس**
   - يشكل الذكور **67%** من المستخدمين، بينما تمثل الإناث **33%**، يظهر ذلك أن الذكور يشكلون نسبة أكبر من مستخدمي نفاذ.

٤. **اعتماد التطبيق**
   - تم تحميل تطبيق نفاذ **20.8 مليون مرة** من إجمالي **23.3 مليون مستخدم**، بنسبة اعتماد بلغت **89.3%**.
   - يدل ذلك على أن أغلب المستخدمين يعتمدون على التطبيق للوصول إلى منصة نفاذ، في حين قد يستخدم القليل منهم المنصة عبر الويب.
   - **ملاحظة**: قد يقوم بعض المستخدمين بتحميل التطبيق على أكثر من جهاز.

٥. **التوزيع حسب العمر**
   - الفئة العمرية الأكثر استخدامًا: **30-40 عامًا** بنسبة 31.1%، تليها الفئة **20-30** عامًا بنسبة **28.3%**، مما يشير إلى أن الأفراد في سن العمل يشكلون الجزء الأكبر من قاعدة المستخدمين.
   - تقل معدلات الاستخدام بشكل كبير بعد عمر 50 عامًا، حيث تشكل الفئة العمرية **60-70** عامًا نسبة **2.8%** فقط، وهذا يمكن أن يُعزى إلى ضعف التبني بين كبار السن أو إلى قلة عددهم.


## مصدر البيانات
البيانات مستخلصة من  [بيانات سدايا المفتوحة](https://open.data.gov.sa/en/datasets/view/8563c70c-c870-41cb-9c75-9a89a0cb4f90/resources).




# Nafath Platform Analysis

## Overview

This repository provides an analysis of the Nafath platform's user statistics as of July 3, 2024.


## About Nafath

[Nafath](https://www.iam.gov.sa/sso/about) is the Saudi National Digital Identity Management platform developed by the Saudi Data and Artificial Intelligence Authority (SDAIA). It aims to provide secure and unified digital identity services to individuals and organizations within the Kingdom. This platform plays a crucial role in facilitating digital transactions and enhancing cybersecurity across various sectors.


## Repository Contents

- **Data/**: Contains the raw Excel file with Nafath Platform Statistics.
- **Nafath.ipynb**: Is the Jupyter Notebook used for the data cleaning process.
- **nafath-dashboard**: Is an image of the 'Nafath Platform Statistics' dashboard.


## Key Insights

### **Summarized Insights**

1. **User Penetration**: **68.6%** of Saudi residents use Nafath (23.3M users) out of a population of **33.96M** (as of July 2024).  
2. **Authentication Requests**: Each user made an average of **89** requests, totaling **2.08 billion** requests.  
3. **Gender Distribution**: **67%** male, **33%** female users.  
4. **App Adoption**: **89.3%** app adoption with **20.8M** downloads out of **23.3M** users.  
5. **Age Distribution**: Largest user group: **30-40 years old** (31.1%), followed by **20-30 years old** (28.3%). Only **2.8%** of users are **60-70** years old.


### **Insights in Detail**

1. **User Penetration**:  
   - As of July 2024, the Saudi population was approximately 33,962,800. ([Source: World Population Review](https://worldpopulationreview.com/countries/saudi-arabia))
   - The Nafath platform had **23,297,934** users, achieving a penetration rate of **68.6%**, indicating widespread adoption nationwide.
   - The July 2024 population figure is used to align with the last data update timestamp (2024-07-03 16:34:18) from [SDAIA's Open Data](https://open.data.gov.sa/en/datasets/view/8563c70c-c870-41cb-9c75-9a89a0cb4f90/resources), ensuring accuracy and relevance.

2. **Authentication Requests per User**:  
   - With a total of **2,075,830,418** authentication requests and **23,297,934** users, the average number of requests per user was approximately **89**.  
   - This reflects frequent utilization of the platform's identity verification services.

3. **Gender Distribution**:
   - Male users make up **67%** of the platform’s user base, while female users account for **33%**.
   - This shows that male users represent a larger share of the platform's user base.

4. **User Base vs. App Adoption**:  
   - The platform has achieved an app adoption rate of **89.3%**, with **20,800,000 downloads** among **23,297,934 users**.
   - This indicates that the majority of users access Nafath through the mobile app, while a smaller portion may use the web platform.
   - **Note**: Some users may have downloaded the app on more than one device.

5. **Number of Users by Age**:  
   - The largest user group is aged **30-40**, representing **31.1%** of users, followed by 20-30 (28.3%), indicating that working-age individuals form the core user base.
   - Participation declines significantly after age 50, with only 2.8% of users aged 60-70, highlighting a lower adoption rate among older populations.



## Data Source

The data is sourced from [SDAIA's Open Data](https://open.data.gov.sa/en/datasets/view/8563c70c-c870-41cb-9c75-9a89a0cb4f90/resources).
