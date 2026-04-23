# Case-Structure-in-LabVIEW

Contains one or more subdiagrams, or cases, exactly one of which executes when the structure executes. The value wired to the case selector determines which case to execute.

<img width="212" height="89" alt="image" src="https://github.com/user-attachments/assets/38ea40c5-4c0d-451c-a165-7f6c222bbbd1" />

# Components of a Case Structure
	
<img width="444" height="291" alt="image" src="https://github.com/user-attachments/assets/1a7af039-d4c6-4639-b4a1-98a8c812e724" />
---------------------------------------------------------------------------------
<img width="444" height="291" alt="image" src="https://github.com/user-attachments/assets/acbe65f1-1cd7-48be-8a0a-724603b3e368" />

1. Selector label—Displays the value(s) for which the associated case executes. You can specify a single value or a range of values. You also can use the selector label to specify a default case.
   
2. Subdiagram(case)—Contains the code that executes when the value wired to the case selector matches the value that appears in the selector label. To modify the number or order of subdiagrams, right-click the border of the Case structure and select the appropriate option.
   
3. Case selector—Selects which case to execute based on the value of the input data. The input data can be a Boolean, string, integer, enumerated type or error cluster. The data type you wire to the case selector   determines the allowed cases you can enter in the selector label.
