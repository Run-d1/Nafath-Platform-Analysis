# تحليل منصة نفاذ

## نظرة عامة
يتضمن هذا المستودع (repository) تحليلًا لإحصائيات مستخدمي منصة نفاذ حتى تاريخ 3 يوليو 2024.


## عن منصة نفاذ
[نفاذ](https://www.iam.gov.sa/sso/about) هي منصة الهوية الرقمية الوطنية للمملكة العربية السعودية، طورتها الهيئة السعودية للبيانات والذكاء الاصطناعي (سدايا). تهدف المنصة إلى تقديم خدمات رقمية موحدة وآمنة للأفراد والمؤسسات، مما يسهم في تسهيل المعاملات الإلكترونية وتعزيز الأمن السيبراني في مختلف القطاعات.

## محتويات المستودع
- **Data/**: ملف يحتوي على البيانات الخام لإحصائيات منصة نفاذ بصيغة اكسل.
- **Nafath.ipynb**: هو ملف Jupyter Notebook المستخدم في عملية تنظيف البيانات.
- **nafath-dashboard**: صورة لواجهة لوحة التحكم (Dashboard) الخاصة بإحصائيات منصة نفاذ.

## أبرز الرؤى

١. **انتشار المستخدمين**
   - بلغ عدد سكان المملكة في منتصف عام 2024 حوالي **35,300,000** نسمة ([المصدر: الهيئة العامة للإحصاء](https://www.stats.gov.sa/documents/20117/2067012/Population+Estimates+Publication+2024.pdf/aaf4f65c-8a9a-6f52-2490-6eb705e626e6?t=1738828639304))، بينما بلغ عدد مستخدمي منصة نفاذ **23,297,934**، مما يعكس معدل انتشار بنسبة **66.0%** تقريبًا.
   - يشير هذا الرقم إلى اعتماد واسع النطاق للمنصة على مستوى المملكة.

٢. **طلبات المصادقة لكل مستخدم**
   - بلغ إجمالي طلبات المصادقة **2,075,830,418**، بمتوسط **89 طلبًا لكل مستخدم**، ما يعكس الاستخدام المتكرر لخدمات التحقق من الهوية في المنصة.

٣. **التوزيع حسب الجنس**
   - يشكل الذكور **67%** من المستخدمين، بينما تمثل الإناث **33%**.
   - ووفقًا للتقديرات السكانية لمنتصف عام 2024، فإن نسبة الذكور تبلغ تقريبًا **62.25%** ونسبة الإناث **37.85%**.
   - هذا يعني أن نسبة الذكور في المنصة أعلى قليلًا من نسبتهم في المجتمع بشكل عام، ويُستنتج من ذلك أنهم يستخدمون منصة نفاذ بنسبة أعلى مقارنة بالإناث.

٤. **اعتماد التطبيق**
   - تم تحميل تطبيق نفاذ **20.8 مليون مرة** من إجمالي **23.3 مليون مستخدم**، بنسبة اعتماد بلغت **89.3%**.
   - يدل ذلك على أن أغلب المستخدمين يعتمدون على التطبيق للوصول إلى منصة نفاذ، في حين قد يستخدم القليل منهم المنصة عبر الويب.
   - **ملاحظة**: قد يقوم بعض المستخدمين بتحميل التطبيق على أكثر من جهاز.

٥. **التوزيع حسب العمر**
   - الفئة العمرية الأكثر استخدامًا: **30-40 عامًا** بنسبة 31.1%، تليها الفئة **20-30** عامًا بنسبة **28.3%**، مما يشير إلى أن الأفراد في سن العمل يشكلون الجزء الأكبر من قاعدة المستخدمين.
   - تقل معدلات الاستخدام بشكل كبير بعد عمر 50 عامًا، حيث تشكل الفئة العمرية **60-70** عامًا نسبة **2.8%** فقط، وهذا يمكن أن يُعزى إلى ضعف التبني بين كبار السن أو إلى قلة عددهم.


## مصدر البيانات
البيانات مستخلصة من  [بيانات سدايا المفتوحة](https://open.data.gov.sa/ar/datasets/view/8563c70c-c870-41cb-9c75-9a89a0cb4f90/resources).




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

1. **User Penetration**: **66.0%** of Saudi residents use Nafath (23.3M users) out of a population of **35.3M** (as of mid-2024).  
2. **Authentication Requests**: Each user made an average of **89** requests, totaling **2.08 billion** requests.  
3. **Gender Distribution**: **67%** male, **33%** female users.  
4. **App Adoption**: **89.3%** app adoption with **20.8M** downloads out of **23.3M** users.  
5. **Age Distribution**: Largest user group: **30-40 years old** (31.1%), followed by **20-30 years old** (28.3%). Only **2.8%** of users are **60-70** years old.


### **Insights in Detail**

1. **User Penetration**:  
   - As of mid-2024, the Saudi population was approximately 35,300,000. ([Source: General Authority for Statistics](https://www.stats.gov.sa/documents/20117/2067012/Population+Estimates+Statistics+2024+EN.pdf/9b71e303-5fd9-19cb-9913-850a9d521639?t=1738859947691))
   - The Nafath platform had **23,297,934** users, achieving a penetration rate of approximately **66.0%**, indicating widespread adoption nationwide.
   - The mid-2024 population figure is used to align with the last data update timestamp (2024-07-03 16:34:18) from [SDAIA's Open Data](https://open.data.gov.sa/en/datasets/view/8563c70c-c870-41cb-9c75-9a89a0cb4f90/resources), ensuring accuracy and relevance.

2. **Authentication Requests per User**:  
   - With a total of **2,075,830,418** authentication requests and **23,297,934** users, the average number of requests per user was approximately **89**.  
   - This reflects frequent utilization of the platform's identity verification services.

3. **Gender Distribution**:
   - Male users make up **67%** of the platform’s user base, while female users account for **33%**.
   - According to the mid-2024 population, males represent approximately **62.25%** of the population, while females make up **37.85%**.
   - This shows that the percentage of male users on the platform is slightly higher than their share in the general population. This indicates that males use the Nafath platform at a relatively higher rate than females.

4. **User Base vs. App Adoption**:  
   - The platform has achieved an app adoption rate of **89.3%**, with **20,800,000 downloads** among **23,297,934 users**.
   - This indicates that the majority of users access Nafath through the mobile app, while a smaller portion may use the web platform.
   - **Note**: Some users may have downloaded the app on more than one device.

5. **Number of Users by Age**:  
   - The largest user group is aged **30-40**, representing **31.1%** of users, followed by 20-30 (28.3%), indicating that working-age individuals form the core user base.
   - Participation declines significantly after age 50, with only 2.8% of users aged 60-70, highlighting a lower adoption rate among older populations.



## Data Source

The data is sourced from [SDAIA's Open Data](https://open.data.gov.sa/en/datasets/view/8563c70c-c870-41cb-9c75-9a89a0cb4f90/resources).
