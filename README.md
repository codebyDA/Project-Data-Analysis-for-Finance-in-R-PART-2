# Project Data Analysis for Finance: Investor Investment Process in R PART-2

### > BACKGROUND ──

<sup><b>DQLab</b></sup> Project, illustrating about a finance company whose plays a role as a peer-to-peer lending company, so the company requires investors to provide loans to prospective borrowers. Every time a borrower applies for a loan, the company will update the loan to the marketplace and then the investor who has signed up will see the loan, if there is a suitable one, then they will order and then pay.

this <b>project focuses on the analysis of the investment process of the investor. (the behaviour of it)</b>



### > A SIMPLE GUIDE STEP-BY-STEP DATASET PROCESSING (2) ──

#### →   Data exploration

#### →   Data manipulation

#### →   Analyzing the investment process

#### →   Analyzing the time needed until the first investment

#### →   Analyzing the retention invest



### > IMPLEMENTATION R PACKAGES ──

#### ⋈ Package DPLYR ─ suitable for data manipulating & analytic

* `select()`    ⍽ variable selection

* `filter()`    ⍽ variable value filtration
						
* `mutate()`    ⍽ new variable creation based on the existed variable
						
* `summarise()` ⍽ variable value summarization
						
* `arrange()`   ⍽ variable arrangement based on it values

#### ⋈ Package LUBRIDATE ─ suitable for processing the date nor timestamp data-type

* `ymd()`        ⍽ data-formatting (YearMonthDate char. format to date data-type)
						
* `ymd_hms()`    ⍽ data-formatting (YearMonthDate HourMinuteSecond char. format to timestamp data-type)

* `floor_date()` ⍽ round the date / timestamp data type down according to the time-type inputted

#### ⋈ Package GGPLOT2 ─ suitable for data visualization using plot function

            	⌐ syntax :> ggplot(data) + geom_type(aes(x,y,fill,color)) 

#### ⋈ Package SCALES ─ suitable for supporting the process of data exploration

* `comma()`   ⍽ variable format conversion (numerical format + separators)
						
* `percent()` ⍽ variable format conversion (numerical format + percent symbol)

#### ⋈ Package TIDYR ─ suitable for data-formatting (wide to long), excellence at the data preparation process

* `spread()` ⍽ data-formatting (data.frame to wide)
						
* `gather()` ⍽ data-formatting (data.frame to long)



### > INVEST EVENT DATASET ──

#### ⋈ Load <sup><b>DQLab</b></sup> Dataset ::

			⌐ df_event <- read.csv('https://dqlab-dataset.s3-ap-southeast-1.amazonaws.com/event.csv', stringsAsFactors = F)
	
* `stringAsFactors` ⍽ to make the char. data type don't reformat to factor



## > ADDITIONAL INFORMATION ──

#### ⋈ R Vers. 4.0.2

#### ⋈ Rstudio Vers. 1.3.1073
