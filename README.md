# Flight Delay Prediction Challenge [...](https://zindi.africa/competitions/ai-tunisia-hack-5-predictive-analytics-challenge-2)
 !["image"](https://zindpublic.blob.core.windows.net/public/uploads/competition/image/31/thumb_4d7026c0-6938-4a9d-a127-a420ac94603c.jpeg)


## Descprition
Predict airline delays for Tunisian aviation company, Tunisair.
We are going to build a Machine Learning model to predict the delays of Tunisair flights.
## Evaluation
The metric used for this challenge is Root Mean Square Error.
It means that we have to measure a kind of average delay error and reduce that.
## Dataset

Files available:

- Train.csv - the training file
- Test.csv - the test file
- SampleSubmission.csv - is an example of what your submission file should look like. The order of the rows does not matter, but the names of the IDs must be correct. The column "target" is your prediction.



Variable definitions ['ID', 'DATOP', 'FLTID', 'DEPSTN', 'ARRSTN', 'STD', 'STA', 'STATUS',
       'AC', 'target'] :
- ID - Id of record
- DATOP - Date of flight 
- FLTID - Id of flight ( like id of bus line )
- DEPSTN - Departure point
- ARRSTN - Arrival point
- STD - Scheduled Time departure
- STA - Scheduled Time arrival
- STATUS - Flight status
- AC - Aircraft Code
- target - Flight Delay ( in minutes ) 