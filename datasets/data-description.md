# Описание датасетов

## sleep75

*number of observations* : 706

- age: in years
- black: =1 if black
- case: identifier
- clerical: =1 if clerical worker
- construc: =1 if construction worker
- educ: years of schooling
- earns74: total earnings, 1974
- gdhlth: =1 if in good or excel. health - inlf: =1 if in labor force
- leis1: sleep - totwrk
- leis2: slpnaps - totwrk
- leis3: rlxall - totwrk
- smsa: =1 if live in smsa
- lhrwage: log hourly wage
- lothinc: log othinc, unless othinc < 0
- male: =1 if male
- marr: =1 if married
- prot: =1 if Protestant
- rlxall: slpnaps + personal activs
- selfe: =1 if self employed
- sleep: mins sleep at night, per wk
- slpnaps: minutes sleep, inc. naps
- south: =1 if live in south
- spsepay: spousal wage income
- spwrk75: =1 if spouse works
- totwrk: mins worked per week
- union: =1 if belong to union
- worknrm: mins work main job
- workscnd: mins work second job
- exper: age - educ - 6
- yngkid: =1 if children < 3 present
- yrsmarr: years married
- hrwage: hourly wage
- agesq: age^2

*Источник*: Wooldridge Source: J.E. Biddle and D.S. Hamermesh (1990), “Sleep and the Allocation of Time,” Journal of Political Economy 98, 922-943

## Electricity

*number of observations* : 158

- cost total cost
- q total output
- pl wage rate
- sl cost share for labor
- pk capital price index
- sk cost share for capital
- pf fuel price
- sf cost share for fuel

*Источник*: Christensen, L. and W. H. Greene (1976) “Economies of scale in U.S. electric power generation”, Journal of Political Economy, 84, 655-676.

## Diamond

*number of observations* : 308

- carat weight of diamond stones in carat unit
- colour a factor with levels (D,E,F,G,H,I)
- clarity a factor with levels (IF,VVS1,VVS2,VS1,VS2)
- certification certification body, a factor with levels ( GIA, IGI, HRD)
- price price in Singapore $

*Источник*: Chu, Singfat (2001) “Pricing the C’s of Diamond Stones”, Journal of Statistics Education, 9(2).

## Labour (Belgian firms)

*number of observations* : 569

- capital total fixed assets, end of 1995 (in 1000000 euro)
- labour number of workers (employment)
- output value added (in 1000000 euro)
- wage wage costs per worker (in 1000 euro)

*Источник*: Verbeek, Marno (2004) A Guide to Modern Econometrics, John Wiley and Sons, chapter 4.

## diamonds (Prices of over 50,000 round cut diamonds)

*number of observations* : 53940

- price price in US dollars ($326–$18,823)
- carat weight of the diamond (0.2–5.01)
- cut quality of the cut (Fair, Good, Very Good, Premium, Ideal) 
- color diamond colour, from D (best) to J (worst)
- clarity a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
- x length in mm (0–10.74)
- y width in mm (0–58.9)
- z depth in mm (0–31.8)
- depth total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43–79)
- table width of top of diamond relative to widest point (43–95)

*Источник*: пакет ggplot2 для R

## loanapp

1989 наблюдений, 59 переменных

- occ: occupancy
- loanamt: loan amt in thousands
- action: type of action taken
- msa: msa number of property
- suffolk: =1 if property in suffolk co.
- appinc: applicant income, $1000s
- typur: type of purchaser of loan
- unit: number of units in property
- married: =1 if applicant married
- dep: number of dependents
- emp: years employed in line of work
- yjob: years at this job
- self: =1 if self employed
- atotinc: total monthly income
- cototinc: coapp total monthly income
- hexp: propose housing expense
- price: purchase price
- other: other financing, $1000s
- liq: liquid assets
- rep: no. of credit reports
- gdlin: credit history meets guidelines
- lines: no. of credit lines on reports
- mortg: credit history on mortgage paym
- cons: credit history on consumer stuf
- pubrec: =1 if filed bankruptcy
- hrat: housing exp, percent total inc
- obrat: other oblgs, percent total inc
- fixadj: fixed or adjustable rate?
- term: term of loan in months
- apr: appraised value
- prop: type of property
- inss: PMI sought
- inson: PMI approved
- gift: gift as down payment
- cosign: is there a cosigner
- unver: unverifiable info
- review: number of times reviewed
- netw: net worth
- unem: unemployment rate by industry
- min30: =1 if minority pop. > 30percent
- bd: =1 if boarded-up val > MSA med
- mi: =1 if tract inc > MSA median
- old: =1 if applic age > MSA median
- vr: =1 if tract vac rte > MSA med
- sch: =1 if > 12 years schooling
- black: =1 if applicant black
- hispan: =1 if applicant Hispanic
- male: =1 if applicant male
- reject: =1 if action == 3
- approve: =1 if action == 1 or 2
- mortno: no mortgage history
- mortperf: no late mort. payments
- mortlat1: one or two late payments
- mortlat2: > 2 late payments
- chist: =0 if accnts deliq. >= 60 days
- multi: =1 if two or more units
- loanprc: amt/price
- thick: =1 if rep > 2
- white: =1 if applicant white

## TableF5-1

Labor Supply Data From Mroz (1987), 753 Observations [Source](https://pages.stern.nyu.edu/~wgreene/Text/Edition7/): 1976 Panel Study of Income Dynamics, Mroz(1987).

- LFP = A dummy variable = 1 if woman worked in 1975, else 0
- WHRS = Wife's hours of work in 1975
- KL6 = Number of children less than 6 years old in household
- K618 = Number of children between ages 6 and 18 in household
- WA = Wife's age
- WE = Wife's educational attainment, in years
- WW = Wife's average hourly earnings, in 1975 dollars
- RPWG = Wife's wage reported at the time of the 1976 interview (not = 1975 estimated wage)
- HHRS = Husband's hours worked in 1975
- HA = Husband's age
- HE = Husband's educational attainment, in years
- HW = Husband's wage, in 1975 dollars
- FAMINC = Family income, in 1975 dollars
- WMED = Wife's mother's educational attainment, in years
- WFED = Wife's father's educational attainment, in years
- UN = Unemployment rate in county of residence, in percentage points.
- CIT = Dummy variable = 1 if live in large city (SMSA), else 0
- AX = Actual years of wife's previous labor market experience

## TableF7-3

Expenditure and Default Data, 13,444 observations [Source](https://pages.stern.nyu.edu/~wgreene/Text/Edition7/): Greene (1992)

- Cardhldr = Dummy variable, 1 if application for credit card accepted, 0 if not
- Default = 1 if defaulted 0 if not (observed when Cardhldr = 1, 10,499 observations),
- Age = Age in years plus twelfths of a year,
- Adepcnt = 1 + number of dependents,
- Acadmos = months living at current address,
- Majordrg = Number of major derogatory reports,
- Minordrg = Number of minor derogatory reports,
- Ownrent = 1 if owns their home, 0 if rent
- Income = Monthly income (divided by 10,000),
- Selfempl = 1 if self employed, 0 if not,
- Inc_per = Income divided by number of dependents,
- Exp_Inc = Ratio of monthly credit card expenditure to yearly income,
- Spending = Average monthly credit card expenditure (for Cardhldr = 1),
- Logspend = Log of spending.

## Mishkin

monthly observations from 1950-2 to 1990-12

*number of observations* : 491

*country* : United States

- pai1: one-month inflation rate (in percent, annual rate)
- pai3: three-month inflation rate (in percent, annual rate)
- tb1: one-month T-bill rate (in percent, annual rate)
- tb3: three-month T-bill rate (in percent, annual rate)
- cpi: CPI for urban consumers, all items (the 1982-1984 average is set to 100)

*Источник*: Mishkin, F. (1992) “Is the Fisher effect for real ?”, Journal of Monetary Economics, 30, 195-215.

## Tbrate

*quarterly observations* from 1950-1 to 1996-4

*number of observations8 : 188

*country* : Canada

- r: the 91-day treasury bill rate
- y: the log of real GDP
- pi: the inflation rate