# School District Analysis  

## Overview Of School District Analysis 

      The School board want maria and her supervisor using student complete data file in specially, reading and math grades for Thomas High School 9th graders appear to have been altered. and school board did not know how and where. so they us me to replace the math and reading scores for Thomas high school with NaNs and keep the rest of the data intact. so we repat the school district analysis module. which is in two part i did it. as follow first deliverable i Replace ninth grade reading and math scores and got final data frame and second we got distirct Summary DataFrame , School District summary DataFrame. 



## Results

   *  How is the district summary affected?

      First we import data and create path and clean up student names ad replacing prefixes and suffixes and got data without prefixes and suffix. in second steps           using loc method with logical and comparison operators, retrieve the student count for Thomas High School ninth graders in the school_data_complete_df                 DataFrame. In Step 2, subtract the number of students retrieved from Step 1 from the total student count to get the new total student count. calculate the math         and reading passing percentages based on the new total student count. calculate the overall passing percentage with the new total student count. and we got             district summary DataFrame as follow

      ![districtsummarydataframe](https://user-images.githubusercontent.com/103727169/177051341-19b03372-dc0a-4fd7-9015-3c2ee5dc9fda.png)

   *  How is the school summary affected?

      school summary dataframe using 10th to 12th graders from thomas high school, first we calulat the number of 10th to 12th graders in Thomas High school. we create       three new DataFrame fro the 10th to 12th graders from Thomas High School student who passed math and readig then get the number both math and reading together         after that recalcuat percentage of those who passed math and reading both in Thomas High School. finally i replace %passing math, %passing reading %overall             Passing scores.

      ![schoolsummarypassingoverall](https://user-images.githubusercontent.com/103727169/177051364-20170aab-8161-4873-85f1-1ae1629a1f62.png)

   *  How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

      To replacing the ninth graders math and reading scores with Nan in our DataFrame when we calculate school dirstrict performace it will not going to count. only         will get the result of 10th to 12th graders only


   *  How does replacing the ninth-grade scores affect the following:


      *  Math and reading scores by grade

         total student of student_dtat_df was 39170 after we repalce ninth graders student scores we got result come out of total_student_count is 38709 so ninth                graders student was 461.

      *  Scores by school spending

         after we establish spending bins and group names we categorize spending based on the bins on per_school_summary_df which its comes up like this below.

         ![spedingsummary](https://user-images.githubusercontent.com/103727169/177051380-8521fa53-be42-41ca-adce-61fbb5e83793.png)

      *  Scores by school size

         ![schoolsize](https://user-images.githubusercontent.com/103727169/177051391-4469e650-b6f0-45c0-80ba-c343ca1dd6bd.png)

      *  Scores by school type

         ![schooltype](https://user-images.githubusercontent.com/103727169/177051399-a16b23f5-7fa7-4386-9c82-8cbb4d8516c9.png)

### Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced              with NaNs.

we got following result after we updated school district analysis with reading and match scores repalce with Nans. we got result after we replace the 9th             graders with NaNs out data look like following so after that we calulate other graders math and reading passing score size, type, and all the data maria wants.

![s](https://user-images.githubusercontent.com/103727169/177051746-1fbc006a-8de9-496b-8625-895188f6742c.png)
             
             
finally we got our result and represent to maria our final DataFrame.






