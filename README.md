# <font size=6 face='Calibri'>IMPROVING STRUCTURE-BASED VIRTUAL SCREENING PERFORMANCE VIA LEARNING FROM SCORING FUNCTIONS COMPONENTS</font>

<font size=4.5 face='Calibri'>Here,
we propose a new scoring method named **E**nergy **A**uxiliary **T**erms
**L**earning (EATL) that brought about the idea of analyzing scoring
components generated from multiple scoring functions by machine learning
algorithm to improve the screening performance. </font>

1. <font size=4.5 face='Calibri'> All the feature matrices employed in this study have been stored in two folders, the *AD_Features* and the ‘*DUD-E_features*. Each folder consists of eight CSV-formatted files which are named after their respective targets. Here, the Number, Label (actives=1, decoys=0), Name, and the value of 61 energy auxiliary terms are provided for each molecular.  </font>

2. <font size=4.5 face='Calibri'>The complete cross-validation
   workflow was established in KNIME (version3.7.1), and the readers can
   import it in any updated versions of KNIME, which can be
   downloaded at https://www.knime.com/knime-analytics-platform (Windows version, 64-Bit). </font>

3. <font size=4.5 face='Calibri'>You can obtain the above data through </font>
   ```
   git clone git@github.com:xiongguoli/data_EATs-learning.git
   ```
<font size=4.5 face='Calibri'> You can also download manually under https://drive.google.com/open?id=1_TCGwLULNu3UB4ReCRY3eUVc96i7JhxE.</font>
   
4. <font size=4.5 face='Calibri'>Any other questions, please contact us via oriental-cds@163.com or junoxiong829@gmail.com</font>