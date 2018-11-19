<!DOCKTYPE html>
<html>
        <html lang="en" dir="ltr"> 
<head>
<body>
    
    <style>
        header {
                position: Centre
        }
        
    </style>
   
    <h1 id="title">Survey Form</h1>
    <div id="form-outer"></div>
    <p id="DESCRIPTION">Let us know how we can improve freeCodeCamp</p>
    <form id="SURVEY FORM"></form>
    <div>id=Name </div>
    
    <div class="rowTab">
        <div class="labels">
            <label id="name-label" for ="name">*Name: </label>
        </div>
        <div class ="rightTab">
                <input autofocus=""type="text" name="name" id="name" class= "input field" placeholder="Enter your name" required="">
               
        </div>
    </div>
    
        <div class="rowTab">
            <div class="labels">
                <label id ="email-label" for="Email">*Email</label>
            </div>
            <div class="rightTab"><input autofocus=""type ="text" name="name" id="name" class="input field" placeholder="Enter your email">
            </div>
        </div>
        
        <div class="rowTab">
            <div class="label">
                <label id="number-label"for ="Age">*Age</label>
            </div>
            <div class="rightTab"><input type="number" name="Age" id="Age" min="1" max="150"class="inpuit field" placeholder="Age">
            </div>
        </div>

        <div class="rowTab">
                <div class="labels">
                        <label id="text-label"for ="Role">*Which option best describes your current role?</label>
                </div>
                    <div class="rightTab">
                        <select id="dropdown" name="Role" class="dropdown">
                            <option disabled="" value="">Select an Option</option>
                            <option value="Engineer">Engineer</option>
                            <option value="Doctor">Doctor</option>
                            <option value="Manager">Manager</option>
                            <option value="Learner">Learner</option>
                            <option value="Recent Graduate">Recent Graduate</option>
                            <option value="Full time Job">Full time Job</option>
                            <option value="Part time Job">Part time Job</option>
                            <option value="Prefer No">Prefer No</option>
                            <option value="Others">Others</option>
                        </select>
                </div>
        </div>
                        <div class="rowTab">
                                <div class="labels">
                                        <label for ="Rating scale">*How likely is that you would recommend freeCodeCamp to a friend?</label>
                                    </div>     
                                    <div class="rightTab">
                                        <ol style="list-style: none;">
                                            <ol class="Radio"><Label>Definitely<input name="Radio Buttons" Value="1" Type="radio" Class="Rating Scale"></Label></ol>
                                            <ol class="Radio"><Label>Maybe<input name="Radio Buttons" Value="2" Type="radio" Class="Rating Scale"></Label></ol>
                                            <ol class="Radio"><Label>Not sure<input name="Radio Buttons" Value="2" Type="radio" Class="Rating Scale"></Label></ol>
                                    </div>  
                                    
                        <div class="rowTab">
                                <div class="labels">
                                        <label for ="Interest">*What do you like most in FCC:</label>
                                </div>  
                                    <div class="rightTab">
                                        <select id="dropdown" name="Role" class="dropdown">
                                            <option disabled="" selected="" value="">Select an Option</option>
                                            <option value="Challenges">Challenges</option>
                                            <option value="Projects">Projects</option>
                                            <option value="Community">Community</option>
                                            <option value="Open Source">Open Source</option>
                                        </select>  
                                    </div>   
                            </div>     
                        
                        <div class="rowTab">
                            <div class="labels">
                                <label for= "Future Improvements">Things that should be improved in the future</label>
                            </div>
                            <div class="rightTab">
                                <ol style="list-style:none">
                                <ol class="checkbox"><label>Front-end Projects<input name="Future Improvements" Value="1" type="checkbox"Class="Rating Scale"></label></ol>
                                <ol class="checkbox"><label>Back-end Projects<input name="Future Improvements" Value="2" type="checkbox"Class="Rating Scale"></label></ol>
                                <ol class="checkbox"><label>Data Visualization<input name="Future Improvements" Value="3" type="checkbox"Class="Rating Scale"></label></ol>
                                <ol class="checkbox"><label>Challenges<input name="Future Improvements" Value="4" type="checkbox"Class="Rating Scale"></label></ol>
                                <ol class="checkbox"><label>Open Source Community<input name="Future Improvements" Value="5" type="checkbox"Class="Rating Scale"></label></ol>
                                <ol class="checkbox"><label>Gitter help rooms<input name="Future Improvements" Value="6" type="checkbox"Class="Rating Scale"></label></ol>
                                <ol class="checkbox"><label>Videos<input name="Future Improvements" Value="7" type="checkbox"Class="Rating Scale"></label></ol>
                                <ol class="checkbox"><label>City Meetups<input name="Future Improvements" Value="8" type="checkbox"Class="Rating Scale"></label></ol>
                                <ol class="checkbox"><label>Wiki<input name="Future Improvements" Value="9" type="checkbox"Class="Rating Scale"></label></ol>
                                <ol class="checkbox"><label>Forum<input name="Future Improvements" Value="10" type="checkbox"Class="Rating Scale"></label></ol>
                                <ol class="checkbox"><label>Additional Courses<input name="Future Improvements" Value="11" type="checkbox"Class="Rating Scale"></label></ol>
                               
                            </div>
                        </div>
                        <div class="rowTab">
                                <div class="labels">
                                    <label for= "Conclusion">Any Comments or Suggestions?</label>
                                </div>
                                <div class="rightTab">
                                        <input autofocus=""type="text" name="name" id="name" class= "input field" placeholder="Enter your comment here ......" required="">
                                </div>
                                <Button id="Submit" type="Submit">Submit</Button>
                        </div>
</div>

    </head>
</body></html>



