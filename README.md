# GT
### (Genial Toil)
#### A Web-Project on Material Management

### Customer Name: SRA Limited
# Requirements
1. Seperate Admin Page
2. Home Page
# Use cases
#### Login – Types
01. Admin Login
02. Employee/Supervisor Login
03. Manager/In-charge Login

### Roles & Responsibilities
#### 01. Admin :-( Servlet-Config)
We are giving authority to create Employee sign in and he can create, update and delete Employee login’s depending on respective Site In-charge instructions. And also to create Manager/Site In-Charge Sign in.
If in case he forgot his id/password, need to contact Application developer.

### Table 01 (employee_tbl)
|   Employee ID   | Employee Name |  Designation  |    Password   |
| -------------   |:-------------:|:-------------:|:-------------:|
|SRA01            |ABC            |Supervisor     | ************* |
|SRA02            |DEF            |Manager        | ************* |
|SRA03            |GHI            |Supervisor     | ************* |
|SRA04            |JKL            |Manager        | ************* |

#### 02. Employee/Supervisor:-
He can only login and do related operations & if in case forgot password or any queries related to sign-in, need to contact admin person.
His roles are, he can do operations like add, update and delete data from Database.
 
### Table 01 (raw_material_tbl)
#### 01. Raw Materials and it's grades
+ Cement
+ Steel
+ Sand
+ Aggregate
+ Admixture
+ Lubricating-Oils
+ Fuel


|  Material Name  |      01       |      02       |      03       |      04       |      05       |      06       |      07       |
| -------------   |:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|
|Cement           |      OPC      |      PSC      |      GGBS     |       PPC     |      RHC      |      LHC      |      QSC      |
|Steel            |      6mm      |      8mm      |      10mm     |      12mm     |      14mm     |      16mm     |      18mm     |
|Coarse Aggregate |     2.36mm    |    4.75mm     |    10.0mm     |      12.5mm   |    16.0mm     |    20.0mm     |    40.0mm     |
|Sand             |     Coarse    |     Fine      |               |               |               |

#### 03. Manager/In-charge:-
Even his login id & password are created by Admin only.
He can view inflow & outflow of data and he can’t edit any field.
He can also view project status as on date.  

#### 02. Hire Bill generation
+ Work Order
+ Bill Generation

