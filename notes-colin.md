
Feedback on:

1. Stockassessment.org models - break / stop if model fit is older than data changes

2. 
  a. run taf.bootstrap automatically if committed changes are related to files in the bootstrap/ folder
  
  b. 
    - if bootstrap changed - run taf.bootstrap, data, model, output, report
    - if data changed - run data, model, output, report
    - if model changed - run model, output report
    - etc.
  
3. Commit user results to Master branch?  This will allow us to check what the user gets versus what the server produces

4. Provide a non-git / non-github methods to upload code and data

5. suggestion: only install r package, and do not refresh data or software

6. more workers working in parallel

7. job list / feedback about position in the queue

----

## Ideas for 'quality scoring' an assessment

* complete metadata (automatic)
* code comments and clarity / readability (human review)
* Before: After: match with what happens
* ...
