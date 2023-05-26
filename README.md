# WordUnscramble

## Acceptance Criteria

## Algorithm
* Option = get input from user  
        if option is manual then ask user to enter scrambled word or words comma sepatared  
        if option is file then ask user to enter the full path icluding the file name  
                if the file is not recognized then show warning and ask if user wants to continue   
                      if user chooses yes then go to the first step  
                      if user chooses no then exit application  
        if option is not recognized then show warining and ask if user wants to continue  
                 if user chooses yes then go to the first step  
                 if user chooses no then exit application  
* Load the word list specified by the iser for unscrambling the given scrambled words
* Start matching scrambled words against the loadded word list  
                for each scrambled word in specified scrambled words  
                        for each unscrambled word in word list  
                                if scrambled word == unscrambled word then add to list of matched  
                                otherwise  
                                        sort scrambled word  
                                        sort unscrambled word  
                                        if sorted scrambled word == sorted unscrambled word then add to list of matched  
                 if matches found then show matched scrambled words for all unscrambled words
                 otherwise show message that no matches have been found
* ask if user wants to continue
                if user chooses yes then go to first step
                if user choose no then exit application


## Flowchart



![Word_unscambler](https://github.com/cozyGarage/WordUnscramble/assets/9263674/60e9d8aa-8ce3-43af-8edd-079ceffc90b9)
