so i was thinking of adding a UI to this. it will have multiple options to pertubrate, diffuse, run pipeline, run brute, run batch brute. All the options will be picked from the json files. User can make any real time changes in the options in the UI if they want but those changes will be for that specific run only. The permanent options will be the jsons as before. Any permanent changes must be made in the json only. During a run, all the real time updates must be visible to the user, what is happening, etc etc. the output etc etc. The history of all previous runs must appear in their specific sections(pertubrate, diffuse, run pipeline, run brute, run batch brute). It is your choice how you want to control this history in the backend. Additional requests - 

For plain brute - 
I should be able to see the specific run happening in real time, which run is happening, see the diffusions in real time, see the match percentage from different deepface models in real time. And then the mean at the last. There should also be a meter showing the lowest and highest percentages recorded till now and their details like run number etc etc and the options to see the images produced in that run and its detailed report or anything etc. I should be able to see these details about each run anytime i want to, after the run, during the run, anytime. No of successful and unsuccesful attempts should also be shown at the side or wherever you want.

About the real time viewing and animations, it should like this

[original image] ------------------- [pertubrated image]
            |                                                     |
            |                                                     |
            |                                                     |
            |                                                     |
            |                                                     |
[original diffused]----------------[pertubrated diffused]

Deepface models - Model1   Model2    Model3    Model4   Model4  Model5
                                   53%          45%    --(pending)   86%         55%        70%

Mean - (the real time mean of all the models that have run till now, to be updated as more model results keep coming back)

The different images i draw in the ascii art should appear as empty boxes until they are generated in real time. Then the deepface models should show processing like a swirving circle to show processing. I think you are getting me. 

This all should happen for every run. 

Requests for batch brute - 
All the things i wrote in brute. The min and max percentage run should still be shown at the side including the min and max percentage of the current combination and of all the combinations till now. 
The current combination which is running should be shown at the top. All the necessary info should be shown. I should be able to view the already ran runs for all the combinations. I should be able to view the queue that the different combinations are in. 

The current cli functionality should not be disturbed at all and should run as it is currently running right now. Make the UI/backend(id needed) on top of it

This is the prompt i am about to give in the main sessions. What are your improvements or suggestions. Is this even possible to do
