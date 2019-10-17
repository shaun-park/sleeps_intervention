# sleeps_intervention

## Feature description
### Demographic data header
* Age(number)
* Gender(1, 2)  
1: man  
2: woman  
* Education(number)
* Alcohol_per_month(number)  
Number of alcohol consumption per month
* Coffee_per_day(number)  
Number of coffee consumption per day
* Exercise_per_week(number)  
Number of exercising per week
* Smoking_per_day(number)  
Number of smoking per day

### Seperator between participants
* Mobile1andWeb2(1 or 2)  
Mobile application(Sleeps) user: 1  
Web-based education participants: 2

### Insomnia Severity Index(ISI_X)
ISI_B shows baseline ISI score before experiment, and ISI_0~7 shows ISI score measured during experiment period.
ISI_F shows ISI score measured after the experiment period. 
Each score is calculated between 0 to 28(severe).
* ISI_B(number)  
* ISI_0(number)
* ISI_3(number)
* ISI_5(number)
* ISI_7(number)

### Patient Health Questionnaire-9(PHQ_X)
PHQ_0~7 shows PHQ-9 score measured during the experiment period. 
PHQ_F shows PHQ-9 score measured after the experiment period.
Each score is calculated between 0 to 27(severe).
* PHQ_0(number)
* PHQ_3(number)
* PHQ_5(number)
* PHQ_7(number)
* PHQ_F(number)

### Sleep Efficiency(SE_XX)
Sleep efficiency(SE) value is measured by _sleep_min / onbed_min_, as a ratio.
Each value is calculated between 0 to 1
* SE_2(ratio)
* SE_3(ratio)
* SE_23(ratio)  
shows merged SE of week 2 and 3
* SE_4(ratio)
* SE_5(ratio)
* SE_45(ratio)  
shows merged SE of week 4 and 5
* SE_6(ratio)
* SE_7(ratio)
* SE_67(ratio)  
shows merged SE of week 6 and 7
* SE_4567(ratio)  
shows merged SE of week 4, 5, 6, 7

### Wake after sleep onset(WASO_X)
Wake after sleep onset(WASO) is defined by the time participants spend awake after initially falling asleep and before they wake up.
* WASO_2(min)
* WASO_3(min)
* WASO_23(min)
* WASO_4(min)
* WASO_5(min)
* WASO_45(min)
* WASO_6(min)
* WASO_7(min)
* WASO_67(min)
* WASO_4567(min)

### Number of Awakenings(AWAN_X)
Number of Awakenings(AWAN) factor indicates number af awakenings during sleep.
* AWAN_2(number)
* AWAN_3(number)
* AWAN_23(number)
* AWAN_4(number)
* AWAN_5(number)
* AWAN_45(number)
* AWAN_6(number)
* AWAN_7(number)
* AWAN_67(number)
* AWAN_4567(number)

### Total sleep time(TST_X)
Total sleep time(TST) factor indicates total length of sleep time in minutes. 
* TST_2(min)
* TST_3(min)
* TST_23(min)
* TST_4(min)
* TST_5(min)
* TST_45(min)
* TST_6(min)
* TST_7(min)
* TST_67(min)
* TST_4567(min)

### Compliance separator: Compliance_good1(None, 1, 2)
* Participants of online-based education: None
* Participants with good compliance: 1
* Participants with bad compliance: 2  
