Desafíos

1 Analizar los datos de las distribuciones e identificar si hay algún valor o registros que no se deben considerar para el modelo.

2 Investigar qué es y como crear un mapa de calor para analizar la correlación de las variables.

3 Crear una conclusión para cada uno de los gráficos del histograma. Mirar los datos y extraer conclusiones, porque es una habilidad esencial

Descripcion de el dataset
1. Title: German Credit data
2. Source Information
Professor Dr. Hans Hofmann  
Institut f"ur Statistik und "Okonometrie  
Universit"at Hamburg  
FB Wirtschaftswissenschaften  
Von-Melle-Park 5    
2000 Hamburg 13 
3. Number of Instances:  1000
4.  Attribute description for german
default:  (numerical)
	       Category of customer
               0 : Good customer
	       1 : Bad customer
account_check_status:  (qualitative)
	       Status of existing checking account
               1 : < 0 DM
	       2 : 0 <= ... <  200 DM
	       3 : >= 200 DM / salary assignments for at least 1 year
               4 : no checking account
duration_in_month:  (numerical)
	      Duration in month
	       1 :  1 <= ... < 12
	       2 : 12 <= ... < 24
	       3 : 24 <= ... < 36
               4 : 36 <= ... < 48
               5 : 48 <= ... < 60
               6 : 60 <= ... < 72
credit_history:  (qualitative)
	      Credit history
	       1 : no credits taken/all credits paid back duly
               2 : all credits at this bank paid back duly
	       3 : existing credits paid back duly till now
               4 : delay in paying off in the past
	       5 : critical account/other credits existing (not at this bank)
purpose:  (qualitative)
	      Purpose
	       1 : car (new)
	       2 : car (used)
	       3 : furniture/equipment
	       4 : radio/television
	       5 : domestic appliances
	       6 : repairs
	       7 : education
	       8 : (vacation - does not exist?)
	       9 : retraining
	      10 : business
	      11 : others
credit_amount:  (numerical)
	      Credit amount
	        1 :     1 <= ... <  1000
	        2 :  1000 <= ... <  2000
	        3 :  2000 <= ... <  3000
                4 :  3000 <= ... <  4000
                5 :  4000 <= ... <  5000
                6 :  5000 <= ... <  6000
	        7 :  6000 <= ... <  7000
	        8 :  7000 <= ... <  8000
                9 :  8000 <= ... <  9000
               10 :  9000 <= ... < 10000
               11 : 10000 <= ... < 11000
               12 : 11000 <= ... < 12000
               13 : 12000 <= ... < 13000
               14 : 13000 <= ... < 14000
               15 : 14000 <= ... < 15000
               16 : 15000 <= ... < 16000
               17 : 16000 <= ... < 17000
               18 : 17000 <= ... < 18000
               19 : 18000 <= ... < 19000
               20 : 19000 <= ... < 20000
savings:  (qualitative)
	      Savings account/bonds
	        5 :          ... <  100 DM
	        4 :   100 <= ... <  500 DM
	        3 :   500 <= ... < 1000 DM
	        2 :          .. >= 1000 DM
                1 :   unknown/ no savings account
present_emp_since:  (qualitative)
	      Present employment since
	        5 : unemployed
	        4 :       ... < 1 year
	        3 : 1  <= ... < 4 years  
	        2 : 4  <= ... < 7 years
	        1 :       .. >= 7 years
installment_as_income_perc:  (numerical)
	      Installment rate in percentage of disposable income
personal_status_sex:  (qualitative)
	      Personal status and sex
	      1 : male   : divorced/separated
	      2 : female : divorced/separated/married
              3 : male   : single
	      4 : male   : married/widowed
	      5 : female : single
other_debtors: (qualitative)
	      Other debtors / guarantors
	      1 : none
	      2 : co-applicant
	      3 : guarantor
present_res_since: (numerical)
	      Present residence since
property: (qualitative)
	      Property
	      1 : real estate
	      2 : if not A121 : building society savings agreement/life insurance
              3 : if not A121/A122 : car or other, not in attribute 6
	      4 : unknown / no property
age: (numerical)
	      Age in years
	       1 : 18 <= ... < 30
	       2 : 30 <= ... < 40
	       3 : 40 <= ... < 50
               4 : 50 <= ... < 60
               5 : 60 <= ... < 70
               6 : 70 <= ... < 80
other_installment_plans: (qualitative)
	      Other installment plans 
	       1 : bank
	       2 : stores
	       3 : none
housing: (qualitative)
	      Housing
	       1 : rent
	       2 : own
	       3 : for free
credits_this_bank: (numerical)
              Number of existing credits at this bank
job: (qualitative)
	      Job
	       1 : unemployed/ unskilled  - non-resident
	       2 : unskilled - resident
	       3 : skilled employee / official
	       4 : management/ self-employed/highly qualified employee/ officer
people_under_maintenance: (numerical)
	      Number of people being liable to provide maintenance for
telephone: (qualitative)
	      Telephone
	       0 : none
	       1 : yes, registered under the customers name
foreign_worker: (qualitative)
	      foreign worker
	       1 : yes
	       0 : no
